---
layout: page
title: design
permalink: /design/
---

{% for project in site.design %}
<div> 
	<!--<img src="{{ project.img }}" alt="{{ project.title }}"/> -->
<h1><a href="{{ project.url }}">{{ project.title }}</a></h1>
<p>{{ project.description }}</p>
</div>
{% endfor %}