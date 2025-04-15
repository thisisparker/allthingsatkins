---
layout: home
image: /assets/uploads/michael_and_lucy.jpg
intro: >-
  Ahoy!


  My name is Michael Atkins. I’m a communicator strategist and multimedia producer with a passion for storytelling, civic engagement, and all things offbeat. I love to explore the built and natural environments, and love connecting people to their local ecosystem. Watch [my videos](/media), read [my writing](/writing), and check out [my press coverage](/press).
bio: >-
  In my professional life I’ve worked for television and film productions and
  nonprofits. I currently serve as the Executive Director of the [Atlantic City
  Arts Foundation](https://atlanticcityartsfoundation.org/) promoting public
  arts in America's playground. I've served as Communications Director for [New
  Jersey Future](<>), a statewide policy nonprofit that advances placemaking and
  urbanism throughout the Garden State, and [Friends of the Los Angeles
  River](https://folar.org/), which organizes the largest urban river cleanup in
  the nation, and advocates for equitable access and a rewilded river in the
  heart of Los Angeles. 


  I've interviewed a wide range of interesting subjects including: authors, artists, architects, active military personnel, congresspersons, historians, and indigenous tribal leaders along the way. I’ve worked political campaigns for local, state, and federal office, and volunteered for public interest endeavors, including the [Baseball Reliquary](https://baseballreliquary.org/) and [Cape May Bird Observatory](https://njaudubon.org/centers/cape-may-bird-observatory/) with elected board positions with [KPFK Los Angeles](https://www.kpfk.org/) and the [East Hollywood Neighborhood Council](https://www.easthollywood.net/). 


  I proudly live in Atlantic City, NJ. Contact me at [michael@allthingsatkins.com](mailto:michael@allthingsatkins.com). Preferably from a pay phone.
link_cards: 
   - text: Calendar of Song
     link: /calendar
   - text: Pages A-Z
     link: /pages
   - text: Blog
     link: /blog
list_title: Recent posts
---

<section id="main-image"><img src="{{ page.image | relative_url }}" /></section>

<section id="intro">{{ page.intro | markdownify }}
</section>

<section id="link-cards">
{% for card in page.link_cards %}
<div><a href="{{ card.link }}"><h2>{{ card.text }}</h2></a></div>
{% endfor -%}
</section>

<section id="more-bio">{{ page.bio | markdownify }}
</section>

<style>
#link-cards {
display: flex;
align-items: stretch;
gap: 30px;
margin-bottom: 15px;
  div {
    padding: 10px;
    border: thick double #020788;
    flex: 1;
    text-align: center;
    a {
      display: flex;
      flex-direction: column;
      justify-content: center;
      width: 100%;
      height: 100%;
      color: #111;
      text-decoration: none;
      :hover {
        text-decoration: underline;
      }
    }
    h2 {
      margin-bottom: 0;
    }
  }
@media (max-width: 600px) {
  flex-direction: column
}
}

</style>
