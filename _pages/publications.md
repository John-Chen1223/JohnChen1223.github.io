---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  
  You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=z1irpJEAAAAJ).

  Since Sept 2022 when I became a postgraduate student at HITSZ (postgraduate recommendation way), I have been involved in 3 China national key programs related to space communication networks.
  
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

