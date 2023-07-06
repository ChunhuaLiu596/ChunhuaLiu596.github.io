---
layout: page
---
<div class="row">
    <div class="col-sm-3"><img src="{{ site.baseurl }}public/blcu16.JPG" alt="Photo of Chunhua"></div> 
    <div class="col-sm-9">
	  <div class="row">
	    <div class="col-sm-3">
	      <b>Chunhua Liu</b>
	      <br>PhD Student
	      <address>
		Melbourne Connect
	      </address>
	    </div>
		<div class="col-sm-7">
		  <a href="http://www.cis.unimelb.edu.au">Computing and Information Systems</a><br/>
		  <a href="http://www.unimelb.edu.au">The University of Melbourne</a><br/>
		  <a href="http://uom-nlp.github.io/">Natural Language Processing group</a>
		</div>
	  </div>
	  <div class="row">
	    <div class="col-sm-3">
	<script type="text/javascript"><!--
	document.write('<a href="' +
	'mailto:t' +
	'cohn@uni' +
	'melb.edu' +
	'.au
">' +
	'<span class="glyphicon glyphicon-envelope"></span></a> Email');
	//-->
	</script>
	<noscript><IMG alt="E-mail" border=0 src="./email.png"></noscript>
	    </div>
	    <div class="col-sm-7"> Ph: +61000000000 </div>
	    </div>
	</div>
    </div>

<p class="message">
I am a PhD student in natural language processing at The University of Melbourne under the supervision of <a href="https://people.eng.unimelb.edu.au/tcohn/">Trevor Cohn</a> and <a href="https://www.frermann.de//">Lea Frermann</a>. My research interests center around understanding the structure and relationships between concepts through interdisciplinary perspectives, including natural language processing and cognitive psychology. With a specific emphasis on understanding the structure and reasons behind human word associations, evaluating the potential of word associations as a source of commonsense knowledge and incorporating commonsense knowledge to improve neural models' reasoning ability on tasks, such as commonsense question answering and natural language inferences. Additionally, I am interested in exploring concept representation and categorization across languages and cultures.
</p>

<h3>News</h3>
<ul>
{% for item in site.data.news.posts %}
  <li><i>{{ item.date }}</i>: {{ item.text }}</li>
{% endfor %}
</ul>

<h3>Recent Papers</h3>
{% for year in (2021..2023) %}
  {% include publications.html year=year %}
{% endfor %}

