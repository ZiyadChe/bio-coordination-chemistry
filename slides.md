---
layout: page
title: Lecture Slides
---

## Available Slides

<ul>
{% raw %}
{% assign files = site.static_files | where_exp:"file","file.path contains '/slides/'" %}
{% for file in files %}
<li>
<a href="{{ file.path }}">{{ file.name }}</a>
</li>
{% endfor %}
{% endraw %}
</ul>
