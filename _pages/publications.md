---
title: "Novembre Lab - Publications"
layout: gridlay
excerpt: "Novembre Lab -- Publications."
sitemap: false
permalink: /publications/
---


<div class="container-fluid">
  <!-- <div class="row"> -->
<img src= "{{ site.url }}{{ site.baseurl }}/images/banner.jpg"  class="img-responsive" style=" margin: 0 auto; width: auto;" />
  <!-- </div> -->
</div>

# Selected Publications

For a full listing of publications see [Pubmed](http://www.ncbi.nlm.nih.gov/pubmed/?term=novembre+j+%5Bau%5D") or [Google Scholar](http://scholar.google.com/citations?user=wIib4t0AAAAJ).

Italics indicate current/former lab members.  * indicates authors contributed equally.

## Preprints

{% for publi in site.data.publist %}
 {% if publi.date > 2021 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/> 
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2020

{% for publi in site.data.publist %}
 {% if publi.date == 2020 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2019

{% for publi in site.data.publist %}
 {% if publi.date == 2019 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}


## 2018

{% for publi in site.data.publist %}
 {% if publi.date == 2018 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2017

{% for publi in site.data.publist %}
 {% if publi.date == 2017 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2016

{% for publi in site.data.publist %}
 {% if publi.date == 2016 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }} <br/> 
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2015

{% for publi in site.data.publist %}
 {% if publi.date == 2015 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/> 
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>
 
 {% endif %}
{% endfor %}

## 2014

{% for publi in site.data.publist %}
 {% if publi.date == 2014 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2013

{% for publi in site.data.publist %}
 {% if publi.date == 2013 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2012

{% for publi in site.data.publist %}
 {% if publi.date == 2012 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2011

{% for publi in site.data.publist %}
 {% if publi.date == 2011 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2010

{% for publi in site.data.publist %}
 {% if publi.date == 2010 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2009

{% for publi in site.data.publist %}
 {% if publi.date == 2009 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/>
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2008

{% for publi in site.data.publist %}
 {% if publi.date == 2008 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/> 
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>

 {% endif %}
{% endfor %}

## 2007 - 2000

{% for publi in site.data.publist %}
 {% if publi.date <= 2007 %}

 <b>{{ publi.title }}</b> <br/>
 {{ publi.authors }}<br/> 
 <a href="{{ publi.link.url }}">\[ {{ publi.link.journal }} {{publi.link.issuepage}} \]</a>
 
 {% endif %}
{% endfor %}
