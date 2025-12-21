---
title: Principal Investigator
layout: page
show_sidebar: false
---

**Hyokeun Lee**
<!--
(<a href="https://www.linkedin.com/in/hyokeunlee">LinkedIn</a>&nbsp;&nbsp;/&nbsp;&nbsp;<a href="https://github.com/relacslab/relacslab.github.io/tree/main/_document/My_CV_hklee.pdf">CV</a>) <br />
-->
(<a href="https://www.linkedin.com/in/hyokeunlee" target="_blank">LinkedIn</a>&nbsp;&nbsp;/&nbsp;&nbsp;<a href="https://github.com/relacslab/my_documents/blob/main/My_CV_hklee.pdf" target="_blank">CV</a>), <em> Assistant Professor </em> <br /> 
**Affiliation:** Department of Electrical and Computer Engineering, Ajou University <br />
**Email:** hyokeunlee[at]ajou.ac.kr <br />
**Biography:** Hyokeun Lee is an Assistant Professor in the Department of Electrical and Computer Engineering (ECE) at Ajou University, Suwon, South Korea. He was a postdoctoral researcher at North Carolina State University (2023-2024, mentor: Prof. Amro Awad) and the ISRC of Seoul National University (2021-2023). He earned the B.S. and Ph.D. (advisor: Prof. Hyuk-Jae Lee) degrees from the Department of ECE at Seoul National University, in 2016 and 2021, respectively. His current research interests include resource disaggregation, memory security, emerging memory technologies, and architecture simulation modeling. His research outcomes have been featured at various prestigious computer architecture conferences (e.g., MICRO, HPCA, PACT) and journals (e.g., IEEE TC, TVLSI, CAL).

# Professional Services
{% for servli in site.data.servlist_prof %}
  {{ servli.title }} <br /> 
  **Roles:** <em>{{ servli.role }}</em>
{% endfor %}

# Talks
{% for servli in site.data.servlist_talk %}
  {{ servli.title }} <br />
  <em>{{ servli.venue }}</em>, {{ servli.year }}
{% endfor %}

