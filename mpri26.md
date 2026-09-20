---
layout: page
title: Analysis of Algorithms MPRI 2026
permalink: /algo-mpri-26/
---

# Analysis of Algorithms MPRI 2.15. 2026-2027

Here is the material for the first part of the course (first 4 lectures).
The official website is <a href="https://mpri-master.ens.fr/doku.php?id=cours:aofa">here</a>

List of files available for download:

<ul>
  {% for archivo in site.static_files %}
    {% if archivo.path contains '/files/course-mpri-26' %}
      <li>
        <a href="{{ archivo.path | relative_url }}">{{ archivo.name }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>


Previous yers: <a href="/algo-mpri-25/">2025</a>
