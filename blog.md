---
layout: splash
title: Community
permalink: /blog/
---

# We love our Community! 
## Here's some of our awesome member's and their awesome day!

<li>
  {% for post in site.data.posts %}
    <a href="{{ post.url }}" target="_blank">{{ post.title }}</a>
    <p>From {{ post.author }} on {{ post.date }}.</p>
  {% endfor %}
</li>
