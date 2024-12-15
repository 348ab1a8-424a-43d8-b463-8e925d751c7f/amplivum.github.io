---
title: Blog
layout: default
nav_order: 3
---
<h1>Recent Blogs</h1>
<h2></h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>