---
use: [organizations]
title: Organization Articles
layout: article
landing: true
---
{% for article in data.organizations %}
<a href="{{ article.url }}">{{ article.title }}</a><br>
{% endfor %}
