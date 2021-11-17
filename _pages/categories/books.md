---
title: "books"
layout: archive
permalink: /categories/books/
author_profile: true
---

{% assign posts = site.categories.books %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}