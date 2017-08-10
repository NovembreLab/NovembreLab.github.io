---
title: "News"
layout: textlay
excerpt: "Novembre Lab - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
  <p><br>
  - {{ article.headline }} ({{ article.date }})</p>
{% endfor %}
