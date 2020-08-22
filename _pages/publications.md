---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
 <u><a href="{{https://scholar.google.com/citations?hl=en&user=W0iPYdUAAAAJ&view_op=list_works&sortby=pubdate}}">Google Scholar</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

title: "Occlusion-Adaptive Deep Network for Robust Facial Expression Recognition"
venue: "INTERNATIONAL JOINT CONFERENCE ON
BIOMETRICS (IJCB 2020)"
date: 2020-9
citation: 'Ding Hui, <b>Peng Zhou</b> and Rama Chellappa. <i>INTERNATIONAL JOINT CONFERENCE ON
BIOMETRICS</i>. <b>IJCB 2020</b>.'
---

[PDF](https://arxiv.org/pdf/2005.06040.pdf)


