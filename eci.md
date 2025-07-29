---
layout: page
title: Análisis Probilístico de Algoritmos
permalink: /eci-25/
---

# Curso Análisis Probilístico de Algoritmos ECI 2025

Listado de archivos disponibles para descarga:

<ul>
  {% for archivo in site.static_files %}
    {% if archivo.path contains '/files/curso-eci-25' %}
      <li>
        <a href="{{ archivo.path | relative_url }}">{{ archivo.name }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

