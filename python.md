---
layout: page
permalink: /python/
title: Python
---

{% for post in site.categories.python %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}