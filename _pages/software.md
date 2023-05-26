---
permalink: /software/
---

<img src="/assets/images/volesti_logo.jpg" alt="photo" class="float-left" />

The main development is currently performed in
[volesti](https://github.com/GeomScale/volume_approximation), a generic open source
C++ library, with R and Python interfaces. *volesti* implements various algorithms
for high-dimensional sampling and volume approximation as well as functions
for copula estimation in financial modelling and metabolic network analysis.

<table width="100%" style="margin: auto;">
 <tr>
   <th><a href="https://github.com/GeomScale/volesti"><img src="/assets/images/github.png"
        width="60" height="60" alt="photo" class="float-left" /></a></th>
   <th><a href="https://cran.r-project.org/package=volesti"><img src="/assets/images/Rlogo.png"
        width="60" height="60" alt="photo" class="float-left" /></a></th>
   <th><a href="https://github.com/GeomScale/volume_approximation/blob/develop/README.md"><img src="/assets/images/doc.png"
        width="50" height="50" alt="photo" class="float-left" /></a></th>
   <th><a href="https://vissarion.github.io/tutorials/volesti_tutorial_pydata.html"><img src="/assets/images/tutorial.png"
        width="60" height="60" alt="photo" class="float-left" /></a></th>
   <th><a href="https://github.com/GeomScale/volume_approximation/blob/develop/CONTRIBUTING.md"><img src="/assets/images/contrib.jpeg"
        width="60" height="60" alt="photo" class="float-left" /></a></th>
 </tr>
 <tr>
   <td>Source code</td>
   <td>R package</td>
   <td>Documentation</td>
   <td>Tutorials</td>
   <td>Contributing</td>
 </tr>
</table>
  <span style="color:white">white text</span>  



<img src="/assets/images/dingo.jpg" width="200" height="200" alt="photo" class="float-left" />

[dingo](https://github.com/GeomScale/dingo) is a python package that analyzes metabolic networks. It relies on high dimensional sampling with Markov Chain Monte Carlo (MCMC) methods and fast optimization methods to analyze the possible states of a metabolic network. To perform MCMC sampling, *dingo* relies on the C++ library [volesti](https://github.com/GeomScale/volume_approximation), which provides several algorithms for sampling convex polytopes. *dingo* also performs two standard methods to analyze the flux space of a metabolic network, namely Flux Balance Analysis and Flux Variability Analysis.  

<table width="100%" style="margin: auto;">
 <tr>
   <th><a href="https://github.com/GeomScale/dingo"><img src="/assets/images/github.png"
        width="60" height="60" alt="photo" class="float-left" /></a></th>
   <th><a href="https://github.com/GeomScale/dingo/blob/develop/README.md"><img src="/assets/images/doc.png"
        width="50" height="50" alt="photo" class="float-left" /></a></th>
   <th><a href="https://colab.research.google.com/drive/1AdXCo6tMBV4lPDYWWOXhzcM0wg30OOIx?usp=sharing"><img src="/assets/images/tutorial.png"
        width="60" height="60" alt="photo" class="float-left" /></a></th>
 </tr>
 <tr>
   <td>Source code</td>
   <td>Documentation</td>
   <td>Tutorials</td>
 </tr>
</table>


## Who is using our software ?

- G. Spallitta, G. Masina, P. Morettin, A. Passerini, R. Sebastiani, Enhancing SMT-based Weighted Model Integration by Structure Awareness, Preprint, 2023. [WWW](https://arxiv.org/abs/2302.06188)  

-  M. Vejdemo-Johansson, S. Mukherjee, Multiple hypothesis testing with persistent homology, American Institute of Mathematical Sciences, Volume 4, 2022. [WWW](https://www.aimsciences.org/article/doi/10.3934/fods.2022018)  

- A. Venzke, D.K. Molzahn, S. Chatzivasileiadis -
*Efficient creation of datasets for data-driven power system applications*,
Electric Power Systems Research, Volume 190, 2021.
[WWW](https://doi.org/10.1016/j.epsr.2020.106614)

- P.Z.D. Martires, Samuel Kolb - *Monte Carlo Anti-Differentiation for
Approximate Weighted Model Integration*, 2020.
[WWW](https://arxiv.org/abs/2001.04566)

- C. Maria, O. Rouillé - *Computation of Large Asymptotics of 3-Manifold Quantum
Invariants*, 2020. [WWW](https://arxiv.org/abs/2010.14316)

## <img src="/assets/images/GSoC.png" width="60" height="60" alt="photo" class="float-left" /> Google Summer of Code

*GeomScale* is participating in <A href="https://summerofcode.withgoogle.com/programs/2023/organizations/geomscale">Google Summer of Code 2023</A> as a mentoring organization!  

*GeomScale* was accepted and participated in
<A href="https://summerofcode.withgoogle.com/archive/2020/organizations/">Google Summer of Code 2020</A>, <A href="https://summerofcode.withgoogle.com/archive/2021/organizations/5291444977270784">Google Summer of Code 2021</A> and <A href="https://summerofcode.withgoogle.com/programs/2022/organizations/geomscale">Google Summer of Code 2022</A> as a mentoring organization. The following projects was successfully completed:

- [Memory allocation in facet redundancy removal in dingo](https://summerofcode.withgoogle.com/programs/2022/projects/968ibP0I) (GSoC 2022).
- [Sampling correlation matrices](https://summerofcode.withgoogle.com/programs/2022/projects/biRI2YLT) (GSoC 2022).
- [Randomized SDP solver with Riemannian Hamiltonian Monte Carlo](https://summerofcode.withgoogle.com/programs/2022/projects/li2dNGB6) (GSoC 2022).
- [Support for new sampling methods and new model formats in dingo](https://summerofcode.withgoogle.com/programs/2022/projects/UKcKOkcC) (GSoC 2022).
- [Counting linear extensions with volume computation](https://summerofcode.withgoogle.com/programs/2022/projects/rpWAufXk) (GSoC 2022).
- [Automatic differentiation support in volesti](https://summerofcode.withgoogle.com/programs/2022/projects/TD3u7S00) (GSoC 2022).

- [From DNA sequences to metabolic interactions: building a pipeline to extract key metabolic processes](https://summerofcode.withgoogle.com/organizations/5553085268623360/#4835597543276544) (GSoC 2021).
- [Monte Carlo Integration](https://summerofcode.withgoogle.com/projects/#5929577068625920) (GSoC 2021).
- [Counting linear extensions](https://summerofcode.withgoogle.com/projects/#6649856422051840) (GSoC 2021).
- [High dimensional geometric computations with least matrix inequalities](https://summerofcode.withgoogle.com/projects/#5853827133079552) (GSoC 2021).
- [Parallel Geometric Random Walks with Sparse Numerical Optimizations](https://summerofcode.withgoogle.com/projects/#6606430762696704) (GSoC 2021).

- <A href="https://alexmanochis.github.io/GSoC20/">A comparative study of uniform high dimensional samplers</A> (GSoC 2020).
- <A href="https://papachristoumarios.github.io/2020/07/21/Sampling-from-high-dimensional-truncated-log-
  concave-densities-with-volesti/">
  Sampling from High-Dimensional log-concave densities</A> (GSoC 2020).

- <A href="https://github.com/GeomScale/volume_approximation/pull/93">Optimization and Sum of Squares</A> (GSoC 2020).  

Members of GeomScale has successfully participated in GSoC in the past with the
<A href="https://www.r-project.org/">R-project for statistical computing</A>.

- <A href="https://tolischal.github.io/GSoC2018">Efficient R tools for geometrical statistics</A>, 2018.
- <A href="https://panagiotisrep.github.io/gsoc2019/gsoc2019">Sampling Methods for Convex Optimization</A>, 2019.
- <A href="https://tolischal.github.io/GSoC2018">State-of-the-art geometric random walks in R</A>, 2019.

