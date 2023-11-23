---
title: "Projects and collaborations"
layout: single
permalink: /Projects/
classes: wide
author_profile: true
---

## European Projects

### Dream4Cars 
Dream4Cars is a European project funded by the European Commission under the Horizon 2020 program. [Project Page](/Projects/Dream4Cars/) | [Project Website](https://www.dreams4cars.eu/en/)

### SafeStrip

### SUNRISE

## Italian Projects

### VeDi2025

## Industry Projects and Collaborations
<!-- 
{% assign projs = site.projects_folder | %}
{% for pub in projs %}
{{ pub.title }} </br>

<div class="pubitem">
  <div class="pubteaser">
    <a href="{{pub.url}}">
      {% if pub.video %}
      <img src="https://img.youtube.com/vi/{{pub.video}}/0.jpg" alt="{{pub.slug}} project teaser"/>
      {% else %}
        {% if pub.logo %}
         <img src="/_images/_third_parties_logos/{{ pub.logo }}" alt="{{pub.logo}} logo"/>
        {% elsif pub.header.teaser %}
          <img src="{{ pub.header.teaser }}" alt="{{pub.slug}} project teaser"/>
        {% else %}
          <img src="/_images/_pub_images/{{ pub.slug }}_small.jpg" alt="{{pub.slug}} project teaser"/>
        {% endif %}
      {% endif %}
    </a>
  </div>
  <div class="column">
    <a href="{{pub.url}}" class="nounderline">
      <div class="pubtitle">
        {{ pub.title }}
      </div>
    </a>
    <div class="publinks">
      {% if pub.pdf %}
      <a href="/download/{{ pub.slug}}.pdf"><i class="far fa-file-pdf"></i> PDF</a>&nbsp;&nbsp;
      {% endif %}
      {% if pub.doi %}
      <a href="{{ pub.doi }}"><i class="fas fa-external-link-alt"></i> DOI</a>&nbsp;&nbsp;
      {% endif %}
      <a href="{{pub.url}}"><i class="fas fa-arrow-right"></i> Project Page</a>
    </div>
  </div>
</div>
{% endfor %} -->
