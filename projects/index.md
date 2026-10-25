---
layout: default
title: Projects.html
---

I will put all my projects here eventually.

<ul>
{% for project in site.projects %}
						<li><a href="{{ project.url }}" title="{{ project.title }}"><img src="{{ project.icon }}" title="{{ project.title }}" />{{ project.title }} - {{project.desc}}</a></li>
{% endfor %}
</ul>