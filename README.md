# Bio-coordination-chemistry
CHE5EJ303 course website
M. Ziyad  
Department of Chemistry  
Farook College

---
## Latest Updates

<ul>
{% raw %}
{% for post in site.announcements reversed limit:5 %}
<li>
<strong>{{ post.date | date: "%b %d" }}</strong> –
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
{% endraw %}
</ul>
---

## Course Materials

- [Course Schedule](schedule.md)
- [Assignments](assignments.md)
- [Resources](resources.md)
