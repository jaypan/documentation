---
use: [local]
title: Local Development Articles
layout: article
landing: true
---
{% for article in data.local %}
<a href="{{ article.url }}">{{ article.title }}</a><br>
{% endfor %}
