---
layout: page
title: portfolio
permalink: /portfolio/
---

{% for project in site.portfolio %}
<div class="project ">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        <img class="thumbnail" src="{{ project.img }}"/>
        <span>
            <h1>{{ project.title }}</h1>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endfor %}






