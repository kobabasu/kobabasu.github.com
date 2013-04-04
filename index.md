---
layout: page
title: kobalog
---
{% include JB/setup %}

<div id="posts">
  {% for post in site.posts %}
    <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><br />
  {% endfor %}
</div>
