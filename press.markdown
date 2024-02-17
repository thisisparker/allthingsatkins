---
layout: page
title: Press Coverage
---

In the last decade of my career, I’ve shaped stories featured in outlets like the Los Angeles Times, WNYC, and WHYY, and supported press outreach and response for the environment, arts, politics, and music while bridging traditional to new media. I have had a lifelong exposure to newsrooms, as the son of a journalist. I enjoy assisting journalists and newsmakers in their storytelling and hope you enjoy the sample items below. 

<ul>
{% for clip in site.data.press.items %}
  <li>
     <p>{% if clip.outlet %}<span class="outlet-name">{{ clip.outlet }}</span>: {% endif %}<span class="outlet-headline"><a href="{{ clip.link }}">{{ clip.headline}}</a></span><br />
    <span class="clip-date">{{ clip.date }}</span></p>
    <blockquote class="clip-quote">{{ clip.quote }}</blockquote>
  </li>{% endfor %}
</ul>
