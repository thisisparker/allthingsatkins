---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: /assets/images/michael_and_lucy.jpg
---

<section id="main-image"><img src="{{ page.image | relative_url }}" /></section>

<section id="intro">{{ site.data.homepage.intro | markdownify }}
</section>

<section id="more-bio">{{ site.data.homepage.bio | markdownify }}
</section>