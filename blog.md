---
title: "Blog"
permalink: /blog/
author_profile: true
---

# Blog

This is where I publish academic blog posts, daily notes, monthly reflections, and personal thoughts about medical physics, research, learning, and scientific writing.

## Types of Posts

- Daily academic notes
- Monthly reflections
- Learning progress
- Research reflections
- Scientific writing practice
- Thoughts on medical physics education

## Posts

{% for post in site.categories.Blog %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
