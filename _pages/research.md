---
permalink: /research/
title: Research
redirect_from:
  - /publications/
  - /talks/
---

## How to cite

If you use volesti, please cite:

{% assign c = site.data.publications | where: "cite", true | first %}
{% include gs/publication.html p=c %}

## Publications

{% include gs/publications.html %}

## Talks

{% include gs/talks.html %}
