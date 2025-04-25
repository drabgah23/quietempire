---
layout: default
title: Quiet Empire Journal
---

Welcome to the Quiet Empire.  
A silent log of edge, code, and conviction.

## Latest Logs

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>
