---
title: ""
permalink: /projects/
author_profile: true
---
# Projects

<ul>
  {% for post in site.categories.research-projects %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>


# Software

<ul>
  {% for post in site.categories.software %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
