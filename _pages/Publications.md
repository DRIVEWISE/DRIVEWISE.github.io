---
layout: single
classes: wide
title: Publications
permalink: /Publications/
author_profile: true
toc: true
toc_label: "Table of Contents"
---

## Journals

{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}
{% if pub.pub_type == "journal" %}
<div class="pubitem">
  <div class="pubteaser">
    <a href="{{pub.url}}">
      {% if pub.video %}
      <img src="https://img.youtube.com/vi/{{pub.video}}/0.jpg" alt="{{pub.slug}} publication teaser"/>
      {% else %}
        {% if pub.logo %}
         <img src="/_images/_third_parties_logos/{{ pub.logo }}" alt="{{pub.logo}} logo"/>
        {% else %}
          <img src="/_images/_pub_images/{{ pub.slug }}_small.jpg" alt="{{pub.slug}} publication teaser"/>
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
    <div class="pubauthors">
      {% for author in pub.authors %}
        {% assign author_without_space = author | remove: ' ' %}
        <a href="../People/{{author_without_space}}">{{author}}</a> {% unless forloop.last %},{% endunless %}
      {% endfor %}
      <!-- {{ pub.authors }} -->
    </div>
    <div class="pubinfo">
      {{ pub.publication }}, {{ pub.year}}
    </div>
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
{% endif %}
{% endfor %}


## Conferences

{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}

{% if pub.pub_type == "conference" %}
<div class="pubitem">
  <div class="pubteaser">
    <a href="{{pub.url}}">
      {% if pub.video %}
      <img src="https://img.youtube.com/vi/{{pub.video}}/0.jpg" alt="{{pub.slug}} publication teaser"/>
      {% else %}
      <img src="/_images/_pub_images/{{ pub.slug }}_small.jpg" alt="{{pub.slug}} publication teaser"/>
      {% endif %}
    </a>
  </div>
  <div class="column">
    <a href="{{pub.url}}" class="nounderline">
      <div class="pubtitle">
        {{ pub.title }}
      </div>
    </a>
    <div class="pubauthors">
      {% for author in pub.authors %}
        {% assign author_without_space = author | remove: ' ' %}
        <a href="../People/{{author_without_space}}">{{author}}</a> {% unless forloop.last %},{% endunless %}
      {% endfor %}
      <!-- {{ pub.authors }} -->
    </div>
    <div class="pubinfo">
      {{ pub.publication }}, {{ pub.year}}
    </div>
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
{% endif %}
{% endfor %}

## Workshops

{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}
{% if pub.pub_type == "workshop" %}
<div class="pubitem">
  <div class="pubteaser">
    <a href="{{pub.url}}">
      {% if pub.video %}
      <img src="https://img.youtube.com/vi/{{pub.video}}/0.jpg" alt="{{pub.slug}} publication teaser"/>
      {% else %}
      <img src="/_images/_pub_images/{{ pub.slug }}_small.jpg" alt="{{pub.slug}} publication teaser"/>
      {% endif %}
    </a>
  </div>
  <div class="column">
    <a href="{{pub.url}}" class="nounderline">
      <div class="pubtitle">
        {{ pub.title }}
      </div>
    </a>
    <div class="pubauthors">
      {% for author in pub.authors %}
        {% assign author_without_space = author | remove: ' ' %}
        <a href="../People/{{author_without_space}}">{{author}}</a> {% unless forloop.last %},{% endunless %}
      {% endfor %}
      <!-- {{ pub.authors }} -->
    </div>
    <div class="pubinfo">
      {{ pub.publication }}, {{ pub.year}}
    </div>
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
{% endif %}
{% endfor %}

## Poster sessions

{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}
{% if pub.pub_type == "poster" %}
<div class="pubitem">
  <div class="pubteaser">
    <a href="{{pub.url}}">
      {% if pub.video %}
      <img src="https://img.youtube.com/vi/{{pub.video}}/0.jpg" alt="{{pub.slug}} publication teaser"/>
      {% else %}
      <img src="/_images/_pub_images/{{ pub.slug }}_small.jpg" alt="{{pub.slug}} publication teaser"/>
      {% endif %}
    </a>
  </div>
  <div class="column">
    <a href="{{pub.url}}" class="nounderline">
      <div class="pubtitle">
        {{ pub.title }}
      </div>
    </a>
    <div class="pubauthors">
      {% for author in pub.authors %}
        {% assign author_without_space = author | remove: ' ' %}
        <a href="../People/{{author_without_space}}">{{author}}</a> {% unless forloop.last %},{% endunless %}
      {% endfor %}
      <!-- {{ pub.authors }} -->
    </div>
    <div class="pubinfo">
      {{ pub.publication }}, {{ pub.year}}
    </div>
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
{% endif %}
{% endfor %}
