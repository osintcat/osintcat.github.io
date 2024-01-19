---
layout: page
title: "OSINT.CAT Website"
permalink: /
---
Welcome 

![OSINTCAT Logo](assets/images/osintcat-logo.png)

## Recent Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
