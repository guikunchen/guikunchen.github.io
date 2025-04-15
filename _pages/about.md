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
  I am currently a D.Eng student at Zhejiang University.


<br />

Education
=======
* D.Eng, Zhejiang University, China, 2023–Present.
* MS, Zhejiang University, China, 2021–2022.


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