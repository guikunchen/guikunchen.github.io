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
  I am currently a D.Eng student at Zhejiang University. My research interests include artificial intelligence, with a focus on scene understanding, 3D reconstruction, and (multimodal) large language models.


<br />

Education
=======
* D.Eng in Artificial Intelligence, Zhejiang University, China, 2023–Present. Supervised by Prof. Wenguan Wang.
* MS in Artificial Intelligence, Zhejiang University, China, 2021–2022. Supervised by Prof. Jun Xiao.


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