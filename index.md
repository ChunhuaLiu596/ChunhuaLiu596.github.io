---
layout: page
---
<div class="row">
    <div class="col-sm-3"><img src="{{ site.baseurl }}public/blcu16.JPG" alt="Photo of Chunhua"></div> 
    <div class="col-sm-9">
	  <div class="row">
	    <div class="col-sm-3">
	      <b>Chunhua Liu</b>
	      <br>Postdoc Research Fellow and Associate Lecturer in NLP
	      <address>
		Melbourne Connect
	      </address>
	    </div>
		<div class="col-sm-7">
		  <a href="http://www.cis.unimelb.edu.au">Computing and Information Systems</a><br/>
		  <a href="http://www.unimelb.edu.au">The University of Melbourne</a><br/>
		  <a href="http://uom-nlp.github.io/">Natural Language Processing group</a> <br/>
		  <a href="https://cis.unimelb.edu.au/research/computer-science/research/software-engineering">Software Engineering group</a>
		</div>
	  </div>
	  <div class="row">
	    <div class="col-sm-3">
	<script type="text/javascript"><!--
	document.write('<a href="' +
	'mailto:chunhua' +
	'liu1@uni' +
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
I am a Research Fellow in NLP at The University of Melbourne, working with <a href="https://scholar.google.com/citations?user=xMne5ZUAAAAJ&hl=en"> Prof Eduard Hovy </a> on topics under the umbrella of disinformation. I'm interested in building more reliable, inclusive and collaborative AI systems that align with the diverse cultures and values of global human societies.
</p>

<p class="message">
Previously, I worked with 
<a href="https://patanamon.com/">Dr Patanamon (Pick) Thongtanunam</a> as a postdoc on empirical software engineering research, focusing on enhancing dataset quality, improving the quality of model generated review comments, and investigating LLM hallucinations in automated code review.
</p>

<p class="message">
I was awarded a PhD in Natural Language Processing under the supervision of <a href="https://people.eng.unimelb.edu.au/tcohn/">Prof Trevor Cohn</a> and <a href="https://www.frermann.de//">Dr Lea Frermann</a>. My research interests center around understanding the structure and relationships between concepts through interdisciplinary perspectives, including NLP and cognitive psychology. With a specific emphasis on understanding the structure and reasons behind human word associations, evaluating the potential of word associations as a source of commonsense knowledge and incorporating commonsense knowledge to improve neural models' reasoning ability on tasks, such as commonsense question answering and natural language inferences.  <br><br>

I'm also exploring how cultural differences shape behaviors and norms, as well as how computational models learn and understand cultural differences. This is also a long-term research agenda that I’m eager to pursue further: understanding how cultural differences shape our daily behaviours and norms, and how these can be learnt and aligned by NLP models such as large-language models.
</p>


<p class="message">
I am actively seeking academic job opportunities in the domains of NLP, software engineering, and cognitive psychology, including postdoctoral, lecturer, and research scientist positions. If you know of any available opportunities, please feel free to reach out via email (chunhua.liu1{at}unimelb.edu.au) or <a href="https://www.linkedin.com/in/chunhua-liu-977626177/">LinkedIn</a>. 
</p>

<h3>News</h3>
<ul>
{% for item in site.data.news.posts %}
  <li><i>{{ item.date }}</i>: {{ item.text }}</li>
{% endfor %}
</ul>

<h3>Recent Papers</h3>

{% for yr in (2021..2023) reversed %}
{% include publications.html year=yr %}
{% endfor %}
