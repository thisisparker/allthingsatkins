---
layout: page
title: Writing
---

{{ site.data.writing.description | markdownify }}

<ul>
{% for piece in site.data.writing.items %}
  <li>
    <p>{% if piece.outlet %}<span class="outlet-name">{{ piece.outlet }}</span>: {% endif%}<a href="{{ piece.link }}">{{ piece.title }}</a>
    {{ piece.text | markdownify }}</p>
  </li>{% endfor %}
</ul>
