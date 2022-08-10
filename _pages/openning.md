---
title: "Openning"
layout: openning
excerpt: "Openning"
sitemap: true
permalink: /openning/
---


# Openning

Jump to: [Introduction](#introduction), [Research Assistant](#researchassistant), [Students](#student)
## Introduction

{% for publi in site.data.openning.introduction %}
<h3>{{ publi.content_areas }}</h3>
  <h5>{{ publi.title_specialized }}</h5>
  <p>{{ publi.experience }}</p>
  <ul>
  {% for vacancie in publi.vacancies %}
    <li>{{ vacancie }}</li>
    {% endfor %}
    </ul>
  <p>{{ publi.content_1 }}<br>{{ publi.content_2 }}</p>
  <br>
  <!-- <a href="{{ publi.link.url }}">{{ publi.title }}</a> -->

  
{% endfor %}

## ResearchAssistant

{% for publi in site.data.openning.researchassistant %}
  <h3>{{ publi.title }}</h3>
  <h5>{{ publi.title_specialized }}</h5>
  <ul>
  {% for vacancie in publi.vacancies %}
    <li>{{ vacancie }}</li>
    {% endfor %}
    </ul>
   <br>
   <p><b>To apply, please email CV and supporting documents to:  <a href="{{ publi.link }}"> {{ publi.title_specialized }}</a></b></p>
{% endfor %}

## Student

{% for publi in site.data.openning.student %}
  <h3>{{ publi.title }}</h3>
  <h5>{{ publi.title_specialized }}</h5>
  <ul>
  {% for vacancie in publi.vacancies %}
    <li>{{ vacancie }}</li>
    {% endfor %}
    </ul>
   <br>
   <p><b>To apply, please email CV and supporting documents to:  <a href="{{ publi.link }}"> {{ publi.title_specialized }}</a></b></p>
{% endfor %}