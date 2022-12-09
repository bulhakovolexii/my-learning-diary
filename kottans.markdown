---
layout: page
permalink: /kottans/
title: Kottans
---

## Stage 0
{% for post in site.categories.kottans-stage-0 %}
<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}