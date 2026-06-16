---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Basic Information

**Shuo Zhang**

- Affiliation: Renmin University of China
- Location: Beijing, China
- Email: [zhangshuo1422@ruc.edu.cn](mailto:zhangshuo1422@ruc.edu.cn)
- Google Scholar: [profile](https://scholar.google.com/citations?user=AL3YxaIAAAAJ&hl=en)

## Education

- Renmin University of China, 2024.09 - Present
- Renmin University of China, 2020.09 - 2024.06

## Research Interests

- Algorithmic game theory
- Mechanism design and auction theory
- Information design and signaling
- Approximation algorithms
- Computational geometry

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% else %}
  <li>Publications will be listed here.</li>
{% endfor %}
</ul>

## Working Projects

- **Optimal Calibrated Signaling in Digital Auctions**. Working paper.

## Note

For theory papers with alphabetical author ordering, `(α-β)` marks alphabetical author order.
