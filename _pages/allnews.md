---
title: "News"
layout: gridlay
excerpt: "Novembre Lab - News"
sitemap: false
permalink: /allnews.html
---

<div class="container-fluid">
  <!-- <div class="row"> -->
<img src= "{{ site.url }}{{ site.baseurl }}/images/chicagoskyline1.jpg"  class="img-responsive" style=" margin: 0 auto; width: auto;" />
  <!-- </div> -->
</div>

# News


{% for article in site.data.news %}
  <br>
  <b>{{ article.date }}</b> \: {{ article.headline }}
{% endfor %}
