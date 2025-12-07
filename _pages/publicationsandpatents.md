---
title: "Peixiao Wang (王培晓) - Publications"
layout: gridlay
excerpt: "Peixiao Wang -- Publications."
sitemap: false
permalink: /publicationsandpatents
---
## Representative Publications (Top Five)
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
 
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-danger">{{ publi.link3.display }}</a></p>



 </div>
</div>

{% endfor %}



##  All Publications
<div class="col-sm-12 clearfix">
 <div class="well well-sm">
  <p style="color: red; font-weight: bold;">2026 (*Corresponding Author, #Students under My Supervision):</p>
  {% for publi in site.data.publist_2026 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2025 (*Corresponding Author, #Students under My Supervision):</p>
  {% for publi in site.data.publist_2025 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2024 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2024 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2023 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2023 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2022 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2022 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2021 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2021 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2020 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2020 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2019 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2019 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
  
  <p style="color: red; font-weight: bold;">2018 (*Corresponding Author):</p>
  {% for publi in site.data.publist_2018 %}
   <p>[{{forloop.index}}] {{ publi.REF }}[<a href='{{ publi.URL }}' target="_blank">{{ publi.TYPE }}</a>]</p>
   {% endfor %}
   
  <p><font color="red"><strong>Note:</strong>Journal Citation Reports (JCR), Chinese Academy of Sciences (CAS), The Geographical Society of China (GSC), China Institute of Communications (CIC), Architectural Society of China (ASC), Journal Citation Reports (JCR)</font></p>
 </div>
</div>

##  All Patents
<div class="col-sm-12 clearfix">
 <div class="well well-sm">
  {% for publi in site.data.patents %}
   <p>[{{forloop.index}}] {{ publi.REF }}</p>
   {% endfor %}
 </div>
</div>




<p> &nbsp; </p>


