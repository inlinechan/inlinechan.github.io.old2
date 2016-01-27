---
layout: page
title: Code Snippets
tagline: I learned
---
{% include JB/setup %}

I'll post some code snippets I've learned.

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

