---
title: "Dame's Picks"
layout: "post"
author: "Madame Simsbury"
date: 2025-10-18
---

Enjoy some of my favorite submissions for good reading! --Madame Simsbury  

<style>
.thumb-list { display: grid; gap: 1rem; }
.thumb { display: flex; gap: .9rem; align-items: flex-start; }
.thumb img { width: 96px; height: 96px; object-fit: cover; border-radius: 6px; }
.thumb h4 { margin: 0 0 .2rem; font-size: 1rem; }
.thumb p { margin: 0; color: #444; }
@media (max-width: 520px) { .thumb img { width: 72px; height: 72px; } }
</style>

{% assign items = site.data.picks['2025-10-18'] %}
<div class="thumb-list">
  {% for t in items %}
  <div class="thumb">
    <a href="{{ t.url }}"><img src="{{ t.img | relative_url }}" alt="{{ t.title }}"></a>
    <div>
      <h4><a href="{{ t.url }}">{{ t.title }}</a></h4>
      <p>{{ t.blurb }}</p>
    </div>
  </div>
  {% endfor %}
</div>
