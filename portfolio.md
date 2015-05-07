---
layout: page
title: portfolio
permalink: /portfolio/
---


  {% for project in site.portfolio %}
      <div class="project entry">
      	<h1><a href="{{ site.baseurl }}{{ project.url }}">{{ project.title }}</a></h1>
      	<p>{{ project.description }}</p>
<!--         {{ project.content | truncatewords:40}}
 -->  </div>


  {% endfor %}











<!-- 
<div class="clearfix"> 
{% for project in site.portfolio %}

	<img src="{{ project.img }}" alt="{{ project.title }}"/>
	<h1><a href="{{ project.url }}">{{ project.title }}</a></h1>
	<p>{{ project.description }}</p>

{% endfor %}
</div>


<div class="grid-container">
	
    <div class="row">
        <div class="col-1">
        	{% for project in site.portfolio %}
    		{% if project.col == "skinny" %}
    		skinny
    		{% endif %}
    		{% endfor %}
        </div> 
        <div class="col-2">
        	{% for project in site.portfolio %}
    		{% if project.col == "wide" %}
    			wide
    			{% endif %}
    		{% endfor %}
        </div> 
    </div> 
    <!-- 
    <div class="row">
        <div class="col-3">
        	<p>
        		col-3
        	</p>
        </div> 
    </div> 

</div>
-->








