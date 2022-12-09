---
layout: page
permalink: /first-steps/
title: First steps
---

{% for post in site.categories.first-steps %}
<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}