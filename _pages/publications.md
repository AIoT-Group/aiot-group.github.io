---
title: "Publications"
layout: publication
excerpt: "Publications"
sitemap: true
permalink: /publications/
---


# Publications
Jump to: [Journal](#journals), [Conferences](#conferences)
## Journals
{% assign order = 1 %}
{% for publi in site.data.pub.journal %}
  
  {% increment order %}. {{ publi.authors }}, "<a href="{{ publi.link.url }}">{{ publi.title }}</a>," {{ publi.link.display }}

{% endfor %}

## Conferences
{% assign order = 1 %}
{% for publi in site.data.pub.conf %}
  
  {% increment order %}. {{ publi.authors }}, "<a href="{{ publi.link.url }}">{{ publi.title }}</a>," {{ publi.link.display }}

{% endfor %}
