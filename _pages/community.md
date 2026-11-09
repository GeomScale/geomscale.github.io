---
permalink: /community/
title: Community
redirect_from:
  - /people/
---

## People

{% include gs/people.html %}

## Google Summer of Code

{% include gs/gsoc.html %}

## Google Season of Docs

{% for d in site.data.gsod %}- {{ d.year }}: [{{ d.title }}]({{ d.result }}). {{ d.writer }} (technical writer). [Proposal]({{ d.proposal }}) · [case study]({{ d.case_study }})
{% endfor %}

## Contribute

- [How to contribute to volesti](https://github.com/GeomScale/volesti/blob/develop/CONTRIBUTING.md)
- [Good first issues](https://github.com/GeomScale/volesti/issues?q=is%3Aopen+label%3A%22good+first+issue%22)
- [GSoC 2026 project ideas](https://github.com/GeomScale/gsoc26/wiki)
