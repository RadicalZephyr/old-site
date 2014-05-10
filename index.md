---
title: Hi There!
layout: main
---

Check out my [github song](http://song-of-github.herokuapp.com/?username=radicalzephyr).

Please forgive the spartan nature of this space. It's currently very
much a work-in-progress.

Posts
-----

<ul>
  {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }} - {{ post.date | date_to_string }}</a>
    </li>
  {% endfor %}
</ul>
