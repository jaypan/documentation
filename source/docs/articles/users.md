---
use: [users]
title: User Articles
layout: article
landing: true
---
{% for article in data.users %}
<a href="{{ article.url }}">{{ article.title }}</a><br>
{% endfor %}
