---
layout: page
permalink: /prog-academy/
title: Prog.academy
---

## FE-React
{% for post in site.categories.prog-module-3 %}
<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

## FE-Pro
{% for post in site.categories.prog-module-2 %}
<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

## FE-Start
{% for post in site.categories.prog-module-1 %}
<li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
