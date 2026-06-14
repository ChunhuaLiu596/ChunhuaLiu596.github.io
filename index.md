---
layout: page
---
<div class="row">
    <div class="col-sm-3">
      <img src="{{ site.baseurl }}public/blcu16.JPG" alt="Photo of Chunhua" style="margin-bottom:10px;">
      <div style="font-size:0.9em; line-height:2;">
        <script type="text/javascript"><!--
        document.write('<a href="' +
        'mailto:chunhua' +
        'liu1@uni' +
        'melb.edu' +
        '.au">' +
        '<span class="glyphicon glyphicon-envelope"></span> Email</a>');
        //-->
        </script>
        <noscript><IMG alt="E-mail" border=0 src="./email.png"></noscript>
        <br>
        <a href="https://www.linkedin.com/in/chunhua-liu-977626177/">LinkedIn</a><br>
        <a href="https://scholar.google.com/citations?user=IvOlenIAAAAJ&hl=en">Google Scholar</a>
      </div>
    </div>
    <div class="col-sm-9">
	  <div class="row">
	    <div class="col-sm-12">
	      <b>Chunhua Liu</b> <span style="font-size:0.85em; color:#888;">(刘春花 &middot; <i>chūn</i> 春=spring, <i>huā</i> 花=flower)</span>
	      <br>Postdoc Research Fellow and Associate Lecturer in NLP
	      <address>
		Melbourne Connect
	      </address>
	    </div>
	  </div>
	  <div class="row">
		<div class="col-sm-12">
		  <a href="http://www.cis.unimelb.edu.au">Computing and Information Systems</a><br/>
		  <a href="http://www.unimelb.edu.au">The University of Melbourne</a><br/>
		  <a href="http://uom-nlp.github.io/">Natural Language Processing group</a> <br/>
		  <a href="https://cis.unimelb.edu.au/research/computer-science/research/software-engineering">Software Engineering group</a>
		</div>
	  </div>
	</div>
    </div>

<p class="message">
I am a Postdoctoral Research Fellow and Associate Lecturer in NLP at The University of Melbourne, working with <a href="https://scholar.google.com/citations?user=xMne5ZUAAAAJ&hl=en">Prof Eduard Hovy</a> and <a href="https://www.frermann.de/">Dr Lea Frermann</a> on cultural and value alignment in language models. My research develops human-centred NLP systems that reliably adapt to the diverse meanings, values, and behaviours of people across cultures and societies.
</p>

<div class="message">
My work spans three interconnected themes:
<ul>
  <li><b>Cultural alignment of language models</b> — grounding LLMs in diverse cultural and moral values
    (<a href="https://aclanthology.org/2025.acl-long.177/">ACL 2025</a>,
     <a href="https://www.arxiv.org/pdf/2508.13426">ACL 2026</a>)</li>
  <li><b>Understanding diversity in human meaning</b> — studying how word meanings and semantic associations vary across cultures using cognitive psychology methods
    (<a href="https://aclanthology.org/2022.aacl-main.9">WAX</a>,
     CogSci 2026)</li>
  <li><b>Human–AI communication and persuasion</b> — examining how LLMs adapt to people and how that power can be misused or steered</li>
  <li><b>NLP for software engineering</b> — trustworthy automated code review
    (<a href="https://www.computer.org/csdl/proceedings-article/msr/2025/018300a236/27vTsGKcCvC">MSR 2025</a>,
     <a href="https://aclanthology.org/2025.findings-acl.476.pdf">ACL Findings 2025</a>,
     <a href="https://dl.acm.org/doi/10.1145/3762183">TOSEM 2025</a>)</li>
</ul>
</div>

<p class="message">
Previously, I spent a year as a postdoc with <a href="https://patanamon.com/">A/Prof Patanamon Thongtanunam</a> on empirical software engineering, focusing on automated code review. I was also very fortunate to complete my PhD under <a href="https://people.eng.unimelb.edu.au/tcohn/">Prof Trevor Cohn</a> and <a href="https://www.frermann.de/">Dr Lea Frermann</a> on commonsense reasoning via human word associations (see my <a href="https://findanexpert.unimelb.edu.au/scholarlywork/1875104-word-associations-as-a-source-of-commonsense-knowledge?cache=1759739545311">PhD thesis</a>). Much of my work bridges cognitive science and NLP, grounded in the <a href="https://smallworldofwords.org/en/project">Small World of Words</a> project in collaboration with <a href="https://scholar.google.com/citations?user=33TqQu8AAAAJ&hl=en">Simon De Deyne</a>. Before this, I completed my undergraduate and master's degrees with <a href="https://scholar.google.com/citations?user=oW2lr0kAAAAJ&hl=zh-CN">Prof Dong Yu</a> at BLCU, where my NLP research began.
</p>

<p class="message">
I am actively seeking academic positions (lecturer, senior lecturer, research scientist) in NLP and related areas. Feel free to reach out via email (chunhua.liu1{at}unimelb.edu.au) or <a href="https://www.linkedin.com/in/chunhua-liu-977626177/">LinkedIn</a>.
</p>

<h3>News</h3>
<ul>
{% for item in site.data.news.posts %}
  <li><i>{{ item.date }}</i>: {{ item.text }}</li>
{% endfor %}
</ul>
