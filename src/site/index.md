---
title: Couple of Idjits
subtitle: An episode by episode podcast covering Supernatural
layout: layouts/base.njk
---

## Latest Episodes
<ul class="listing">
{%- for page in collections.episode | reverse -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Feeds

- [Spotify](https://open.spotify.com/show/6Ul9RlsGJhn9DrPJLejToE)
- [Stitcher](https://www.stitcher.com/podcast/couple-of-idjits)
- [XML Feed](http://cast.rocks/hosting/27557/feeds/CAURZ.jpg?e=0df284f)

## Connect

- Facebook Group - [Armchair Hunters](https://www.facebook.com/groups/437248500580788/)
- Email - [coupleofidjits.podcast@gmail.com](mailto:coupleofidjits.podcast@gmail.com)
- Penny Samuelson - [Facebook](https://www.facebook.com/penny.samuelsonconderman)
- Daniel Conderman - [YouTube](https://www.youtube.com/danconderman), [Facebook](https://www.facebook.com/conderman)

