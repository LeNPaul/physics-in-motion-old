---
layout: page
title: Curriculum
permalink: /pages/curriculum/
---

<h3 class="page-heading">Kinematics</h3>

<ul class="post-list">
  {% for post in site.categories.Kinematics %}
    <li>
      <h1>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h1>
    </li>
  {% endfor %}
</ul>

<h3 class="page-heading">Forces</h3>

<ul class="post-list">
  {% for post in site.categories.Forces %}
    <li>
      <h1>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h1>
    </li>
  {% endfor %}
</ul>

<h3 class="page-heading">Energy</h3>

<ul class="post-list">
  {% for post in site.categories.Energy %}
    <li>
      <h1>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h1>
    </li>
  {% endfor %}
</ul>

<h3 class="page-heading">Momentum</h3>

<ul class="post-list">
  {% for post in site.categories.Momentum %}
    <li>
      <h1>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h1>
    </li>
  {% endfor %}
</ul>

<h3 class="page-heading">Simple Harmonic Motion</h3>

<ul class="post-list">
  {% for post in site.categories.Simple-Harmonic-Motion %}
    <li>
      <h1>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h1>
    </li>
  {% endfor %}
</ul>

<h3 class="page-heading">Waves</h3>

<ul class="post-list">
  {% for post in site.categories.Waves %}
    <li>
      <h1>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h1>
    </li>
  {% endfor %}
</ul>
