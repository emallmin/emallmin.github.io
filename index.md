---
layout: post
title: "Welcome"
---

Welcome to my whisky blog.

<h2>Posts</h2>
<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
