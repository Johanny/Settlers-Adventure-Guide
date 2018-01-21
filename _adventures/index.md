---
title: Adventures
permalink: /adventures/index.html
---

{% for item in site.adventures %}
<p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}