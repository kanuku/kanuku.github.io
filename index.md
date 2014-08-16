---
layout: page
title: Welcome
tagline: First draft
---
{% include JB/setup %}


This blog was started on the 10 of August 2014.  
In this blog some aspects and best practices on software development will  
be shared with you.

The most interesting topics will be go about:  

  * Programming articles in Java or Scala.
  * Developing tips
  * Tools/Tips to help you the best out of a Mac OS/X system.

hallo  
hoi

#### Previous blogs:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
