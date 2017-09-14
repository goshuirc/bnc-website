---
layout: wrapped-default
title: goshubnc news
---

# News

{% for post in site.posts %}
<div class="post box">
    <h3>{{ post.title }}</h3>
    <span class="postinfo">{{ post.author }} - {{ post.date | date_to_string }}</span>
    {{ post.content }}
</div>
{% endfor %}
