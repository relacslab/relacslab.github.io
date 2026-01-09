---
title: Members
layout: page
show_sidebar: false
---

# Professor
**Hyokeun Lee**
<!--
(<a href="https://www.linkedin.com/in/hyokeunlee">LinkedIn</a>&nbsp;&nbsp;/&nbsp;&nbsp;<a href="https://github.com/relacslab/relacslab.github.io/tree/main/_document/My_CV_hklee.pdf">CV</a>) <br />
-->
(<a href="https://www.linkedin.com/in/hyokeunlee" target="_blank">LinkedIn</a>&nbsp;&nbsp;/&nbsp;&nbsp;<a href="https://github.com/relacslab/my_documents/blob/main/My_CV_hklee.pdf" target="_blank">CV</a>), <em> Assistant Professor </em> <br /> 
**Affiliation:** Department of Electrical and Computer Engineering, Ajou University <br />
**Email:** hyokeun.lee[at]dgist.ac.kr <br />
**Biography:** Hyokeun Lee is an Assistant Professor in the Department of Electrical Engineering and Computer Science at DGIST, South Korea. Before joining DGIST, he was a faculty member of Ajou University, South Korea. Hyokeun Lee worked as a Postdoctoral Researcher at North Carolina State University (2023-2024) and the ISRC of Seoul National University (2021-2023). He earned the B.S. and Ph.D. degrees from Seoul National University, in 2016 and 2021, respectively. His current research interests include resource disaggregation, memory security, emerging memory technologies, and architecture simulation modeling. His research outcomes have been featured at various prestigious computer architecture conferences, including MICRO, HPCA, and PACT. 

# Dissertation
Mitigating Disturbance Errors and Enhancing RMW Performance for PCM <br />
Ph.D. Dissertation, Seoul National University, Aug. 2021 <br />
Committee: Deog-Kyoon Jeong (Chair), Hyuk-Jae Lee (Advisor), Soojung Ryu, Jangwoo Kim, Jaewoong Sim

# Services
{% for servli in site.data.servlist_prof %}
  <b>{{ servli.title }}</b> <br /> 
  <em>{{ servli.role }}</em>
{% endfor %}

# Talks
{% for servli in site.data.servlist_talk %}
  <b>{{ servli.title }}</b> <br />
  <em>{{ servli.venue }}</em>, {{ servli.year }}
{% endfor %}

