---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%m/%d/%Y" }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

