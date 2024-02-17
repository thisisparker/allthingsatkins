---
layout: page
title: Media
---

{{ site.data.media.description | markdownify }}

<ul>
{% for video in site.data.media.items %}
  <li>
    <p>{% if video.context %}<span class="video-context">{{ video.context }}</span>: {% endif %}<span class="video-title"><a href="{{ video.link }}">{{ video.title}}</a></span><!--{% if video.duration %} <span class="video-duration">({{ video.duration }})</span>{% endif %}--></p>
    <p class="video-description">{{ video.description | markdownify }}</p>
  </li>{% endfor %}
</ul>
