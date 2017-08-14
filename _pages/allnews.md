---
title: "News"
layout: textlay
excerpt: "Novembre Lab - News"
sitemap: false
permalink: /allnews.html
---

<!-- <div class="container-fluid">
  <div class="row">
![]({{ site.url }}{{ site.baseurl }}/images/banner.jpg){: style="display: block; margin: 0 auto; width: 900px; border: 10px"}
  </div>
</div> -->

# News

{% for article in site.data.news %}
  <br>
  <b>{{ article.date }}</b> \: {{ article.headline }}
{% endfor %}
