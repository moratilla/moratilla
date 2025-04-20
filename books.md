---
layout: page
title: Books
description:
  I've had the pleasure of lending my expertise as a technical reviewer for these fantastic Packt Publishing titles.
---

I've had the pleasure of contributing my technical expertise as a reviewer for the following Packt Publishing titles. If you're seeking a meticulous and knowledgeable technical reviewer for your upcoming project, I'd be delighted to discuss potential collaborations, subject to my availability.

{% for item in site.books %}

<h2><a href="{{ item.url | prepend: site.baseurl }}">{{ item.title }}</a></h2>

<p class="post-excerpt">{{ item.description | truncate: 160 }}</p>

{% endfor %}  