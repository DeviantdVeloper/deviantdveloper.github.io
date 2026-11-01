---
layout: default
title: Projects.html
---

Here is a list of all my projects, be they games, programs, plugins, or something else.

<ul>
{% for project in site.projects %}
						<li><a href="{{ project.url }}" title="{{ project.title }}"><img src="{{ project.icon }}" title="{{ project.title }}" width="32" height="32"/>{{ project.title }} - {{project.desc}}</a></li>
{% endfor %}
</ul>