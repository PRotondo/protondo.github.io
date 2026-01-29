---
layout: page
title: Pablo Rotondo - teaching
permalink: /teaching/
---
<link rel="stylesheet" href="/assets/css/teaching.css">
<link rel="stylesheet"
 href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<h1>Teaching</h1>

<div class="teaching-header">
  <p class="teaching-intro"> I am a Maître de Conférences (Associate Professor) in Informatics at Université Gustave Eiffel.
    My teaching focuses mainly on several aspects of programming. I teach at various levels, Master 1 (first year of master), École d'Ingénieurs, and Licence 3. I also intervene in the course in Analysis of Algorithms in The Parisian Master of Research in Computer Science (MPRI). </p>
  <img src="/assets/photo-swerc.jpeg" class="teaching-photo" alt="Pablo Rotondo during SWERC analysis session">
</div>

<p></p>

## 📌 Current Teaching
 
<div class="courses-grid">
{% for course in site.data.teaching.current %}
<div class="course-card">
<h3>
  <i class="fa-solid fa-{{ course.icon }}"></i>
  {{ course.title }}
</h3>

<p class="meta">
  {{ course.level }} • {{ course.year }} • {{ course.hours }}
</p>

<p>{{ course.description }}</p>

{% if course.links %}
<p class="links">
{% if course.links.syllabus %}
<a href="{{ course.links.syllabus }}">
  <i class="fa-solid fa-file-pdf"></i> Syllabus
</a>
{% endif %}
{% if course.links.github %}
• <a href="{{ course.links.github }}">
  <i class="fa-brands fa-github"></i> Resources
</a>
{% endif %}
</p>
{% endif %}
</div>
{% endfor %}
</div>

## 📅 Past Teaching
Show past courses
<details>
<ul>
{% for course in site.data.teaching.past %}
<li>
<strong>{{ course.title }}</strong> — {{ course.level }} ({{ course.year }})
</li>
{% endfor %}
</ul>
</details>

<!--<h4>  Maître de Conférences, Université Gustave Eiffel  </h4>-->
<!--<ul>-->
<!--<li>-->
<!--2022-- - Programmation d'applications réseaux, Cours/TD (45h, Master 1 Informatique) -->
<!--</li>-->
<!--<li>-->
<!--2022-- - Java Avancé, TP (Master 1 Informatique) -->
<!--</li>-->
<!--<li>-->
<!--2022-- - Concurrence in Java, Cours/TD (Master 1 Informatique)-->
<!--</li>-->
<!--<li>-->
<!--2023-- - Programmation Système, TP (Licence 3 Informatique)-->
<!--</li>-->
<!--</ul>-->
<!--<p></p>-->
<!--<h4>  ATER Université Gustave Eiffel  </h4>-->
<!--<ul>-->
<!--<li> 2021 - Programmation d'applications réseaux, CoursTD (45h, Master 1 Informatique) - One semester course. Design network applications and protocols on top of IP, UDP or TCP, in Java. -->
<!--</li>-->
<!--<li> 2021 - Algorithmique avancée, TD+TP (30h, 3rd semester, engineering students) - Dynamic programming, divide and conquer, algorithms on graphs.-->
<!--</li><li> 2021 - Algorithmique des arbres, TP (24h, 3rd semester, Licence Informatique) - Introduction to trees in C: lists, trees, binary search trees, AVL, heaps.-->
<!--</li><li> 2021 - Compilers, TD (24h, 3rd year, Licence Informatique) - One semester course. Translation in Flex&amp;Bison, along with assembler x86, in order to make a compiler for a ``reduced'' subset of the C language.-->
<!--</li>-->
<!--<li> 2020 - Analyse syntaxique, TD+TP (30h, 3rd semester, engineering students) - One semester course. Context free grammars, push-down automata, elimination of left-recurisivity, Chomsky normal form, LL(k) and LR(k) grammars. Construction of syntax analyser for a subset of the C language.-->
<!--</li><li> 2020 - Intro. Prog. C, TD (24h, 3rd semester, Licence Informatique) - Introduction to trees in C: lists, trees, binary search trees, AVL, heaps.-->
<!--</li><li> 2020 - Prog. C Avancée, TD (48h, 3rd year, Licence Informatique).-->
<!--</li><li> 2020 - Principes des systèmes d’exploitation, TD (20h, 3rd semester, DUT Informatique) - Introduction to computer architecture, assembleur, system calls and processes&amp;threads in C. </li>-->
<!--</ul>-->

<!--<p></p>-->
<!--<h4>  ATER Marne-la-Vallée  </h4>-->
<!--<ul>-->
<!--<li> 2019 - Algorithmique avancée, TD+TP (30h, 3rd semester, engineering students) - Dynamic programming, divide and conquer, algorithms on graphs.-->
<!--</li><li> 2019 - Algorithmique des arbres, TP (24h, 3rd semester, Licence Informatique) - Introduction to trees in C: lists, trees, binary search trees, AVL, heaps.-->
<!--</li><li> 2019 - Compilers, TD (48h, 3rd year, Licence Informatique) - One semester course. Translation in Flex&amp;Bison, along with assembler x86, in order to make a compiler for a ``reduced'' subset of the C language.-->
<!--</li><li> 2018 - Principes des systèmes d’exploitation, TD (40h, 3rd semester, DUT Informatique) - Introduction to computer architecture, assembleur, system calls and processes&amp;threads in C.-->
<!--</li><li> 2018 - Administration Système, CM+TP (30h, 1st semester engineering students) - Introduction to the *nix environment: installing debian, bash, disk partitions, backups.-->
<!--</li>-->



<!--</ul>-->
<!--<p></p>-->
<!--<h4> Monitorat: Licence Informatique, Paris 7 </h4>-->
<!--<ul>-->
<!--<li> 2018 - Internet et Outils 2, TD (48h, 2nd semester students) - Introduction to web programming with <abbr title="HyperText Markup Language">HTML</abbr>, <abbr title="Cascading Style Sheets">CSS</abbr> and PHP.-->
<!--</li><li> 2017 - <a href="https://www.irif.fr/~amicheli//Ens/EA3/" class="urlextern" title="https://www.irif.fr/~amicheli//Ens/EA3/" rel="nofollow">Eléments d'Algorithmique 2</a>,-->
<!-- TD (24h, 3rd semester students) - Third semester course giving basic -->
<!--notions of correctness and efficiency of an algorithm. Includes basic -->
<!--data structures, Mergesort and Binary Heaps.-->
<!--</li><li> 2016 - <a href="https://www.irif.fr/~amelie/BD1617.html" class="urlextern" title="https://www.irif.fr/~amelie/BD1617.html" rel="nofollow">Bases de Donées</a>,-->
<!-- TP (36h, 3rd semester students) - Introduction to Databases: relational-->
<!-- algebra, SQL queries, database design. Project in MySQL.-->
<!--</li><li> 2016 - Initiation à la Programmation-->
<!-- 1, TP (24, 1st semester students) -   Introduction to programming for -->
<!--first semester students.-->
<!--</li><li> 2016 -  Initiation à la -->
<!--Programmation 2, TD and TP (48h, 2nd semester students), TD (24h, 2nd -->
<!--semester students) -   Programming of basic  data structures such as -->
<!--lists and trees in Java.-->
<!--</li><li> 2016 - <a href="https://www.irif.univ-paris-diderot.fr/~yunes/cours/concepts/" class="urlextern" title="https://www.irif.univ-paris-diderot.fr/~yunes/cours/concepts/" rel="nofollow">Concepts Informatiques 2</a>,-->
<!-- TD (24h, 2nd semester students) -  Introduction to concepts such as -->
<!--pointers and recursion, emphasis given on what happens at the machine -->
<!--level (pseudo-ensembler).-->
<!--</li>-->





<!--</ul>-->
