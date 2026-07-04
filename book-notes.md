---
title: "Book Notes"
permalink: /book-notes/
author_profile: true
---

# Book Notes

In this section, I share notes and summaries from scientific and academic books.

Possible topics include:

- Medical physics textbooks
- Radiation physics
- Dosimetry
- Medical imaging
- Radiobiology
- Research methodology
- Scientific writing
- Biostatistics

## Posts

{% for post in site.categories.Book-Notes %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
