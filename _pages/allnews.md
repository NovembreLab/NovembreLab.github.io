---
title: "News"
layout: textlay
excerpt: "Novembre Lab - News"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
  <p>{{ article.date }} <br>
  <b>{{ article.headline }}</b>
  {% if article.blurb %}
    {{ article.blurb }}
  {% endif %}
  </p>
{% endfor %}
