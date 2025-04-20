---
layout: page
title: Projects
description:
  Beyond the 9-to-5 - Fueled by Passion. Currently Reviewing. 
---

This space showcases my journey of continuous learning through hands-on side projects. Here you'll find a selection of completed and ongoing initiatives that allow me to explore new technologies and ideas.

{% for item in site.projects %}

{% if item.category == "project" %}
<h2><a href="{{ item.url | prepend: site.baseurl }}">{{ item.title }}</a></h2>
<p class="post-excerpt">{{ item.description | truncate: 160 }}</p>
{% endif %}

{% endfor %}  