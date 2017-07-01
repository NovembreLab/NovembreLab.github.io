---
title: "Novembre Lab - Publications"
layout: gridlay
excerpt: "Novembre Lab -- Publications."
sitemap: false
permalink: /publications/
---

# Publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
