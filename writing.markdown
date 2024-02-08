---
layout: page
title: Writing
---

I have dedicated more than a decade to amplifying the intersections of arts, environment, and music. I contributed a series of impactful write-ups for Track 16, a prominent Los Angeles art gallery, where I’m especially proud to have highlighted the work of fabulous artists and share personal thoughts on the city of Los Angeles and its concrete river. Throughout two nonprofit communications directorships roles, I’ve orchestrated cohesive narratives across blogs, emails, promotional materials, and scripts as the architect of expressive content. If you're seeking a wordsmith to breathe life into your narratives with depth and resonance, consider this an invitation to explore the possibilities together. 

<ul>
{% for piece in site.data.writing %}
  <li>
    <p>{% if piece.outlet %}<span class="outlet-name">{{ piece.outlet }}</span>: {% endif%}<a href="{{ piece.link }}">{{ piece.title }}</a>
    {{ piece.text | markdownify }}</p>
  </li>{% endfor %}
</ul>
