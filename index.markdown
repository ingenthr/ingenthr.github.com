---
layout: default
title: NorthScale
---

High performance, web scale-out consulting, support and training.

Memcached.  Beanstalkd.  Web Infrastructure.

Scale-out done right.

<div id="home">
  <h1>Blog</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date: "%Y/%m/%d" }}</span> &raquo;
          <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>
  
