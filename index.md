---
layout: page
title: Free and Open Source Software
---
{% include JB/setup %}

## Projects
Fork and check out my projects:

[Github Cheat-Sheet](https://github.com/Treehopper/Git-Cheat-Sheet)

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
