---
layout: page
title: Welcome
tagline: First draft
---
{% include JB/setup %}


 I started this blog on the 10 of August 2014.

 In this blog I hope to share some aspects and practices I have experience during my career as a Developer.

 This are for me the most interesting topics I would like to wirte about on this blog:
  Programming articles in Java or Scala.
  Developing tips
  Tools and tips that helped me get the best out of a Mac OS/X system.

Welcome, in this blog I hope to share with you ddI just released my first block article.


#### Previous blogs:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
