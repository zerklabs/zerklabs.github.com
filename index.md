---
layout: page
title: Zerklabs
---
{% include JB/setup %}

<h1>Posts</h1>
{% for post in site.posts %}
  <h2>{{post.date | date_to_string}} <a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}

