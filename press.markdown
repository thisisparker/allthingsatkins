---
layout: page
title: Press Coverage
---

{{ site.data.press.description | markdownify }}

<ul>
{% for clip in site.data.press.items %}
  <li>
     <p>{% if clip.outlet %}<span class="outlet-name">{{ clip.outlet }}</span>: {% endif %}<span class="outlet-headline"><a href="{{ clip.link }}">{{ clip.headline}}</a></span><br />
    <span class="clip-date">{{ clip.date }}</span></p>
    <blockquote class="clip-quote">{{ clip.quote | markdownify }}</blockquote>
  </li>{% endfor %}
</ul>
