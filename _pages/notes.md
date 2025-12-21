---
layout: archive
title: "Notes"
permalink: /notes/
author_profile: true
---

{% include base_path %}

This is a collection of my notes.

{% for post in site.notes %}
  {% include archive-single.html %}
{% endfor %}
