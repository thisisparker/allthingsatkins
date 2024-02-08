---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
image: /assets/images/michael_and_lucy.jpg
---

<section id="main-image"><img src="{{ page.image }}" /></section>

<section id="intro">
{% capture intro %}{% include intro.markdown %}{% endcapture %}{{ intro | markdownify }}
</section>

<section id="more-bio">
{% capture bio %}{% include bio.markdown %}{% endcapture %}{{ bio | markdownify }}
</section>