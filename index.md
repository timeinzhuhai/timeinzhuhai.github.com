---
layout: page
title: 活动信息
tagline: 
---
{% include JB/setup %}



<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><p>{{ post.content | split:'<!--more-->' |first }}</p></li>
  {% endfor %}
</ul>