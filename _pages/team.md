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
 After more than ten years now as a lab, we have an even spread of alumni that have gone into academics and industry. Thus far, geographically our alumni can be found in the United States, Mexico, Canada, Switzerland, and Germany.  While we work in a university setting and train ourselves in the practice of research and teaching, this prepares our alumni for a broad set of careers.
- [Mashaal Sohail](https://www.sohaillab.com): Chicago Fellow, 2019-2021.  Associate Professsor, UNAM. 
- [Chi Chun Liu](https://www.linkedin.com/in/chi-chun-liu/): Masters student, 2019-2020.  Machine learning engineer, Prooton, Inc.
- [Arjun Biddanda](https://aabiddanda.github.io/) : PhD in Human Genetics, 2020.  Computational scientist, 54gene.
- [Dan Rice](https://dp-rice.github.io/): Chicago Fellow, 2017-2020. Data Scientist Outreach Coordinator at NCBI.  
- [Joe Marcus](https://www.linkedin.com/in/joseph-marcus-661bb3ab/): PhD in Human Genetics, 2020.  Bioinformatic Scientist at Grail, Inc.
- [Harald Ringbauer](https://reich.hms.harvard.edu/people/harald-ringbauer): Postdoctoral fellow, 2018-2019.  Group leader at Max Planck Institute for Evolutionary Anthropology.
- [Christian Porras](https://www.linkedin.com/in/cporras) : Undergraduate researcher.  Now an MD/PhD student at the Icahn School of Medicine at Mount Sinai.
- [Hussein Al-asadi](https://www.linkedin.com/in/hussein-al-asadi-82b5b71b): PhD student in Committee of Evolutionary Biology, Masters in Statistcs, 2018.  Data scientist at Adaptive biotech.  
- [Evan Koch](https://emkoch.github.io): PhD student in Ecology & Evolution, 2018.  Postdoctoral fellow with Shamil Sunyaev at Harvard.
- [Joel Smith](https://www.linkedin.com/in/joel-smith-36a32a149): PhD student in Ecology & Evolution, 2018.  Scientist at Zymeworks.
- [Ben Peter](http://www.eva.mpg.de/genetics/staff/benjamin-peter/index.html): Postdoctoral Fellow, 2014-2017.  Group leader at Max Planck Institute for Evolutionary Anthropology.
- [Mark Reppell](https://www.linkedin.com/in/mark-reppell-9870a981): Postdoctoral Fellow, 2014-2017.  Senior scientist at Abbvie Genomics.
- [Diego Ortega Del Vecchyo](http://diegoortega.bol.ucla.edu/): PhD student in Bioinformatics, 2016.  Group leader, Institute for Human Genomics in Mexico.  
- [Charleston Chiang](https://chianglab.usc.edu): Postdoctoral Fellow, 2011-2015. Assistant Professor, Center for Genetic Epidemiology, Keck School of Medicine of University of Southern California.
- [Alex Platt](http://www.alexanderplatt.org): Research Associate, 2011-2014.  Research Assistant Professor, Center for Computational Genetics and Genomics at Temple University.
- [Eunjung/Christine Han](https://www.linkedin.com/pub/eunjung-christine-han/85/5a8/510): PhD student in Biostatistics, 2014.  Research Scientist at Amazon Alexa Machine Learning.
- [Darren Kessner](https://www.linkedin.com/in/darrenkessner): PhD student in Bioinformatics, 2014.  Computer science faculty at Marlborough School.
- [Adam Freedman](https://www.linkedin.com/pub/adam-freedman/17/811/b92): NSF Bioinformatics Postdoctoral Fellow, 2009-2012.  Data Scientist in the Faculty of Arts and Sciences Informatics Group at Harvard University.
- [Colin Rundel](https://stat.duke.edu/~cr173/): PhD student in Statistics, Joint advised with Jan de Leeuw, 2012. 'Professor of the practice' at Duke.
- [Daniel Wegmann](http://www.unifr.ch/biochem/index.php?id=789): Postdoctoral fellow, 2009-2011. Professor in Computational Biology, University of Fribourg.
- [David Alexander](http://dalexander.github.io/): PhD student in Biomathematics and Collaborator advised by Ken Lange.  2011.  Bioinformatics at Google.
- [Krishna Veeramah](http://life.bio.sunysb.edu/ee/veeramahlab/): Center for Society and Genetics Postdoctoral fellow, 2008-2010.  Associate Professor, Department of Ecology & Evolution, Stony Brook University.  

# Photo Gallery

A small sampling from over the ages...
{% assign number_printed = 0 %}
{% for member in site.data.teamgalleryphotos %}

<div class="row">

<div class="col-sm-11 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="60%" style="float: left" />
  <p>{{member.caption}}</p>
</div>

</div>

{% endfor %}
