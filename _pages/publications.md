---
layout: posts
title: "Publications"
permalink: /publications/
author_profile: true
#excerpt: "This post should display a **header with a solid background color**, if the theme supports it."
header:
  overlay_color: "#333"
---

{% for post in site.publications reversed %}
  {% include archive-single-publications.html %}
{% endfor %}