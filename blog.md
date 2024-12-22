---
title: Blog
layout: default
nav_order: 2
permalink: /blog/
---
<h1><b><b>/RECENT_BLOGS/</b></b></h1>
<br>
<ul>
  {% for post in site.posts %}
    <li>
      <b><small>{{ post.date | date: "%B %d, %Y" }} - </small></b>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>