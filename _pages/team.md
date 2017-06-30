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

{% assign even_odd = number_printed | modulo: 1%}

{% if even_odd == 0 %}
  <div class="row">
{% endif %}

<div class="col-sm-11 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="20%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <h5><i>{{member.info}}</i></h5>
  <p>{{member.blurb}}</p>
</div>


{% if even_odd == 0 %}
</div>
{% endif %}

{% endfor %}


# Alumni

<!-- <table align="center" style="width:100%">
<tr><th>Visitors</th>
    <th>Master Students</th>
    <th>Bachelor Students</th>
  </tr>
  <tr>
    <td>Nikolaos Iliopoulos, Spring 2016</td>
    <td>Oliver Ostojic, Spring 2016</td>
    <td>Alexander Vanstone, Spring 2016</td>
  </tr>
  <tr>
    <td>Vitaly Feedosev, all of 2016</td>
    <td>Farshaad Hoeseni, Fall 2015</td>
    <td>Tjerk Benschop, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Arjo Andringa, Spring 2016</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>Daniëlle van Klink, Spring 2016</td>
  </tr>
</table> -->

# Lab Guests
