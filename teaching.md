---
layout: default
title: Teaching
---
I have taught Software Engineering at the University of Fiji. My courses cover topics mostly related to software development and business informatics. Below is a list of courses that I have taught in my previous academic positions. <br>

<h2 class="text-primary">Courses Taught</h2>
{% for item in site.data.teaching %}
  <div style="padding-bottom: 10px"> <b>{{item.name}}</b><br>
  <i>{{item.place}}</i><br>
  {{item.years}}</div>
{% endfor %}
