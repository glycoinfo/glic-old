---
layout: default
title: Wish List
redirect_from: /blog.html
---

Ask for specific tools you need developed here.
{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.url }}{{ post.url }})
{% endfor %}

Subscribe to the [RSS feed](/rss.xml) for new blog posts.
