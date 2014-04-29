---
title: Posts
layout: main
---

Link to SICP [Lecture 01](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/1a-overview-and-introduction-to-lisp/).

<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }} - {{ post.date | date_to_string }}</a>
    </li>
  {% endfor %}
</ul>
