---
layout: page
title: Blog
description: Stay up to date with projects
nav-menu: true
image: assets/images/pic09.jpg
---
{% for page in site.pages %}
	{% if page.layout == "post" %}
		<li><a href="{{ "" | absolute_url }}/">{{ page.title }}</a></li>
	{% endif %}
{% endfor %}