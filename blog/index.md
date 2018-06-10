---
layout: default
title: Blog
---

{% assign post = site.posts[0] %}
{% include before_post.html %}
{{ post.content }}
{% include after_post.html %}
