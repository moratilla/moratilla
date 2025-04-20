---
layout: page
title: Repositories
description:
  What I've Been Building - A Highlight Reel of My Repositories.
---

{% for item in site.repositories %}

<h2><a href="{{ item.url | prepend: site.baseurl }}">{{ item.title }}</a></h2>

<p class="post-excerpt">{{ item.description | truncate: 160 }}</p>

{% endfor %}  