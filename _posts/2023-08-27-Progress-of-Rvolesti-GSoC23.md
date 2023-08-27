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
  <b style="font-size:25px">Enhancing Volesti R Package: A Journey Towards Improved Performance and Testability</b>
  <br>
  by
  <br>
  <b>Soumya Tarafder</b>
  <br>
  <b>GSoC 2023 | GeomScale | IIT Kharagpur</b>
  <br>
  <br>
</div>

## Introduction:

Here's a detailed overview of the progress achieved during the <b>Google Summer of Code (GSoC) 2023</b>, focusing on refining the <b>Volesti R Package</b> for <b>GeomScale</b>.

Throughout this venture, several key aspects of the project were thoroughly examined, including the strategic restructuring of the repository, the integration of comprehensive tests and optimization efforts to boost the package's overall performance.

- <b>Repository Restructuring:</b>

    Merged PR Link: <b>https://github.com/GeomScale/Rvolesti/pull/1</b>

    <b>Overview:</b> One of the principal objectives encompassed the establishment of a dedicated repository for the <b>Volesti R Package</b>, in light of the prior amalgamation of both <b>R</b> and <b>C++</b> code within a singular repository, which subsequently posed organizational complexities. In response, a conscientious endeavor was undertaken to restructure the repository framework for the stable <b>Volesti</b> version <b>1.1.2-6</b>. This endeavor involved the segregation of the <b>R</b> package code into a distinct repository denominated as <b>Rvolesti</b>, resulting in heightened lucidity and a more streamlined developmental approach.

    In order to facilitate seamless cohesion between the <b>Rvolesti</b> and <b>Volesti</b> repositories, the implementation of <b>Git Submodule</b> was undertaken. This strategic step enabled the <b>Rvolesti</b> repository to seamlessly retrieve the requisite <b>Header Files</b> from the <b>Volesti</b> repository.

- <b>Integration of Comprehensive Tests:</b>

    Merged PR Link: <b>https://github.com/GeomScale/Rvolesti/pull/5</b>

    <b>Overview:</b> Ensuring the dependability and resilience of the <b>Volesti R Package</b> necessitated the incorporation of thorough testing mechanisms. In pursuit of this goal, emphasis was placed on the implementation of <b>CI</b> tests through the utilization of <b>GitHub Actions</b>. Specifically, the <b>rcmdcheck</b> package was utilized to execute static analysis and validate the <b>R</b> package comprehensively.

- <b>Elimination of the Test Notes with .Rbuildignore:</b>

    Merged PR Link: <b>https://github.com/GeomScale/Rvolesti/pull/6</b>

    <b>Overview:</b> During the <b>CI</b> testing phase, there were instances where unnecessary <b>Notes</b> were generated, posing a potential for ambiguity. In response, efforts were channeled towards the integration of the <b>.Rbuildignore</b> file into the <b>Rvolesti</b> repository. This file facilitated the exclusion of certain files or elements from the testing procedure.

- <b>Modification of the R Codes:</b>

    Merged PR Link: <b>https://github.com/GeomScale/Rvolesti/pull/7</b>

    <b>Overview:</b> Upon the establishment of the initial framework, a requirement emerged to integrate the latest functionalities into <b>Rvolesti</b>. Subsequently, the process of replicating the <b>R</b> files from the <b>develop</b> branch of <b>Volesti</b> was initiated, leading to the assimilation of the following functions:

    - <b>ess()</b>
    - <b>geweke()</b>
    - <b>ode_solve()</b>
    - <b>psrf_multivariate()</b>
    - <b>psrf_univariate()</b>
    - <b>raftery()</b>
    <br><br>

- <b>Deletion of C++ Modules:</b>

    Merged PR Link: <b>https://github.com/GeomScale/Rvolesti/pull/12</b>

    <b>Overview:</b> To resolve the challenges posed by the <b>CI</b> tests post the assimilation of the latest code, distinct <b>Class Files</b> were incorporated into the <b>R</b> directory. The files, specifically <b>HpolytopeClass.R</b>, <b>SpectrahedronClass.R</b>, <b>VpolytopeClass.R</b>, <b>VpolytopeIntersectionClass.R</b>, and <b>ZonotopeClass.R</b>, had earlier been realized as a <b>C++</b> module.

## <b>Other Works:</b>

In addition to the tasks previously outlined, several other issues pertinent to both <b>Volesti</b> and <b>Rvolesti</b> were addressed. Notable among these were:

- <b>Modification of the cran_include Branch of Volesti</b><br>
    PR Link: <b>https://github.com/GeomScale/volesti/pull/277</b>

- <b>Restructuring the README.md in Rvolesti</b><br>
    PR Link: <b>https://github.com/GeomScale/Rvolesti/pull/14</b>

## <b>Conclusion:</b>

Lastly, it is important to note that <b>Rvolesti</b> is a newly established repository that may necessitate further refinement to attain full functionality. The prospect of contributing towards enhancing its functionality is an endeavor that holds a strong appeal and interest.

## <b>Acknowledgement:</b>

I extend my heartfelt gratitude to the <b>GeomScale</b> community for providing an enriching environment for development and growth. And the insights and expertise shared by my mentors, <b>Apostolos Chalkis</b> and <b>Vissarion Fisikopoulos</b>, have been instrumental in shaping this journey.


<div style="text-align:center;">
  <br>
  <br>
  <b style="font-size:25px">Thank You</b>
</div>