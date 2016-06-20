---
title: "Projects"
layout: archive
excerpt: "What I'm working on"
sitemap: false
permalink: /projects/
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
