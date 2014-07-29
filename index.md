---
layout: page
title: Peter Burkholder
tagline: WIP
---
{% include JB/setup %}

## Posts

### I'm not here right now, please see [old site](http://www.pburkholder.com/) 

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


