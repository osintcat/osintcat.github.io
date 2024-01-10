---
layout: page
title: Blog
permalink: /blog/
---
## Blog

Find here all the blog posts shared in our website
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>