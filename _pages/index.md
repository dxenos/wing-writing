---
layout: page
title: Home
id: home
permalink: /
---

# What is this eternal Wing Chun space?

<img src="{{ site.baseurl }}/assets/cat_attack.webp" alt="Cat" style="width: 30%; display: block; margin-left: 0; margin-right: auto;">

"Recently there have been people getting on in the world as strategists but they are usually sword-fencers..." - Musashi Yamamoto 1645

Wing Chun is heavily misunderstood. I see all these opportunistic “sifus” trying to commercialise this beautiful art, and I feel extremely frustrated. I see online videos demonstrating how Wing Chun should “work” with explanations that do not make sense – you just need some common sense to understand the flaws in their demos and their explanations.

I feel the responsibility to share my knowledge and understanding about this remarkable martial art. This space will present my explanations about Wing Chun, and I will share my findings and my analysis. I want to grow my ideas and share my progress in public.

My vision is to understand if there is an ultimate martial art based on the principles of Wing Chun that could be eternal... there is no end so it will keep evolving.

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


