---
title: "Novembre Lab - Software"
layout: gridlay
excerpt: "Novembre Lab at UChicago"
sitemap: false
permalink: /software.html
---



## Software

Many of our projects are available via the [Novembre Lab Github Page](https://github.com/NovembreLab). Here are some of our software projects:

{% for soft in site.data.software %}

<div class="row">
<div class="col-sm-11 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/softpic/{{ soft.photo }}" class="img-responsive" width="120px" style="float: left; padding-right: 20px" />
  <h4><a href="{{soft.url}}" target="_blank">{{ soft.name }}</a></h4>
  <p>{{soft.desc}}</p>
</div>  
</div>

{% endfor %}

## Data Resources

[Resources related to Novembre et al 2008](https://github.com/jnovembre/Novembre_etal_2008_misc):  Several files that aid in recreating the main figure from our paper:“Genes Mirror Geography in Europe” (Nature 956:98-101).

[African-American/African-Caribbean recombination maps](https://jnpopgen.org/software/software/AfricanAmerican_AfricanCaribbean_recombination_maps.zip): Recombination maps inferred from a sample of 2565 African Americans and 299 African Caribbeans.  From our paper: Wegmann et al (2011) Nature Genetics 43:847-53.

Resources for Freedman et al 2014:  Fastq files are available via [SRA](http://www.ncbi.nlm.nih.gov/bioproject/PRJNA274504).  Auxiliary files such as vcf/bams are available via an sftp server. Please email – jnovembre at uchicago dot edu – for user and password.
