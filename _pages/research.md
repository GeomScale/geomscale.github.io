---
permalink: /research/
title: Research
redirect_from:
  - /publications/
  - /talks/
---

## Scientific background, problems and applications

![Boltzmann distribution]({{ site.url }}{{ site.baseurl }}/assets/images/boltzmann.png){: .align-left} The main computational problem we study is sampling from high-dimensional distributions. Sampling is a fundamental operation that plays a crucial role across sciences including modern machine learning and data science. To address this problem we develop and implement Markov Chain Monte Carlo sampling methods that scale up to thousands of dimensions. We also work on the development of practical algorithms based on sampling for a set of fundamental computational problems such as convex optimization, integration, volume computation and Bayesian inference.

Regarding applications, GeomScale provides efficient geometric modeling and algorithms that are useful in computational finance, in particular in financial crisis and anomaly detection, portfolio scoring and portfolio optimization. Moreover, GeomScale hosts a software framework for analysis of metabolic networks that given a metabolic model generates high-dimensional random sampling of metabolic fluxes that in turn provide an unbiased description of the capabilities of the metabolic network.

## How to cite

If you use volesti, please cite:

{% assign c = site.data.publications | where: "cite", true | first %}
{% include gs/publication.html p=c %}

## Publications

{% include gs/publications.html %}

## Talks

{% include gs/talks.html %}
