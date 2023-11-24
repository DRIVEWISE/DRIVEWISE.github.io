---
title: "People"
layout: single
permalink: /People/
image_path: ../_images/_people/
classes: wide
author_profile: true
---
<style>
  .inner {
    max-width: 95%;
  }

  .member-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .member-container .member {
    text-align: center;
    margin: 5px;
    flex: 1 0 50%;
    max-width: 30%;
    min-width: 100px;
  }

  .member-container .member .image-container {
    width: 100%;
    padding-bottom: 0%;
    position: relative;
    border-radius: 50%;
    overflow: hidden;
  }

  .member-container .member .image-container:before {
    content: "";
    display: block;
    padding-top: 100%;
  }

  .member-container .member .image-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top center;
    position: absolute;
    top: 0;
    left: 0;
  }

  .member-container2 {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .member-container2 .member2 {
    text-align: center;
    margin: 5px;
    flex: 1 0 30%;
    max-width: 20%;
    min-width: 80px;
  }

  .member-container2 .member2 .image-container2 {
    width: 100%;
    padding-bottom: 0%;
    position: relative;
    border-radius: 50%;
    overflow: hidden;
  }

  .member-container2 .member2 .image-container2:before {
    content: "";
    display: block;
    padding-top: 100%;
  }

  .member-container2 .member2 .image-container2 img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top center;
    position: absolute;
    top: 0;
    left: 0;
  }

  .member-container3 {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .member-container3 .member3 {
    text-align: center;
    margin: 5px;
    flex: 1 0 30%;
    max-width: 20%;
    min-width: 80px;
  }

  .member-container3 .member3 .image-container3 {
    width: 100%;
    padding-bottom: 0%;
    position: relative;
    border-radius: 50%;
    overflow: hidden;
  }

  .member-container3 .member3 .image-container3:before {
    content: "";
    display: block;
    padding-top: 100%;
  }

  .member-container3 .member3 .image-container3 img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top center;
    position: absolute;
    top: 0;
    left: 0;
  }

</style>

  <h2>Professor and senior members</h2>

  <div class="member-container">
  
  {% assign filtered_people = "" | split: "," %}
  {% for person in site.people_pages %}
    {% if person.member_type == "professor" or person.member_type == "senior" %}
      {% assign filtered_people = filtered_people | push: person %}
    {% endif %}
  {% endfor %}
  {% assign people = filtered_people | sort: "surname" %}
  {% assign people = people | sort: "seniority" %}

  {{ people | size }}

  </div>