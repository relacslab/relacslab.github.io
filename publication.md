---
title: Publication
layout: page
show_sidebar: false
---

^: equally contributed first author

\*: (co-)corresponding author

# Conference Papers
{% for publi in site.data.publist_conference %}
  {{ publi.label }} {{ publi.authors }} <br />
  <a href="{{ publi.tlink }}">{{ publi.title }}</a> <br />
  {% if publi.code %}
    <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }} <br />
    <a href="{{ publi.clink }}">{{ publi.code }}</a> <a href="{{ publi.plink }}">{{ publi.slide }}</a> <br />
  {% else %}
    <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
  {% endif $}
{% endfor %}

# Journal Papers
{% for publi in site.data.publist_journal %}
  {{ publi.label }} {{ publi.authors }} <br />
  <a href="{{ publi.tlink }}">{{ publi.title }}</a> <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
{% endfor %}

# Patents
{% for publi in site.data.publist_patent %}
  {{ publi.label }} {{ publi.inventors }} <br />
  {{ publi.title }} <br />
  <em>{{ publi.ptype }} {{ publi.pnum }}</em>, {{ publi.year }} {{ publi.status }}
{% endfor %}


# Dissertation
Mitigating Disturbance Errors and Enhancing RMW Performance for PCM <br />
Ph.D. Dissertation, Seoul National University, Aug. 2021 <br />
Committee: Deog-Kyoon Jeong (Chair), Hyuk-Jae Lee (Advisor), Soojung Ryu, Jangwoo Kim, Jaewoong Sim
