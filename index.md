---
layout: page
title: Home
---
# Bio-coordination-chemistry
CHE5EJ303 course website

**Instructor:** M. Ziyad  
Department of Chemistry  
Farook College

---
## Latest Updates

<ul>
{% for post in site.announcements reversed limit:5 %}
<li>
<strong>{{ post.date | date: "%b %d" }}</strong> –
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
---

## Course Materials

- [Course Schedule](schedule.md)
- [Assignments](assignments.md)
- [Resources](resources.md)
- Quiz
