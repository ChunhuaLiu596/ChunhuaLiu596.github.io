---
layout: page
title: "Teaching"
---

{% for yr in (2021..2026) reversed %}
{% assign has_teaching = false %}
{% for subject in site.data.teaching.subjects %}
  {% assign syear = subject.year | plus: 0 %}
  {% if syear == yr %}
    {% assign has_teaching = true %}
  {% endif %}
{% endfor %}
{% if has_teaching %}
## {{yr}}
{% include teaching.html year=yr %}
{% endif %}
{% endfor %}
