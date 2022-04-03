---
layout: none
title: news
permalink: /
subtitle:

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

<div class="news">
  <h2>news</h2>
  {% if site.news != blank -%}
  <div class="table-responsive">
    <table class="table table-sm table-borderless">
    {%- assign news = site.news | reverse -%}
    {% for item in news limit: site.news_limit %}
      <tr>
        <!-- <th scope="row">{{ item.date | date: "%b %-d, %Y" }}</th> -->
        <th scope="row">{{ item.date | date: "%b %Y" }}</th>
        <td>
          {% if item.inline -%}
            {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
          {%- else -%}
            <a class="news-title" href="{{ item.url | relative_url }}">{{ item.title }}</a>
          {%- endif %}
        </td>
      </tr>
    {%- endfor %}
    </table>
  </div>
{%- else -%}
  <p>No news so far...</p>
{%- endif %}
</div>


<ul>
<li>
Hyunggu Jung was a research intern at Microsoft Research.
</li>
<li>
Invited Talk at College of Nursing, Seoul National University, Seoul, Korea.
</li>
<li>
Hyunggu Jung was a research intern at Microsoft Research.
</li>
</ul>
