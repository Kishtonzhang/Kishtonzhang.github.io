---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

{% include base_path %}

Study notes, reading memos, and handouts. New items appear below after you push to GitHub.

## How to upload notes

| Format | Where to put files | Example URL after publish |
|--------|-------------------|---------------------------|
| **Markdown** (recommended) | `_notes/your-file.md` | `https://kishtonzhang.github.io/notes/your-file/` |
| **PDF / slides** | `files/notes/your-file.pdf` | `https://kishtonzhang.github.io/files/notes/your-file.pdf` |

**Steps:** open [the repository](https://github.com/Kishtonzhang/Kishtonzhang.github.io) → **Add file** → **Upload files** (or create new file) → commit to `master` → wait 1–3 minutes for the site to rebuild.

Markdown note template (front matter required):

```yaml
---
title: "Microeconomics — Consumer Theory"
date: 2026-06-01
categories: [economics, micro]
tags: [UG, notes]
---
Your content here…
```

## All notes

{% for post in site.notes %}
  {% include archive-single.html %}
{% endfor %}

## PDF & other files

Upload PDFs to [`files/notes/`](https://github.com/Kishtonzhang/Kishtonzhang.github.io/tree/master/files/notes) and link them like: `[Chapter 3](/files/notes/chapter3.pdf)`.
