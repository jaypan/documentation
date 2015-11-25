---
use: [wordpress]
title: WordPress Articles
layout: article
landing: true
---
{% for article in data.wordpress %}
<a href="{{ article.url }}">{{ article.title }}</a><br>
{% endfor %}
