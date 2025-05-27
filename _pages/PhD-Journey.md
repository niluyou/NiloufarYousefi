---
title: "PhD Journey"
layout: single
permalink: /Journey/
author_profile: true
---

Here, I keep track of my research progress.

{% for post in site.categories.journey %}
- <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
