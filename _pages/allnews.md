---
title: "Home"
layout: textlay
excerpt: "Novembre Lab at UChicago"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
  <p><br>
  - {{ article.headline }} ({{ article.date }})</p>
{% endfor %}
