---
layout: page
title: Welcome
tagline: First draft
---
{% include JB/setup %}

Hello world and Welcome!!

#### Previous blogs:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
