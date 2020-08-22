---
<!-- layout: archive -->
title: "Publications [(Google Scholar)](https://scholar.google.com/citations?hl=en&user=W0iPYdUAAAAJ&view_op=list_works&sortby=pubdate)"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
 You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=W0iPYdUAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
