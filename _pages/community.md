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

## Support

GeomScale is a [NumFOCUS affiliated project](https://numfocus.org/sponsored-projects/affiliated-projects).
Funding information: [funding.json](/funding.json).

<p class="gs-logos">
<a href="https://nlnet.nl"><img src="https://nlnet.nl/logo/banner.svg" alt="NLnet foundation logo" height="50"></a>
<a href="https://nlnet.nl/commonsfund"><img src="https://nlnet.nl/image/logos/NGI0CommonsFund_tag.svg" alt="NGI Zero Commons Fund logo" height="50"></a>
</p>

[ovolesti](https://nlnet.nl/project/Ovolesti/) is funded through the [NGI0 Commons Fund](https://nlnet.nl/commonsfund),
a fund established by [NLnet](https://nlnet.nl) with financial support from the European Commission's
[Next Generation Internet](https://ngi.eu) programme, under the aegis of DG Communications Networks, Content and Technology
under grant agreement N<sup>o</sup> [101135429](https://cordis.europa.eu/project/id/101135429).
Additional funding is made available by the Swiss State Secretariat for Education, Research and Innovation (SERI).
