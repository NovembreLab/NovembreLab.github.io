---
title: "News"
layout: textlay
excerpt: "Novembre Lab - News"
sitemap: false
permalink: /allnews.html
---

![]({{ site.url }}{{ site.baseurl }}/images/banner.jpg){: style="width: 1000px; float: right; border: 10px"}


# News

{% for article in site.data.news %}
  <br>
  <b>{{ article.date }}</b> {{ article.headline }}
{% endfor %}
