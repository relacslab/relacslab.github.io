---
title: Service
layout: page
show_sidebar: false
---

# Lectures & Invited Talks
{% for servli in site.data.servlist_talk %}
  {{ servli.label }} {{ servli.title }} <br />
  <em>{{ servli.venue }}</em>, {{ servli.year }}
{% endfor %}


# Professional Services
{% for servli in site.data.servlist_prof %}
  {{ servli.role }}, <em>{{ servli.title }}</em>, {{ servli.year }}
{% endfor %}
