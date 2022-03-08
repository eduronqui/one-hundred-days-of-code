---
layout: page
title: Tutorials
permalink: /tutorials/
---

{% if site.tutorials == empty %}
  <p>No tutorials have been published so far</p>
{% else %}
{% for tutorial in site.tutorials %}
  <h3>
    <a href="{{ tutorial.url }}">
      {{ tutorial.title }}
    </a>
  </h3>
{% endfor %}
{% endif %}
