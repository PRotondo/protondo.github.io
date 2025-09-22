---
layout: page
title: Analysis of Algorithms MPRI
permalink: /algo-mpri-25/
---

# Analysis of Algorithms MPRI 2.15. 2025-2026

Here is the material for the first part of the course (first 4 lectures).
The official website is <a href="https://mpri-master.ens.fr/doku.php?id=cours:aofa">here</a>

List of files available for download:

<ul>
  {% for archivo in site.static_files %}
    {% if archivo.path contains '/files/course-mpri-25' %}
      <li>
        <a href="{{ archivo.path | relative_url }}">{{ archivo.name }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

