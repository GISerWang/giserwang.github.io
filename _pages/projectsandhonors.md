---
title: "Peixiao Wang (王培晓) - Gallery"
layout: gridlay
excerpt: "Peixiao Wang"
sitemap: false
permalink: /ProjectsAndHonors
---

<div class="col-sm-4" align="right" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="https://giserwang.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/pages/Word Art.jpeg" class="img-responsive" width="100%" /></a>
  <a href ="https://giserwang.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/pages/adminxxx.png" class="img-responsive" width="100%" /></a>
  </ul>
  The word cloud was made by <a href ="https://wordart.com/">WordArt</a><br>
</div>

<div class="col-sm-8">

## Project

<ol>
	{% for pproject  in site.data.pprojects %}
		<li> {{pproject.type}}: {{pproject.name}}, {{pproject.span}}, {{pproject.fundingamount}}, {{pproject.status}}, {{pproject.role}}.<font color='white'>{{pproject.grant}}</font></li>
	{% endfor %}
	<!--{% for cproject  in site.data.cprojects %}
		<li> {{cproject.type}}: {{cproject.name}}, {{cproject.span}}, {{cproject.fundingamount}}, {{cproject.role}}.<font color='white'>{{cproject.grant}}</font></li>
	{% endfor %}-->
</ol>


## Honor

<ol>
	{% for honor in site.data.honors %}
		<li> {{honor.title}}, {{honor.year}}, {{honor.department}}. </li>
	{% endfor %}
</ol>
<!--
{% for honor in site.data.honors %}

<div class="col-sm-12 clearfix">
 <div class="well">
 <pubtit>{{ honor.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/honors/{{ honor.image }}" class="img-responsive" width="180px" style="float: left" />

 <p>{{ honor.description }}</p>

 <p><em>{{ honor.names }}</em></p>

 <p>{{ honor.year }}, {{ honor.department }} </p>

 </div>
</div>

{% endfor %}
-->
## Scholarship

<ol>
	{% for scholarship in site.data.scholarships %}
		<li> {{scholarship.title}}, {{scholarship.year}}, {{scholarship.department}}. </li>
	{% endfor %}
</ol>
<!--
{% for scholarship in site.data.scholarships %}

<div class="col-sm-12 clearfix">
 <div class="well">
 <pubtit>{{ scholarship.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/honors/{{ scholarship.image }}" class="img-responsive" width="180px" style="float: left" />

 <p>{{ scholarship.description }}</p>

 <p><em>{{ scholarship.names }}</em></p>

 <p>{{ scholarship.year }}, {{ scholarship.department }}</p>
 
 <p></p>
 
 </div>
</div>

{% endfor %}
-->

## Competition

<ol>
	{% for c in site.data.competitions %}
		<li> {{c.title}}, {{c.competition}}, {{c.year}}, {{c.department}}. </li>
	{% endfor %}
	<!--{% for cproject  in site.data.cprojects %}
		<li> {{cproject.type}}: {{cproject.name}}, {{cproject.span}}, {{cproject.fundingamount}}, {{cproject.role}}.<font color='white'>{{cproject.grant}}</font></li>
	{% endfor %}-->
</ol>
<!--
{% for competition in site.data.competitions %}

<div class="col-sm-12 clearfix">
 <div class="well">
 <pubtit>{{ honor.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ competition.image }}" class="img-responsive" width="180px" style="float: left" />

 <p>{{ competition.description }}</p>

 <p><em>{{ competition.authors }}</em></p>

 <p>{{ competition.venue }}</p>
 
 <p>{{ competition.name }}</p>
 
 <p>{{ competition.DOI }}</p>
 </div>
</div>

{% endfor %}
-->
</div>