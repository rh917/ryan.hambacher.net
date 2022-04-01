---
layout: post
title: "Recipes"
permalink: /recipes/
---

{% for post in site.recipes %}
  {% include archive-single.html %}
{% endfor %}