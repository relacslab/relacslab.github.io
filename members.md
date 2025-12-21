---
title: Group Members
layout: page
show_sidebar: false
---

# Ph.D./M.S. Students
{% for sli in site.data.stulist_extern %}
  [**{{ sli.name }}**]({{ sli.web }}), {{ sli.role }} <br />
  **Topic:** {{ sli.topic }} <br />
{% endfor %}

{% for sli in site.data.stulist_current %}
  [**{{ sli.name }}**]({{ sli.web }}), {{ sli.role }} <br />
  **Enrolled:** {{ sli.year }} <br />
  **Topic:** {{ sli.topic }} <br />
  **Email:** {{ sli.email }} <br />
{% endfor %}


# Undergraduate Students
{% for sli in site.data.ungradlist_current %}
  [**{{ sli.name }}**]({{ sli.web }}), {{ sli.role }} <br />
  **Enrolled:** {{ sli.year }} <br />
  **Email:** {{ sli.email }} <br />
{% endfor %}
