---
title: "PhD Journey"
layout: single
permalink: /Journey/
author_profile: true
---

Here, I keep track of my research progress.

{% for post in site.categories.journey %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p><strong>{{ post.date | date: "%B %d, %Y" }}</strong></p>
    <p>{{ post.excerpt }}</p>
  </article>
  <hr>
{% endfor %}