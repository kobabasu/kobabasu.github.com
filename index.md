---
layout: page
title: kobalog
tagline: 10分後の打ち合わせの前に…
---
{% include JB/setup %}

<div id="posts">
  {% for post in site.posts %}
    <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><br />
  {% endfor %}
</div>
