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
I am a Postdoctoral Research Fellow at The University of Melbourne. Currently, I'm working with 
<a href="https://patanamon.com/">Dr Patanamon (Pick) Thongtanunam </a> on empirical software engineering research, focusing on automated code review. My current work emphasizes the importance of high-quality datasets and challenges such as hallucinations to ensure the reliability and trustworthiness of machine learning systems in software engineering.
</p>

<p class="message">
I was awarded a PhD in Natural Language Processing under the supervision of <a href="https://people.eng.unimelb.edu.au/tcohn/">Trevor Cohn</a> and <a href="https://www.frermann.de//">Lea Frermann</a>. My research interests center around understanding the structure and relationships between concepts through interdisciplinary perspectives, including NLP and cognitive psychology. With a specific emphasis on understanding the structure and reasons behind human word associations, evaluating the potential of word associations as a source of commonsense knowledge and incorporating commonsense knowledge to improve neural models' reasoning ability on tasks, such as commonsense question answering and natural language inferences.  </br>

This naturally evolved into an exploration of how these concept networks vary across languages and cultures. As my research progressed, I became increasingly intrigued by how computational models learn and understand these cultural differences. This sparked a long-term research agenda that I’m eager to pursue further: exploring how cultural differences shape our daily behaviours and norms, and how these can be learnt and aligned by NLP models such as large-language models. This work will contribute to the long-term goal of building more inclusive and collaborative AI systems that align with the diverse cultures and values of global human societies.
</p>


<p class="message">
I am actively seeking job opportunities in the domains of NLP, software engineering, and cognitive psychology, including postdoctoral, lecturer, and research scientist positions. If you know of any available opportunities, please feel free to reach out via email (chunhua.liu1{at}unimelb.edu.au) or <a href="https://www.linkedin.com/in/chunhua-liu-977626177/">LinkedIn</a>. 
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
