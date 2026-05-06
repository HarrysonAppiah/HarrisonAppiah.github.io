---
layout: default
title: "Blog"
permalink: /blog/
---

<h2>Blog Posts</h2>

{% for post in site.posts %}
  <div style="margin-bottom: 20px;">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  </div>
{% endfor %}
