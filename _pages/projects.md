---
layout: page
title: projects
permalink: /projects/
description:
nav: true
display_categories: [Artificial Intelligence, Digital Health, Social Computing, Accessibility & Aging]
horizontal: false
---

### Ongoing Research Projects
<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

---

### Sponsored Research Projects
<table class="imgtable"><tr><td>
<img src="/assets/img/da.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;</td>
<td align="left"><h5>Development of an AI-based Dietary Assessment System for Digital Therapeutics to Support Older Adults with Diabetes</h5>
<h6>Principle Investigator, National Research Foundation of Korea (via Ministry of Science and ICT)</h6>
<h6>Mar. 2020 - Feb. 2023</h6>
</td></tr></table>

---

### Completed Sponsored Research Projects
<table class="imgtable"><tr><td>
<img src="/assets/img/mr.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;</td>
<td align="left">
  <h5>
    AI Application Technology with MR-IoT Convergence to Countermeasure Disasters
  </h5>
  <h6>
    Co-Investigator, Ajou University (via Ministry of Science and ICT)
  </h6>
  <h6>
    June 2018 - Dec. 2021
  </h6>
</td></tr></table>

<table class="imgtable"><tr><td>
<img src="/assets/img/da.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;</td>
<td align="left">
    <h5>
    Development of a Smartphone Application for Dietary Assessment
    </h5>
  <h6>Principle Investigator, Kyung Hee University</h6>
  <h6>Sep. 2018 - Aug. 2019</h6>
</td></tr></table>
