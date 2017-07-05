---
title: "Novembre Lab - Publications"
layout: gridlay
excerpt: "Novembre Lab -- Publications."
sitemap: false
permalink: /publications/
---
<!-- TODO : make the segmentation by date a little bit easier to read -->

# Publications

{% assign years = "2017|2016|2015" | split: "|" %}

{% for y in years  %}

## {{ y }}

{% for publi in site.data.publist %}
 {% if publi.date == "{{ y }}" %}

  <b>{{ publi.title }}</b> <br/>
  <em>{{ publi.authors }} </em> <br/> <a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

 {% endif %}
{% endfor %}

{% endfor %}
