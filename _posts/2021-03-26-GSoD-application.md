---
layout: single
title: "Create the GeomScale Reference Documentation"
date: 2021-03-26
author: GeomScale
author_profile: true
read_time: true
comments: true
share: true
related: true
hidden: false
---


# Create the GeomScale Reference Documentation

> Open call for documentation development

## About the organization

GeomScale is a research and development project that delivers open source code for
state-of-the-art algorithms at the intersection of *data science*, *optimization*, *geometric*,
and *statistical computing*. The current focus of GeomScale is scalable algorithms for
sampling from high-dimensional distributions, integration, convex optimization,
and their applications. One of our ambitions is to fill the gap between theory and
practice by turning state-of-the-art theoretical tools in geometry and optimization
to state-of-the-art implementations. We believe that towards this goal, we will
deliver various innovative solutions in a variety of application fields, like finance,
computational biology, and statistics that will extend the limits of contemporary
computational tools. GeomScale aims in serving as a building block for an international,
interdisciplinary, and open community in high dimensional geometrical and statistical
computing.

The main development is currently performed in volesti, a generic open
source `C++` library, with `R` and `Python` interfaces, for high-dimensional sampling,
volume approximation, and copula estimation for financial modelling.
In particular, the current implementation scales up to hundred or thousand
dimensions, depending on the problem. It is the most efficient software package
for sampling and volume computation to date. It is faster by orders of magnitude
compared to packages that solve the same problems in several cases.
It can compute challenging multivariate integrals and approximate optimal
solutions in optimization problems.

It has already found important applications
in systems biology, for [analyzing large metabolic networks](https://arxiv.org/pdf/2012.05503.pdf)
(e.g., the latest human network), and in FinTech for detecting shock events and
evaluating portfolios performance in stock markets with thousands of assets.
Other application areas include AI and in particular approximate weighted
model integration and data-driven power systems in control.

## About the project

### The problem

GeomScale develops scientific and research oriented software, therefore,
detailed and well written documentation is an important requirement to reach the
communities, the users, the practitioners,  and the researchers it may concern.

GeomScale’s software can solve several complex and high dimensional problems efficiently
in various fields; so our aim now is to create the essential tools to make it well-known
and easily accessible across open source communities.

The main bottleneck for onboarding new contributors to GeomScale is the nature
of the project that requires knowledge from various fields of advanced applied
mathematics and theoretical computer science. The creation of a complete and
detailed documentation will be a valuable tool towards overcoming that burden.
Therefore, solid documentation is a stepping stone to grow our organization to
become the reference open source software in geometric and statistical computing
in high dimensions.

We aim to adopt the documentation system of [divio](https://documentation.divio.com/).

According to this system there are four types of documentation:

- learning-oriented *tutorials*
- problem-oriented *how-to guides*
- understanding-oriented *explanations*
- information-oriented *technical reference*

![](https://documentation.divio.com/_images/overview.png)

### The project’s scope

The GeomScale project will:

- Audit and collect the existing documentation currently distributed in README documents, code comments and tutorials and create a friction log.
- Using the friction log as a guide for understanding the gaps in the currently fragmented documentation, create a complete reference documentation for volesti using the doxygen system.
- Update the current README and contributors’ tutorial to help potential contributors, inaugural to git, GitHub and pull requests.
- Incorporate feedback from documentation testers (volunteers in the project) and the wider GeomScale community.
- Collaborate with GeomScale project administrators to select the right platform to upload the reference documentation. There are two choices here:  [readthedocs](https://readthedocs.org)
(via the [Sphinx](https://www.sphinx-doc.org/en/master/) system) or
[github pages](https://pages.github.com/).

Work that is out-of-scope for this project:

- This project will not create any explanation, tutorials or how-to guides.


## Measuring your project’s success

GeomScale receives an average of 15 pull requests a quarter to add a new feature or optimization or propose a bug fix.
The majority of these pull requests (>80%) are from previous contributors.
We believe that this improved documentation will result in more pull requests
and more pull requests from new contributors.

We will track three metrics:
(a) number of new feature pull requests,
(b) number of pull requests from new contributors,
(c) standard metrics (number of views, downloads, web traffic to GeomScale site, time on page),
monthly after the documentation is published. We will also track the number
of contributors who have made more than three contributions overall,
starting quarterly after the documentation is published.

We would consider the project successful if, after publication of the new documentation at least three of the following hold:
- The number of new feature pull requests increases by 10%
- The number of pull requests from new contributors increases by 15%
- The number of contributors who have made >2 contributions increases by 5% (beginning the quarter after the documentation is published)
- The standard metrics increased by 10% on average
- The number of forks and stars in our repository increased by 10%

## Project budget

| Budget item  | Amount  | Running Total  | Notes/justifications  |
|---|---|---|---|
| Technical writer audit, update, test, and publish reference documentation of GeomScale project  |  10000.00 | 10000.00  |   |
| Volunteer stipends  |  500 |  11500.00 | 3 volunteer stipends x 500 each  |
|  TOTAL |   | 11500.00  |   |


## Additional information

### Previous experience with technical writers or documentation:

Members of GeomScale have experience in developing and reviewing documentation.
For example in developing and mentoring documentation development
for [`R` CRAN package volesti](https://CRAN.R-project.org/package=volesti).
The review process used was similar to a coding review. Examples of documentation
review process in GeomScale are available from
[github](https://github.com/boostorg/geometry/pulls?q=is%3Apr+is%3Aclosed+label%3Adocumentation).
In addition to this we usually employ a last step of iterating the final draft
of documentation to our peers and users for feedback.

Our previous experience with documentation development gives us confidence to
apply best practices and well established review processes and tools to the
potential GSoD projects. For example, the GSoD project development will take
part in github by opening issues for discussion and pull requests
(with a documentation tab) to submit/review the technical writer's contributions.

### Previous participation in Season of Docs, Google Summer of Code or others:

All the members of GeomScale have previously participated in Google Summer of
Code as mentors or/and as students. Our members have mentored 7 GSoC coding
projects under `R`-project and Boost `C++` libraries organizations (2017-2019).
The main software package of GeomScale has been substantially enhanced through
3 GSoC projects under the mentoring of two of GeomScale’s members, while one
student of those projects (Apostolos Chalkis) became a GeomScale member and
GSoC mentor and admin. 

The last three years (2020-2022) GeomScale has been selected as a mentoring
organization for GSoC. In 2021 we have successfully mentored 5 projects
resulting in >10 pull requests all of which are merged into our repositories
development branch.

We strongly believe that this experience will play a crucial role for
successful GSoD projects. In particular, we have experience in communicating
with persons of diverged educational and cultural background and focused
to give the right tips and guidance for successful projects. Moreover,
we are capable of fixing detailed and realistic time schedules based on
the technical writer’s profile and potential.
