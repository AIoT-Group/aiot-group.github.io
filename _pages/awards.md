---
title: "Awards"
layout: awards
excerpt: "Awards"
sitemap: true
permalink: /awards/
---


# Awards
<br>
<br>
<br>

{% for publi in site.data.awards %}
<div style="text-align: justify;">
  <ul>
     <li><p><b>{{ publi.achivement }},</b> "{{ publi.name }}," {{ publi.members }}, {{ publi.year}}.</p></li>
  <br>
  </ul>
</div>

  
{% endfor %}