---
layout: page
title: "Recipes"
permalink: /recipes/
---


<div id="home">
  <h1>Recipes</h1>
  <ul class="posts">
    {% for post in site.recipes %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>