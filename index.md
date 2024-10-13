---
title: Heluca Projects Blog
---

# Welcome to the Heluca Technical Blog

Welcome to the Heluca Technical Blog! This blog is dedicated to sharing insights, tutorials, and updates my from my projects that include software development, 3D printing, machine learning, IoT, open collaboration platforms, and Linux.

# Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      Tags: {{ post.tag }}
    </li>
  {% endfor %}
</ul>