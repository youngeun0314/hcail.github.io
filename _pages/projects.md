---
layout: page
title: projects
permalink: /projects/
description: We pursue research in the combinations of AI, Health, & HCI.
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
<table class="imgtable"><tr>
<!-- <td>
<img src="/assets/img/da.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;</td>
-->
<td align="left">
<b>Development of an AI-based Dietary Assessment System for Digital Therapeutics to Support Older Adults with Diabetes</b>
<p>Principle Investigator, National Research Foundation of Korea `한국연구재단 생애첫연구`
<br>
Mar. 2020 - Feb. 2023</p>
</td></tr></table>

<table class="imgtable">
<tr>
<!-- <td>
<img src="/assets/img/mr.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;
</td>
-->
<td align="left">
<b>
    Development of AI-based Technology for Improving Accessibility to Information for People with Visual Impairments
</b>
<p>
    Principle Investigator, Seoul Metropolitan Government `서울특별시 시정연구`
<br>
    Apr. 2022 - Dec. 2022
</p>
</td></tr></table>

---

### Completed Sponsored Research Projects
<table class="imgtable">
<tr>
<!-- <td>
<img src="/assets/img/mr.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;
</td>
-->
<td align="left">
<b>
    Development of Technology for Quantifying Web Accessibility Based on Big Data to Improve Accessibility to Information for People with Visual Impairments
</b>
<p>
    Principle Investigator, Seoul Metropolitan Government `서울특별시 시정연구`
<br>
    Apr. 2021 - Dec. 2021
</p>
</td></tr></table>

<table class="imgtable"><tr>
<!-- <td>
<img src="/assets/img/mr.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;
</td>
-->
<td align="left">
<b>
    AI Application Technology with MR-IoT Convergence to Countermeasure Disasters
</b>
<p>
    Co-Investigator, Ajou University (via Ministry of Science and ICT)
<br>
    June 2018 - Dec. 2021
</p>
</td></tr></table>

<table class="imgtable"><tr>
<!-- <td>
<img src="/assets/img/da.jpeg" alt="alt text" width="125px" height="125px" />&nbsp;
</td>
-->
<td align="left">
<b>
    Development of a Smartphone Application for Dietary Assessment
  </b>
<p>Principle Investigator, Kyung Hee University
  <br>Sep. 2018 - Aug. 2019
  </p>
</td></tr></table>
