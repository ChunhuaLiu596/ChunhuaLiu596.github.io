---
layout: page
title: "Publications"
---

You can also find my articles on <a href="{{site.gscholar}}">my Google Scholar profile</a> or <a  href="{{ site.dblp }}"> my DBLP profile</a>. Code links are provided below, see also <a  href="{{ site.github }}">my GitHub page</a>.


{% assign currentYear = "now" | date: "%Y" | plus: 0 %}
{% assign startYear = 2014 %}

{% for year in (startYear..currentYear) reversed %}

## }

  {% include publications.html year=year %}
{% endfor %}
