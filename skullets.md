---
layout: page
title: Comics
permalink: /skullets/
---

{% for post in site.skullets reversed %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% endfor %}
