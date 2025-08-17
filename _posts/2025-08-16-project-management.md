---
laytou: default
title: "Project Management"
---

<!--# Project Management-->

This section contains posts about project management, workflows and tools.
<ul>
  {% for posts in site.categories.project-management %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%B %-d, %Y" }}
    </li>
  {% endfor %}
</ul>
