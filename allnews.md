---
title: All News
layout: page
show_sidebar: false
---

{% for article in site.data.news %}
  [**{{ article.date }}**] {{ article.headline }}<br />
  {% if article.descript %}
  - {{ article.descript }}<br />
  {% else %}
  {% endif %}
{% endfor %}

