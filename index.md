---
layout: page
title: danny316p.github.io
tagline: 
---
{% include JB/setup %}

This is a simple placeholder page.



### Blog posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


