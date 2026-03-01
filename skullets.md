---
layout: page
title: Archive
permalink: /skullets/
---

<div style="max-width:700px;margin:40px auto;">
{% for post in site.skullets reversed %}
  <p style="margin:20px 0;">
    <a href="{{ post.url }}" style="font-size:18px;text-decoration:none;">
      {{ post.title }}
    </a>
  </p>
{% endfor %}
</div>
