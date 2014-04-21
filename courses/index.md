---
layout: page
title: Courses
tagline: 
group: navigation
---
{% include JB/setup %}

<h2>For CU Students</h2>
<p>CU offers many courses teaching knowledge and skills essential for Big Data research:</p>
<ul>
{% for course in site.data.courses %}
  <li>
    {{ course.dept }} {{ course.number }} - {{ course.title }}
  </li>
{% endfor %}
</ul>

<h2>For Industry</h2>
<p>The Department of Computer Science is planning to offer week-long intensive training courses on Big Data.</p>