---
layout: page
title: members
permalink: /members/
description: Members.
nav: true
display_categories: [work, fun]
horizontal: false
---

<div class="projects">
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="card hoverable mt-2">
    <div class="card-body">
      <h5 class="card-title text-lowercase">
        <a href="{{ project.html_url }}" target="_blank">{{ project.name }}</a>
      </h5>
       <h6 class="card-subtitle mb-2 text-muted">{{project.language}} &bull; <i class="fa fa-star"></i> {{project.stargazers_count}} </h6>
      <p class="card-text">{{ project.description }}</p>
    </div>
  </div>
  {% endfor %}
</div>

<!-- pages/members.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.members | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2" style="text-transform: none;">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid" style="text-transform: none;">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.members | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2" style="text-transform: none;">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid" style="text-transform: none;">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
