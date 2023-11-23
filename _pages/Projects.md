---
title: "Projects and collaborations"
layout: single
permalink: /Projects/
classes: wide
author_profile: true
---

## European Projects

{% assign projs = site.projects | sort: "project_year" | reverse %}
{% for proj in projs %}
{% if proj.European_project %}

<div class="projitem">
  <div class="projteaser">
    <a href="{{proj.url}}">
      {% if proj.header.teaser %}
        <img src="{{ proj.header.teaser }}" alt="{{proj.slug}} project teaser"/>
      {% else %}
        <img src="/_images/_proj_images/{{ proj.slug }}_small.jpg" alt="{{proj.slug}} project teaser"/>
      {% endif %}
    </a>
  </div>
  <div class="column">
    <a href="{{proj.url}}" class="nounderline">
      <div class="projtitle">
        {{ proj.title }}
      </div>
    </a>
    <div class="projbrief">
      {{ proj.brief }}
    </div>
    <div class="projlinks">
      <a href="{{proj.url}}"><i class="fas fa-arrow-right"></i> Project Page</a>&nbsp;&nbsp;
      <a href="{{proj.Project_website}}"><i class="fa fa-globe"></i> Project Website</a>
    </div>
  </div>
</div>
  
{% endif %}
{% endfor %}

## Italian National Projects

{% assign projs = site.projects | sort: "project_year" | %}
{% for proj in projs %}
{% if proj.Italian_project %}
<div class="projitem">
  <div class="projteaser">
    <a href="{{proj.url}}">
      {% if proj.header.teaser %}
        <img src="{{ proj.header.teaser }}" alt="{{proj.slug}} project teaser"/>
      {% else %}
        <img src="/_images/_proj_images/{{ proj.slug }}_small.jpg" alt="{{proj.slug}} project teaser"/>
      {% endif %}
    </a>
  </div>
  <div class="column">
    <a href="{{proj.url}}" class="nounderline">
      <div class="projtitle">
        {{ proj.title }}
      </div>
    </a>
    <div class="projbrief">
      {{ proj.brief }}
    </div>
    <div class="projlinks">
      <a href="{{proj.url}}"><i class="fas fa-arrow-right"></i> Project Page</a>&nbsp;&nbsp;
      <a href="{{proj.Project_website}}"><i class="fa fa-globe"></i> Project Website</a>
    </div>
  </div>
</div>
{% endif %}
{% endfor %}

## Industry Projects and Collaborations

Our research group has a long history of collaboration with industry. We have been involved in several projects with automotive producers or related service companies. The following are examples:
 - STELLANTIS (Italy-France)
 - CRF (Centro Ricerche Fiat S.C.p.A., Italy)
 - DANA Incorporated (Italy)
 - RELab (Italy)
 - AnteMotion (Italy)
  
We are currently involved in several projects with the motorsport industry on two and four wheels. In addition, we collaborate with tire manufacturers.
