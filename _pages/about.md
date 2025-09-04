---
permalink: /
title: "Minghao Hu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a third-year Ph.D. student at the Department of Computer Science, [George Mason University](https://www.gmu.edu/). My research focuses on NLP applications in software engineering. I am advised by [Prof. Lannan Luo](https://lannan.github.io/). Previously, I obtained my Master's degree and Bachelor's degree both from [Southeast University](https://www.seu.edu.cn/). 



## Publications

{% assign publications = site.publications | sort: 'date' | reverse %}
{% for pub in publications %}
{{ pub.content }}

{% endfor %}

## Teaching Experience

Fall 2025, ISA 562, Information Security System and Theory, Teaching Assistant



