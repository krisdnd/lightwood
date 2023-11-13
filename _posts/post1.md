---
title: First post
date: 2023-11-13 12:00:00 -500
categories: [lightwood, dnd]
tags: [dnd,lightwood]
---

# First post
Josie to fill in ahhaa

## Images
{% raw%}{% for image in site.static_files %}
  {% if image.path contains 'assets/images/post-1' %}
    <img src="{{ image.path }}" alt="">
  {% endif %}
{% endfor %}