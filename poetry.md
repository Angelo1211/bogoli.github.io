---
layout: page
title: poetry
permalink: /poetry/
---

{% for poem in site.poetry %}
<div> 
<img src="{{ project.img }}" alt="{{ project.title }}"/>
<h1><a href="{{ project.url }}">{{ project.title }}</a></h1>
<p>{{ project.description }}</p>
</div>
{% endfor %}