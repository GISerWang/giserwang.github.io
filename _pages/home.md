---
title: "Peixiao Wang (王培晓) - Homepage"
layout: gridlay
excerpt: "Peixiao Wang"
sitemap: false
permalink: /
---

<!-- <div id="top"></div> -->
<div class="container-fluid">
<div class="row">
<div class="col-sm-8">

### **About <font color="#00d1ff">Me</font> (Peixiao Wang)**
I come from Jinan, Shandong, China, where is known as 'City of Springs'. 
I am currently a Postdoctoral Fellow under the supervision of <a href="http://www.igsnrr.cas.cn/sourcedb_igsnrr_cas/zw/dsjs/bssds/dtxydlxx/200906/t20090626_1842363.html" target="_blank">Prof. Feng Lu</a> from <a href="http://www.lreis.ac.cn/" target="_blank">State Key Laboratory of Resources and Environmental Information System</a>, <a href="http://www.igsnrr.ac.cn/" target="_blank">Institute of Geographic Sciences and Nature Resources Research, Chinese Academy of Sciences</a>.
I received Ph.D. degree under the supervision of <a href="http://www.lmars.whu.edu.cn/prof_web/zhangtong/index.html" target="_blank">Prof. Tong Zhang</a> from <a href="http://liesmars.whu.edu.cn/" target="_blank">State Key Laboratory of Information Engineering in Surveying, Mapping and Remote Sensing</a>, <a href="https://www.whu.edu.cn/" target="_blank">Wuhan University</a> in 2023, 
and received the M.S. degree under the supervision of <a href="http://adcfj.cn/sirc/door/team/TeacherList/Detail?personId=422" target="_blank">Prof. Sheng Wu</a> from <a href="https://adc.fzu.edu.cn/" target="_blank">The Academy of Digital China</a>, <a href="https://www.fzu.edu.cn/" target="_blank">Fuzhou University</a> in 2020.
<br>
My research interests include Spatiotemporal data mining, Spatiotemporal prediction, Social computing, and Public health, especially focus on Spatiotemporal prediction of transportation systems.
<br>

### **CV**
You can download my latest CV (<a href="https://giserwang.github.io/papers/resume/Peixiao Wang's CV.pdf" target="_blank">English Version</a> and <a href="https://giserwang.github.io/papers/resume/王培晓的简历.pdf" target="_blank">Chinese Version</a>).<br>
CV was last updated on 2023.5.07. <br>



### **News** 
{% for article in site.data.news limit:4 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{{article.news}}
{{article.hot}}
{% endfor %}

#### <a href="{{ site.url }}{{ site.baseurl }}/allnews" class="btn-xs btn-success">See All News</a>


</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="{{ site.url }}{{ site.baseurl }}/experience"> <img src="{{ site.url }}{{ site.baseurl }}/images/pages/adminRX.jpg" class="img-responsive" width="100%" alt="我自己"/></a>
  </ul>

  <!-- <br clear="all" /> -->

  Peixiao Wang<br> 
  
  王培晓<br> 
  
  100101 post code, A11 Datun Road, Chaoyang District (<a href="https://j.map.baidu.com/95/6bK">Maps</a>).<br>
  
  <a href="http://www.lreis.ac.cn/" target="_blank">State Key Laboratory of Resources and Environmental Information System</a>, 
  
  <a href="http://www.igsnrr.ac.cn/" target="_blank">Institute of Geographic Sciences and Nature Resources Research, Chinese Academy of Sciences</a>
  ,Beijing, China. <br> 
  
  <script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=LApw56d6sOaj2ITovU21uzUMrlCCVzPAna_WqNKoZPk"></script>
</div>

</div>
</div>

<div class="col-sm-12">

### **Publications (<font color="red">Journal Papers</font> <font color="green">&</font> <font color="blue">Conference Papers</font>)**

<!-- #### * means corresponding authors -->

{% for publi in site.data.reppublist limit:3 %}

<div class="col-sm-11 clearfix">
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

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications" class="btn-xs btn-success">See All Publications</a>

<!-- #### <a href="#top" class="btn-xs btn-primary">Go Back to Top</a> -->

### **Academic Related**

#### **Project (<font color="red">Principle Investigator</font> <font color="green">&</font> <font color="blue">Co-Principle Investigator</font>)**

<ul>
    <li><strong>Project in Progress</strong></li>
	<ul>
	{% for pproject  in site.data.pprojects limit:4 %}
		<li> {{pproject.type}}:{{pproject.name}}, {{pproject.span}}, {{pproject.fundingamount}}, {{pproject.role}}.</li>
	{% endfor %}
	</ul>
</ul>

<!--<ul>
    <li><strong>Completed Project</strong></li>
	<ul>
    {% for cproject  in site.data.cprojects limit:4 %}
		<li> {{cproject.type}}: {{cproject.name}}, {{cproject.span}}, {{cproject.fundingamount}}, {{cproject.role}}.</li>
	{% endfor %}
	</ul>
</ul>-->


#### **Award & Honor**

<ul>
    <li><strong>Honor</strong></li>
	<ul>
	{% for honor in site.data.honors %}
		<li> {{honor.title}}, {{honor.year}}, {{honor.department}}. </li>
	{% endfor %}
	</ul>
</ul>

<ul>
    <li><strong>Competition</strong></li>
	<ul>
	{% for c in site.data.competitions %}
		<li> {{c.title}}, {{c.competition}}, {{c.year}}, {{c.department}}. </li>
	{% endfor %}
	</ul>
</ul>

<ul>
    <li><strong>Scholarship</strong></li>
	<ul>
	{% for scholarship in site.data.scholarships %}
		<li> {{scholarship.title}}, {{scholarship.year}}, {{scholarship.department}}. </li>
	{% endfor %}
	</ul>
</ul>

#### **Academic Service**

<ul>
    <li><strong>Journal Reviewer</strong></li>
	<ul>
	{% for journal  in site.data.jreviewer limit:5 %}
		<li> <a href="{{journal.url}}" target="_blank" >{{journal.name}}</a> </li>
	{% endfor %}
	    <li> <a href="{{ site.url }}{{ site.baseurl }}/service" class="btn-xs btn-success">See All Journals</a> </li>
	</ul>
</ul>


<ul>
    <li><strong>Conference Reviewer</strong></li>
	<ul>
	{% for conference  in site.data.creviewer limit:5 %}
		<li> <a href="{{conference.url}}" target="_blank" >{{conference.name}}</a> </li>
	{% endfor %}
	    <li> <a href="{{ site.url }}{{ site.baseurl }}/service" class="btn-xs btn-success">See All Conferences</a> </li>
	</ul>
</ul>



