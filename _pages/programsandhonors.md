---
title: "Peixiao Wang (王培晓) - Gallery"
layout: gridlay
excerpt: "Peixiao Wang"
sitemap: false
permalink: /ProgramsAndHonors
---

<div class="col-sm-4" align="right" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="https://giserwang.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/pages/Word Art.jpeg" class="img-responsive" width="100%" /></a>
  <a href ="https://giserwang.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/pages/adminxxx.png" class="img-responsive" width="100%" /></a>
  </ul>
  The word cloud was made by <a href ="https://wordart.com/">WordArt</a><br>
</div>

<div class="col-sm-8">

## Program

<ol>
	{% for pprogram  in site.data.pprograms %}
		<li> {{pprogram.type}}:{{pprogram.name}}, {{pprogram.span}}, {{pprogram.fundingamount}}, {{pprogram.status}}, {{pprogram.role}}.<font color='white'>{{pprogram.grant}}</font></li>
	{% endfor %}
	<!--{% for cprogram  in site.data.cprograms %}
		<li> {{cprogram.type}}: {{cprogram.name}}, {{cprogram.span}}, {{cprogram.fundingamount}}, {{cprogram.role}}.<font color='white'>{{cprogram.grant}}</font></li>
	{% endfor %}-->
</ol>


## Honor

<ol>
	{% for honor in site.data.honors %}
		<li> {{honor.title}}, {{honor.year}}, {{honor.department}}. </li>
	{% endfor %}
</ol>


## Competition

<ol>
	{% for c in site.data.competitions %}
		<li> {{c.title}}, {{c.competition}}, {{c.year}}, {{c.department}}. </li>
	{% endfor %}
	<!--{% for cproject  in site.data.cprojects %}
		<li> {{cproject.type}}: {{cproject.name}}, {{cproject.span}}, {{cproject.fundingamount}}, {{cproject.role}}.<font color='white'>{{cproject.grant}}</font></li>
	{% endfor %}-->
</ol>


## Scholarship

<ol>
	{% for scholarship in site.data.scholarships %}
		<li> {{scholarship.title}}, {{scholarship.year}}, {{scholarship.department}}. </li>
	{% endfor %}
</ol>

</div>
