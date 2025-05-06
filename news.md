---
title: News
layout: page
show_sidebar: false
---

{% for article in site.data.news %}
  [{{ article.date }}] {{ article.headline }}<br />
{% endfor %}

