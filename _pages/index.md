---
layout: page
title: Home
id: home
permalink: /
---

# What is all about

<img src="{{ site.baseurl }}/assets/cat_attack.webp" alt="Cat" style="width: 30%; display: block; margin-left: 0; margin-right: auto;">

This place is dedicated to practical learnings of Wing Chun. 

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>


