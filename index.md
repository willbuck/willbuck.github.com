---
layout: page
title: Wills Tech Project Blog
tagline: Getting a start on writing and projects
---
{% include JB/setup %}

## Wills Tech Blog

Here is where I'll be putting my thoughts on how to improve my tech career!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
