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

- [Ben Peter](http://www.eva.mpg.de/genetics/staff/benjamin-peter/index.html): Postdoctoral Fellow, 2014-2017
- [Mark Reppell](http://mreppell.github.io/): Postdoctoral Fellow, 2014-2017.
- [Diego Ortega Del Vecchyo](http://diegoortega.bol.ucla.edu/): PhD student in Bioinformatics, Finished 2016.
- [Charleston Chiang](https://sites.google.com/site/charlestonchiang/): Postdoctoral Fellow, 2011-2015.
- [Alex Platt](http://www.alexanderplatt.org): Research Associate, 2011-2014.
- [Eunjung/Christine Han](https://www.linkedin.com/pub/eunjung-christine-han/85/5a8/510): PhD student in Biostatistics, Finished 2014.
- [Darren Kessner](https://www.linkedin.com/in/darrenkessner): PhD student in Bioinformatics, Finished 2014.
- [Adam Freedman](https://www.linkedin.com/pub/adam-freedman/17/811/b92): NSF Bioinformatics Postdoctoral Fellow, 2009-2012
- [Colin Rundel](https://stat.duke.edu/~cr173/): PhD student in Statistics, Joint advised with Jan de Leeuw.  Finished 2012.
- [Daniel Wegmann](http://www.unifr.ch/biochem/index.php?id=789): Postdoctoral fellow, 2009-2011.
- [David Alexander](http://dalexander.github.io/): PhD student in Biomathematics and Collaborator. Finished 2011.
- [Krishna Veeramah](http://life.bio.sunysb.edu/ee/veeramahlab/): Center for Society and Genetics Postdoctoral fellow, 2008-2010
