---
layout: default
title: Workers
permalink: /workers/
---

# 📜 Workers of The Forgotten Library

<ul>
{% for worker in site.workers %}
    <li><a href="{{ worker.url | relative_url }}">{{ worker.title }} - {{ worker.codename }}</a></li>
{% endfor %}
</ul>
