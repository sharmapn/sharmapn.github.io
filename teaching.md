---
layout: default
title: Teaching
---

I teach undergraduate and postgraduate computing students. At UCOL, my teaching includes mobile application development, cybersecurity, and data analytics. I currently teach D303 Mobile Application Development and D804 Advanced Mobile Application Solutions. Previously, at the University of Fiji, I taught courses in data science, business intelligence, artificial intelligence, penetration testing, software engineering, and data warehousing.

<h2 class="text-primary">Courses Taught</h2>
{% for item in site.data.teaching %}
  <div style="padding-bottom: 10px"> <b>{{item.course.name}}</b><br>
  <i>{{item.course.place}}</i><br>
  {{item.course.years}}</div>
{% endfor %}

In my teaching, I connect computing concepts with practical work and real-world applications. I use project coaching to help students build confidence, solve problems, and develop their independence.

Earlier courses included web development, mobile application development, data warehousing, business intelligence, and game programming. I used technologies such as Android, ASP.NET with C#, SQL Server Integration Services, SQL Server Analysis Services, and SQL Server Reporting Services. Student projects I coached included a timetable generation system, student course registration and information systems, and a mobile health application.
