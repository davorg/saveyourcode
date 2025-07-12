---
title: Welcome
layout: default
description: Learn how to save your code (and your sanity) with Git and GitHub.
---

# Welcome to Save Your Code

![Illustration of saving your code](/assets/images/saveyourcode.png)

Whether you’re copy-pasting AI-generated code, experimenting with new ideas,
or just vibe-coding your way through a weekend project — this site will help
you keep your progress safe, your experiments recoverable, and your projects
shareable.

We focus on using version control tools like Git and cloud platforms like
GitHub, explained for coders who are learning on the fly (often with a little
help from ChatGPT, Claude, or Copilot).

No jargon. No gatekeeping. Just practical advice to help you save your code —
and your sanity.

## Recent Posts

<ul class="post-list">
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%d %B %Y" }}</small>
    </li>
  {% endfor %}
</ul>

