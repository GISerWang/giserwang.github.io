---
title: "Peixiao Wang (王培晓) - Service"
layout: gridlay
excerpt: "Peixiao Wang: Service"
sitemap: false
permalink: service
---

<div class="col-sm-4" align="right" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="https://giserwang.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/pages/adminXX.jpg" class="img-responsive" width="100%" /></a>
  <a href ="https://giserwang.github.io"> <img align="right" src="{{ site.url }}{{ site.baseurl }}/images/pages/adminxxx.png" class="img-responsive" width="100%" /></a>
  </ul>
  The word cloud was made by <a href ="https://wordart.com/">WordArt</a><br>
<!--  Photoed at NJTECH <br> -->
</div>

<div class="col-sm-8">

## Academic Service

### Guest Editor

{% for specialissue in site.data.guesteditor %}

<a href="{{specialissue.url}}" target="_blank"> <img align="left" src="{{ site.url }}{{ site.baseurl }}/images/specialissues/{{ specialissue.image }}" width="12%"  /></a>

* <strong><a href="{{specialissue.siurl}}" target="_blank">{{specialissue.name}}</a><strong>
    - <strong>Journal Name</strong>: {{specialissue.journal}}
    - <strong>Guest Editors</strong>: {{specialissue.guesteditors}}

<br>

{% endfor %}

### Journal Reviewer

<ul>
	{% for journal  in site.data.jreviewer%}
		<li><p><a href="{{journal.url}}" target="_blank" >{{journal.name}}</a> </p></li>
	{% endfor %}
</ul>

### Conference Reviewer

<ul>
	{% for conference  in site.data.creviewer%}
		<li><p><a href="{{conference.url}}" target="_blank" >{{conference.name}}</a> </p></li>
	{% endfor %}
</ul>

## Public Repositories (Click to Visit)

<center class="left">
	<a href="https://github.com/giserwang" target="_blank"> <img align="left" src="{{ site.url }}{{ site.baseurl }}/images/logo/github.png" width="15%"/></a>
    <a href="https://blog.csdn.net/LoveCarpenter" target="_blank"> <img align="left" src="{{ site.url }}{{ site.baseurl }}/images/logo/csdn.jpeg" width="15%"/></a>
</center>

</div>
