---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
About Me
=======
  I am currently a D.Eng student at Zhejiang University. My research interests include artificial intelligence, with a focus on scene understanding, GenAI, and (multimodal) large language models.


<br />

Education
=======
* D.Eng in Artificial Intelligence, Zhejiang University, China, 2023–Present. Supervised by Prof. <a href="https://sites.google.com/view/wenguanwang/home" target="_blank">Wenguan Wang</a>.
* MS in Artificial Intelligence, Zhejiang University, China, 2021–2022. Supervised by Prof. <a href="https://scholar.google.com/citations?user=fqOwFhQAAAAJ" target="_blank">Jun Xiao</a>.


<br />

Selected Publications
=======
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<br />

Selected Awards
=======
{% include base_path %}

{% for post in site.awards reversed %}
  {% include archive-single.html %}
{% endfor %}