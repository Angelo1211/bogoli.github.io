---
layout: page
title: portfolio
permalink: /portfolio/
---

{% for project in site.portfolio %}
<div> 
<img src="{{ project.img }}" alt="{{ project.title }}"/>
<h1><a href="{{ project.url }}">{{ project.title }}</a></h1>
<p>{{ project.description }}</p>
</div>
{% endfor %}