---
layout: page
title: reading-automated-writing
tagline: Writing about reading the writing written by automated computer scripts that I wrote.
---
{% include JB/setup %}

Elsewhere, my scripts produce automated writing. Here, I write about reading it.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
