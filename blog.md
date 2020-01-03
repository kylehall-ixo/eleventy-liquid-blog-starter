---
layout: layouts/basicLayout.html
title: Posts
---

# {{ title }}

{% for post in collection.post %}
{{ post.data.title }}
{% endfor %}
