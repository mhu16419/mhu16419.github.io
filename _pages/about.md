---
permalink: /
title: "Minghao Hu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at the Department of Computer Science, George Mason University. I am advised by [Prof. Lannan Luo](https://lannan.github.io/). Previously, I obtained my Master's degree and Bachelor's degree both from Southeast University. 

My research focuses on machine learning applications in security and privacy, particularly in malware detection and binary code analysis. I work on developing novel deep learning architectures that can effectively detect and analyze malicious software across different instruction set architectures.

## Publications

{% raw %}{% assign publications = site.publications | sort: 'date' | reverse %}{% endraw %}
{% raw %}{% for pub in publications %}{% endraw %}
**{{ pub.title }}**  
{{ pub.content | strip_html | strip_newlines | truncate: 200 }}  
[>>PDF]({{ pub.paperurl }})

{% raw %}{% endfor %}{% endraw %}



