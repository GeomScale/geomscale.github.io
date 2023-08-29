---
layout: single
title: "Enhancing Volesti R Package: A Journey Towards Improved Performance and Testability"
date: 2023-08-27
author: Soumya Tarafder
author_profile: true
read_time: true
comments: true
share: true
related: true
hidden: false
---

<div style="text-align:center;">
  <br>
  <b>Soumya Tarafder</b>
  <br>
  <b>GSoC 2023 | GeomScale | IIT Kharagpur</b>
  <br>
  <br>
</div>

## Introduction:

Here's a detailed overview of the progress achieved during the **Google Summer of Code (GSoC) 2023**, focusing on refining the **Volesti R Package** for **GeomScale**.

Throughout this venture, several key aspects of the project were thoroughly examined, including the strategic restructuring of the repository, the integration of comprehensive tests and optimization efforts to boost the package's overall performance.

- **Repository Restructuring:**

    Merged PR Link: [https://github.com/GeomScale/Rvolesti/pull/1](https://github.com/GeomScale/Rvolesti/pull/1)

    **Overview:** One of the principal objectives encompassed the establishment of a dedicated repository for the **Volesti R Package**, in light of the prior amalgamation of both **R** and **C++** code within a singular repository, which subsequently posed organizational complexities. In response, a conscientious endeavor was undertaken to restructure the repository framework for the stable **Volesti** version **1.1.2-6**. This endeavor involved the segregation of the **R** package code into a distinct repository denominated as **Rvolesti**, resulting in heightened lucidity and a more streamlined developmental approach.

    In order to facilitate seamless cohesion between the **Rvolesti** and **Volesti** repositories, the implementation of **Git Submodule** was undertaken. This strategic step enabled the **Rvolesti** repository to seamlessly retrieve the requisite **Header Files** from the **Volesti** repository.

- **Integration of Comprehensive Tests:**

    Merged PR Link: [https://github.com/GeomScale/Rvolesti/pull/5](https://github.com/GeomScale/Rvolesti/pull/5)

    **Overview:** Ensuring the dependability and resilience of the **Volesti R Package** necessitated the incorporation of thorough testing mechanisms. In pursuit of this goal, emphasis was placed on the implementation of **CI** tests through the utilization of **GitHub Actions**. Specifically, the **rcmdcheck** package was utilized to execute static analysis and validate the **R** package comprehensively.

- **Elimination of the Test Notes with .Rbuildignore:**

    Merged PR Link: [https://github.com/GeomScale/Rvolesti/pull/6](https://github.com/GeomScale/Rvolesti/pull/6)

    **Overview:** During the **CI** testing phase, there were instances where unnecessary **Notes** were generated, posing a potential for ambiguity. In response, efforts were channeled towards the integration of the **.Rbuildignore** file into the **Rvolesti** repository. This file facilitated the exclusion of certain files or elements from the testing procedure.

- **Modification of the R Codes:**

    Merged PR Link: [https://github.com/GeomScale/Rvolesti/pull/7](https://github.com/GeomScale/Rvolesti/pull/7)

    **Overview:** Upon the establishment of the initial framework, a requirement emerged to integrate the latest functionalities into **Rvolesti**. Subsequently, the process of replicating the **R** files from the **develop** branch of **Volesti** was initiated, leading to the assimilation of the following functions:

    - **ess()**
    - **geweke()**
    - **ode_solve()**
    - **psrf_multivariate()**
    - **psrf_univariate()**
    - **raftery()**
    <br><br>

- **Deletion of C++ Modules:**

    Merged PR Link: [https://github.com/GeomScale/Rvolesti/pull/12](https://github.com/GeomScale/Rvolesti/pull/12)

    **Overview:** To resolve the challenges posed by the **CI** tests post the assimilation of the latest code, distinct **Class Files** were incorporated into the **R** directory. The files, specifically **HpolytopeClass.R**, **SpectrahedronClass.R**, **VpolytopeClass.R**, **VpolytopeIntersectionClass.R**, and **ZonotopeClass.R**, had earlier been realized as a **C++** module.

## **Other Works:**

In addition to the tasks previously outlined, several other issues pertinent to both **Volesti** and **Rvolesti** were addressed. Notable among these were:

- **Modification of the cran_include Branch of Volesti**<br>
    PR Link: [https://github.com/GeomScale/volesti/pull/277](https://github.com/GeomScale/volesti/pull/277)

- **Restructuring the README.md in Rvolesti**<br>
    PR Link: [https://github.com/GeomScale/Rvolesti/pull/14](https://github.com/GeomScale/Rvolesti/pull/14)

## **Conclusion:**

Lastly, it is important to note that **Rvolesti** is a newly established repository that may necessitate further refinement to attain full functionality. The prospect of contributing towards enhancing its functionality is an endeavor that holds a strong appeal and interest.

## **Acknowledgement:**

I extend my heartfelt gratitude to the **GeomScale** community for providing an enriching environment for development and growth. And the insights and expertise shared by my mentors, **Apostolos Chalkis** and **Vissarion Fisikopoulos**, have been instrumental in shaping this journey.