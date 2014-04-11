---
layout: page
title: Welcome to ...
tagline: 
---
{% include JB/setup %}

### Manfreds notes, statements, whys and wherefores, ideas, news, announcements, this and that, ...
  
Here's a list of posts so far:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

