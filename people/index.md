---
layout: page
title: People
tagline: 
group: navigation
---
{% include JB/setup %}

<h2>Investigators</h2>
<ul>
{% for investigator in site.data.investigators %}
  <li>
    {{ investigator.name }}, {{ investigator.dept }}
  </li>
{% endfor %}
</ul>

<h2>Students</h2>
<ul>
{% for student in site.data.students %}
  <li>
    {{ student.name }}, {{ student.dept }}
  </li>
{% endfor %}
</ul>