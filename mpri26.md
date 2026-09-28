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


Previous years: <a href="/algo-mpri-25/">2025</a>


Online resources: 
<ul>
<li>
<a href="https://algo.inria.fr/flajolet/Publications/book.pdf">Analytic Combinatorics</a> by P. Flajolet and R. Sedgewick.
</li>
<li>
<a href="https://www2.math.upenn.edu/~wilf/gfology2.pdf">Generatingfunctionology</a> by H. Wilf.
</li>
<li>
<a href="https://arxiv.org/pdf/2305.17576">Lagrange Inversion Formula by Induction</a> by E Surya and L Warnke.
</li>
</ul>
