---
title: "Projects"
permalink: /projects/
author_profile: true
---
<ul>
  {% for post in site.categories.project %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
