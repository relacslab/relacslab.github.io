---
title: Publication
layout: page
show_sidebar: false
---

^: equally contributed first author

\*: corresponding author(s)

# Conference Papers
{% for publi in site.data.publist_conference %}
  {{ publi.label }} {{ publi.authors }} <br />
  <a href="{{ publi.tlink }}">{{ publi.title }}</a> <br />
  {%- if publi.code or publi.slide or publi.poster -%}
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }} <br />
  <a href="{{ publi.clink }}">{{ publi.code }}</a> <a href="{{ publi.clink }}">{{ publi.code2 }}</a> <a href="{{ publi.slink }}">{{ publi.slide }}</a> <a href="{{ publi.plink }}">{{ publi.poster }}</a> <br /> 
  {%- else -%}
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
  {%- endif %}
{% endfor %}

# Journal Papers
{% for publi in site.data.publist_journal %}
  {{ publi.label }} {{ publi.authors }} <br />
  <a href="{{ publi.tlink }}">{{ publi.title }}</a> <br />
  <em>{{ publi.issue }}</em>, {{ publi.year }} {{ publi.tier }}
{% endfor %}

# Submitted Papers 
[S4] Minseok Seo, Seongho Jeong, Jungi Hyun, Hyuk-Jae Lee, <u>Hyokeun Lee</u>\*, ASPLOS 2027<br />
[S3] Younghoon Ko, Hyemin Park, Hyuk-Jae Lee, <u>Hyokeun Lee</u>\*, ICS 2026<br />
[S2] John McFarland, Hyokeun Lee, Aydin Aysu, Amro Awad, "Secure Integrity for Third-Party IOMMUs," IEEE Transactions on Computers<br />
[S1] <u>Hyokeun Lee^</u>, Rahaf Abdullah^, Abbas Fairouz, Huiyang Zhou, Amro Awad, "An Efficient Unified Memory Security Model for CXL Memory-Expanded GPU Sytems," IEEE Transactions on Dependable and Secure Computing <br />

# Patents
{% for publi in site.data.publist_patent %}
  {{ publi.label }} {{ publi.inventors }} <br />
  {{ publi.title }} <br />
  <em>{{ publi.ptype }} {{ publi.pnum }}</em>, {{ publi.year }} {{ publi.status }}
{% endfor %}


