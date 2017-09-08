---
layout: default
title: Official Website of Sanctus Immortalis
---

<section>
  <h1>Posts</h1>
  {% for post in site.posts %}
  <b><a href="{{ post.url }}">{{ post.title }}</a></b>
  <br>{{ post.excerpt }}
  <br><a href="{{ post.url }}">Read more</a>
  {% endfor %}
</section>  
