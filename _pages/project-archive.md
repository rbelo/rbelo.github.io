---
title: ""
permalink: /projects/
author_profile: true
---

# Software

<ul>
  {% for post in site.categories.software %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
