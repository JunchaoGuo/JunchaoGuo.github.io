---
layout: default
title: "Junchao Guo's cyber garden"
---

Welcome to my personal website!

Here are my notes and journals.

- [About me]({{ "/about/" | relative_url }})
- [ categories ]({{ "/categories/" | relative_url }})

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
