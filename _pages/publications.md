---
layout: posts
title: "Publications"
permalink: /publications/
author_profile: true
#excerpt: "This post should display a **header with a solid background color**, if the theme supports it."
header:
  overlay_color: #0a0a0a
  overlay_filter: rgba(240, 240, 240, 0.4)
  overlay_image: /images/portfolio/windings/bp5_stator.jpg
---

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}