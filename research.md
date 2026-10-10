---
title: Research Themes
layout: page
show_sidebar: false
---


# Main Research Theme: Resource Disaggregation

Modern computer applications, like LLM, demand larger memory resources but also highly integrated functionalities. Accordingly, <em>resource disaggregation</em> is key to achieving high performance and high scalability in future large-scale computing systems---it aggregates resources, such as memory or accelerators, into modular subsystems just like Lego blocks. Recently, these technologies have been actively applied to various levels of computing systems, ranging from data centers (e.g., disaggregated memory) to SoCs (e.g., chiplet). My research aims at fundamental issues in these large-scale computing systems to achieve low power and high reliability while ensuring high performance and scalability. To be more specific, my research can be further divided into the following **two paths**:


## Memory Disaggregation
<div class="columns">
<div class="column is-4">
{% include image-modal.html ratio="is-16by9" link="![mem-disag](https://github.com/relacslab/relacslab.github.io/blob/main/img/mem-disag.jpg)" alt="Example image" large_link="https://via.placeholder.com/1200x675" %}
</div>
<div class="column is-8">
Memory disaggregation is a scalable main memory expansion solution that modularly aggregates several memory devices in a separate node at the system level. Also, it can be achieved by leveraging I/O interconnects in addition to traditional DIMM interfaces at the node level. However, such a large-scale memory system is usually shared by a large number of processing units, thereby potentially incurring security, reliability, and resource efficiency issues. Thus, we develop scalable disaggregated memory architectures through advanced (1) protocols that support hardware-based cache coherence (e.g., CXL), (2) features (e.g., security, compression), and (3) memory technologies (e.g., NVM). 
</div>
</div>

Selected Recent Publications: [HPCA '24], [PACT '23], [CAL '25], [ICS '26], [TC '20, '23], [ISPASS '22], [ISLPED '24]


## Accelerator Disaggregation
<div class="columns">
<div class="column is-4">
{% include image-modal.html ratio="is-16by9" link="https://via.placeholder.com/400x225" alt="Example image" large_link="https://via.placeholder.com/1200x675" %}
</div>
<div class="column is-8">
Accelerator disaggregation forms so-called accelerator-rich systems by aggregating the computation power of various acceleration functional units (AFUs). For example, modern SoCs have included more third-party intellectual properties (IPs) over the years. However, the introduction of third-party IPs conversely enlarges the security attack surface. Thus, we address security-related issues, such as MMU or memory, in the context of larger-scale SoCs (e.g., chiplet or accelerator-rich SoCs).
</div>
</div>

Selected Recent Publications: [MICRO '23], [HPCA '24], [TC '26]

## Research collaborators
<div class="columns">
<div class="column is-12">
{% include image-modal.html ratio="is-16by9" link="https://via.placeholder.com/400x225" alt="Example image" large_link="https://via.placeholder.com/1200x675" %}
</div>
</div>

<a href="https://github.com/relacslab/my_documents/blob/main/lab_poster.pdf">Glance at a poster</a> <br />


