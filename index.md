---
layout: page
title: 英语口语集结号！
tagline: 我们一起练口语吧！
---
{% include JB/setup %}



<ul class="posts">
  {% for post in site.posts %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><p>{{ post.content | split:'<!--more-->' |first }}</p></li>
  {% endfor %}
</ul>