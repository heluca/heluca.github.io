---
title: Heluca Projects Blog
---

Welcome to the Heluca Technical Blog! This blog is dedicated to sharing insights, tutorials, and updates my from my projects that include software development, 3D printing, machine learning, IoT, open collaboration platforms, and Linux.

# Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
      Tags: {{ post.tag }}
      <br>
    </li>
  {% endfor %}
</ul>

# Blog Posts by Tag

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

