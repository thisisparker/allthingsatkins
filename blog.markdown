---
layout: page
title: Blog
list_title: ''
noindex: true
---

{%- if site.posts.size > 0 -%}
{% include post_list.html posts=site.posts show_excerpt=true %}

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | relative_url }}">via RSS</a></p>
{%- endif -%}
