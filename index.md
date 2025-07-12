---
title: Welcome
layout: default
description: Learn how to save your code (and your sanity) with Git and GitHub.
---

# Welcome to Save Your Code

![Illustration of saving your code](/assets/images/saveyourcode.png)

This site teaches you how to save your code (and your sanity) with Git and GitHub.

## Recent Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%d %B %Y" }}</small>
    </li>
  {% endfor %}
</ul>

