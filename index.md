---
layout: default
title: Trading Journal
---

# Henry Regan-Elson Trading Journal

## Trading Logs

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    — {{ post.date | date: "%d %B %Y" }}
  </li>
{% endfor %}
</ul>
