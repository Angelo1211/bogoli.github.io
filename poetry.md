---
layout: page
title: poetry
permalink: /poetry/
description: in reverse chronological order, dating back to 2002. 
---

<ul class="post-list">
{% for poem in site.poetry %}
    <li>
        <h2><a class="post-title" href="{{ poem.url | prepend: site.baseurl }}">{{ poem.title }}</a></h2>
        <p class="post-meta">{{ poem.date | date: '%B %-d, %Y — %H:%M' }}</p>
        <br/>
        <hr/>
      </li>
{% endfor %}
</ul>