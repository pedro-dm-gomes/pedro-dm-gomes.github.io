---
title: "Research"
layout: gridlay
excerpt: "Pedro Gomes-- Research."
sitemap: false
permalink: /stuff/
---


# Research HighLights



<div class="row">


<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>Point Cloud Motion Forecasting via Graph‑based Machine Learning</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/GNN_box2.png" class="img-responsive" width="33%" style="float: left" />
  <p>We developed a technique for feature disentanglement  and feature visualization</p>
  <p><em> P.Gomes, S.Rossi, L.Toni</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>


</div>
</div>

<div class="row">


<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>Point Cloud Motion Forecasting via Graph‑based Machine Learning</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/GNN_box2.png" class="img-responsive" width="33%" style="float: left" />
  <p>We developed a technique for feature disentanglement  and feature visualization</p>
  <p><em> P.Gomes, S.Rossi, L.Toni</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>


</div>
</div>



<p> &nbsp; </p>


## Patents
<em>Milan P Allan, S Gröblacher, RA Norte, M Leeuwenhoek</em><br />Novel atomic force microscopy probes with phononic crystals<br /> PCT/NL20-20/050797 (2020)

<em>Milan P Allan</em><br /> Methods of manufacturing superconductor and phononic elements <br /> <a href="https://patents.google.com/patent/US10439125B2/en?inventor=Milan+ALLAN&oq=inventor:(Milan+ALLAN)">US10439125B2 (2016)</a>

## Full List of publications

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
