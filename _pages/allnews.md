---
title: "Home"
layout: textlay
excerpt: "Novembre Lab at UChicago"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
  <p>{{ article.date }} <br>
  <em>{{ article.headline }}</em></p>
{% endfor %}
