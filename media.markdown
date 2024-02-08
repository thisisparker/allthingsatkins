---
layout: page
title: Media
---

In my 15-year journey through media, I've navigated multimedia production for network television, independent films, documentaries, and internet broadcast. As an elite interviewer, I've spoken to a staggering array of subjects, for which I am incredibly grateful. My expertise extends to nonprofit videos, consistently well-regarded by local audiences. Enjoy the videos below, where narratives come to life with a personal touch.

<ul>
{% for video in site.data.media %}
  <li>
    <p>{% if video.context %}<span class="video-context">{{ video.context }}</span>: {% endif %}<span class="video-title"><a href="{{ video.link }}">{{ video.title}}</a></span>{% if video.duration %} <span class="video-duration">({{ video.duration }})</span>{% endif %}</p>
    <p class="video-description">{{ video.description }}</p>
  </li>{% endfor %}
</ul>
