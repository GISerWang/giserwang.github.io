---
title: "Peixiao Wang (王培晓) - Publications"
layout: gridlay
excerpt: "Peixiao Wang -- Publications."
sitemap: false
permalink: /publications
---
## Representative Publications (Up to Five)
{% for publi in site.data.reppublist %}

<div class="col-sm-12 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>
 
 <p>{{ publi.name }}</p>
 
 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 {% endif %}
 
 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-danger">{{ publi.link3.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a>
 <a href="{{ publi.link5.url }}" target="_blank" class="btn btn-warning">{{ publi.link5.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 6 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a>
 <a href="{{ publi.link5.url }}" target="_blank" class="btn btn-warning">{{ publi.link5.display }}</a>
 <a href="{{ publi.link6.url }}" target="_blank" class="btn btn-danger">{{ publi.link6.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}



##  All Publications
<div class="col-sm-12 clearfix">
 <div class="well well-sm">
  <p style="color: red; font-weight: bold;">2024:</p>
  {% for publi in site.data.publist_2024 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2023:</p>
  {% for publi in site.data.publist_2023 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2022:</p>
  {% for publi in site.data.publist_2022 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2021:</p>
  {% for publi in site.data.publist_2021 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2020:</p>
  {% for publi in site.data.publist_2020 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2019:</p>
  {% for publi in site.data.publist_2019 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2018:</p>
  {% for publi in site.data.publist_2018 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
   
  <p><font color="red"><strong>Note:</strong>The Geographical Society of China (GSC), China Institute of Communications (CIC), Architectural Society of China (ASC), Journal Citation Reports (JCR)</font></p>
 </div>
</div>


<p> &nbsp; </p>


