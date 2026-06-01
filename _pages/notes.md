---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

{% include base_path %}

Study notes, reading memos, and handouts.

## Waseda University — Microeconomics I (Spring 2026)

*Course notes from **Microeconomics I**, taken in **Spring 2026** at **Waseda University** (Graduate School of Economics).*

| File | Description |
|------|-------------|
| [Microeconomics_I_2026.pdf](/files/notes/Microeconomics_I_2026.pdf) | Course materials written by **Prof. Hisatoshi Tanaka** ([Waseda researcher profile](https://w-rdb.waseda.jp/html/100000609_ja.html)). |
| [Waseda_GSE_MICRO_1.pdf](/files/notes/Waseda_GSE_MICRO_1.pdf) | My own lecture notes compiled from class. |

I am deeply grateful to **Prof. Tanaka** for his teaching this semester; I learned a great deal from his lectures on microeconomic theory and related mathematics.

---

## How to upload notes

| Format | Where to put files | Example URL after publish |
|--------|-------------------|---------------------------|
| **Markdown** (recommended) | `_notes/your-file.md` | `https://kishtonzhang.github.io/notes/your-file/` |
| **PDF / slides** | `files/notes/your-file.pdf` | `https://kishtonzhang.github.io/files/notes/your-file.pdf` |

**Steps:** open [the repository](https://github.com/Kishtonzhang/Kishtonzhang.github.io) → **Add file** → **Upload files** → commit to `master` → wait 1–3 minutes for the site to rebuild.

## All notes (Markdown)

{% for post in site.notes %}
  {% include archive-single.html %}
{% endfor %}
