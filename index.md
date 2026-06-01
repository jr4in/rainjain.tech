---
layout: default
title: Home
---
## Here are some of my latest posts

{% for post in site.posts %}
 - [{{ post.title }}]({{ post.url }})
  {% endfor %}
