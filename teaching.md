---
layout: page
title: "Teaching"
---

<!-- I coordinate the <a href="https://study.unimelb.edu.au/find/courses/graduate/master-of-data-science/">Master of Data Science</a> degree, alongside <a href="https://findanexpert.unimelb.edu.au/display/person600991">Howard Bondell</a>. -->

{% for yr in (2021..2024) reversed %}
## {{yr}}
{% include teaching.html year=yr %}
{% endfor %}

