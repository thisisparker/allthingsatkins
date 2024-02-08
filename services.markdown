---
layout: page
title: Services
---

Michael Atkins is available to contract for communications consultation, multimedia production, and private naturalist walks. Rates vary depending upon the scale of the consultation project, with in-kind opportunities available for nonprofit endeavors. Read the list of services offered below and use the contact form to request services. 

<ul>
{% for service in site.data.services %}
  <li>
    <p><strong>{{ service.title }}</strong></p>
    <p>{{ service.description }}</p>
  </li>{% endfor %}
</ul>
