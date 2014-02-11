---
layout: page
title: 一起练口语吧！
tagline: 
---
{% include JB/setup %}



<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><p>{{ post.content | split:'<!--more-->' |first }}</p></li>
  {% endfor %}
</ul>