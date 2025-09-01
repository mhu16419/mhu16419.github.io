---
permalink: /
title: "Minghao Hu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at the Department of Computer Science, George Mason University. My research focuses on NLP applications in software engineering. I am advised by [Prof. Lannan Luo](https://lannan.github.io/). Previously, I obtained my Master's degree and Bachelor's degree both from Southeast University. 



## Publications

{% assign publications = site.publications | sort: 'date' | reverse %}
{% for pub in publications %}
**{{ pub.title }}**  

{{ pub.content | strip_html | strip_newlines | truncate: 200 }}  

[>>PDF]({{ pub.paperurl }})

{% endfor %}



