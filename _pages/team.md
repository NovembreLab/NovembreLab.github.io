---
title: "Novembre Lab - Team"
layout: gridlay
excerpt: "Novembre Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

<div class="row">

<div class="col-sm-11 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="20%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{member.info}}</i></h5>
  <p>{{member.blurb}}</p>
</div>


</div>

{% endfor %}


# Alumni

* Mark Reppell  
* Diego Ortega del Vecchyo?
* Dan Wegmann


# Lab Guests

* Enrique Lessa
