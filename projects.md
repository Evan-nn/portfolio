---
layout: page
title: Projets
permalink: /projects/
---

Voici une sélection de mes projets académiques et personnels.

<ul>
  {% for project in site.projects %}
    <li>
      <strong>{{ project.title }}</strong><br>
      {{ project.excerpt }}<br>
      <a href="{{ project.url | relative_url }}">
        Voir le projet →
      </a>
    </li>
  {% endfor %}
</ul>