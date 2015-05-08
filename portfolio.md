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
<<<<<<< HEAD
<<<<<<< HEAD
            <br/>
=======
>>>>>>> 5555a4258404ffe98e5c78a2a4055ec9125dca63
=======
>>>>>>> 5555a4258404ffe98e5c78a2a4055ec9125dca63
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>

{% endfor %}






