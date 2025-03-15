---
title: "project"
layout: archive
permalink: /project
author_profile: true
sidebar:
    nav: "sidebar-category"
---
{% assign posts = site.categories.human %}
{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
