---
title: "Awards"
layout: awards
excerpt: "Awards"
sitemap: true
permalink: /awards/
---


# Awards

{% for publi in site.data.awards %}
<div style="text-align: justify;">
  <ul>
     <li><p><b>{{ publi.achivement }},</b> "{{ publi.name }}," {{ publi.members }}, {{ publi.year}}.</p></li>
  </ul>
</div>

  
{% endfor %}