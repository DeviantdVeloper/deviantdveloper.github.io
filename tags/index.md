---
layout: default
title: Tags.html
permalink: /tags/
---

hello guvna

<ul>
{% assign tags = site.tags | sort %}
{% for tag in tags %}
    <li><a href="/tag/{{ tag | first | slugify }}/" title="{{ tag[0] | replace:'-', ' ' }}"><img src="/assets/img/folder.ico" />{{ tag[0] | replace:'-', ' ' }}</a></li>
{% endfor %}
</ul>