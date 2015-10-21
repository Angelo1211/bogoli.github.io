---
layout: page
title: portfolio
permalink: /portfolio/
---

Click on a project for description and more photos. Print and online resume at the end. 

<p><b>html + css</b> : including themes for Jekyll and other web based projects.</p>
{% for project in site.portfolio %}
{% if project.cat == "web" %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% endif %}
{% endfor %}

<div class="clearfix"></div>
<br/>
<hr/>
<br/>

<p><b>architecture</b> : projects completed for studio and computational architecture classes.</p>
{% for project in site.portfolio %}
{% if project.cat == "arch" %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% endif %}
{% endfor %}


<div class="clearfix"></div>
<br/>
<hr/>
<br/>

<p><b>resume</b> : cumulative list of work experience, skills, and education.</p>
{% for project in site.portfolio %}
{% if project.cat == "resume" %}
<div class="project">
    <div class="thumbnail">
        <a href="{{ site.baseurl }}{{ project.url }}">
        {% if project.img %}
        <img class="thumbnail" src="{{ project.img }}"/>
        {% else %}
        <div class="thumbnail blankbox"></div>
        {% endif %}    
        <span>
            <h1>{{ project.title }}</h1>
            <br/>
            <p>{{ project.description }}</p>
        </span>
        </a>
    </div>
</div>
{% endif %}
{% endfor %}