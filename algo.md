---
layout: page
title: Pablo Rotondo - AAP CNRS - Algo in Programming
permalink: /algo-cnrs-23/
---



<style>
 .grid {
  display: flex;
 }
.column-left{ float: left; width: 33.333%; }
.column-right{ float: right; width: 33.333%; }
.column-center{ display: inline-block; width: 33.333%; }
</style>


<h2> A fine study of algorithmic choices in 
common programming languages</h2>

<h3>
Project AAP CNRS
</h3>

Contents
<nav class="navigation">
<a href="#description">Description</a> - 
<a href="#members">Members</a> -
<a href="#meeting">Meeting</a> 
</nav>


<h3 id='description'>Description</h3>
All contemporary programming languages offer implementations of classical algorithms and classical data structures such as lists, hash tables, sorting, etc. 
These are basic building blocks that are used to develop larger programs. Efficient algorithms for dealing with such issues have been known for several decades, since the beginning of computing,
often with several efficient variants proposed in the literature.
When developers of a programming language choose to implement a particular algorithm, such as their generic array sort, they have a wide choice of solutions.
In addition to the constraints of their language, they use various performance tests to guide their decision.
Sometimes engineers innovate and go off the beaten track to propose completely new solutions. Performance testing
is not easy to perform at this level of genericity (language designers do not know in which contexts their language will be used).
In this context our project adopts the following approach:
1. Examine the source code of different programming languages (Java, PHP, Python, . . . ) to identify
surprising or questionable choices, or innovations.
2. Propose probabilistic scenarios that model realistic behaviours for the use of these algorithms.
3. Conduct a precise mathematical study of the behaviour of the algorithms studied in the various
scenarios.
4. Confirm the efficiency of certain algorithms, reveal the weaknesses of others and possibly propose improvements


More details available <a href="/files/22_AAP_CNRS.pdf">here</a> in the original proposal for the project.

<!--[3] Conrado Mart ́ınez, Cyril Nicaud, Pablo Rotondo: A Probabilistic Model Revealing Shortcomings in Lua’s-->
<!--Hybrid Tables. Accepted at COCOON 2022. https://arxiv.org/abs/2208.13602-->
<!--<a href="/files/Pres_COCOON_22-1.pdf">A Probabilistic Model Revealing Shortcomings in Lua’s Hybrid Tables</a>, COCOON 2022, Online, 23 Octobre, 2022.-->

<h3 id='members'>Members</h3>

<div class="grid">
<div class="column-left">
<h4>Université Gustave Eiffel</h4>

* [Arnaud Carayol][arnaud]
* [Cyril Nicaud][cyril]
* [Carine Pivoteau][carine]
* [Pablo Rotondo][pablo]
</div>
<div class="column-center">
<h4>Université de Caen</h4>
* [Julien Clément][julien]
* [Julien Courtiel][julieng]
* [Matthieu Dien][matthieu]
</div>
<div class="column-right">
<h4>International</h4>
* [Conrado Martínez][conrado] (UPC, Barcelona)
* [Alfredo Viola][tuba] (UdelaR, Montevideo)
</div>
</div>


<h3 id='meeting'>Meeting - Algo a la playa !</h3>

General meeting in <a href="https://www.saint-julien-en-born.fr/">Saint Julien en Born</a> programmed !

<ul>
<li>
Date:

July 3 2023 (Monday) through July 7 2023 (Friday)
</li>
<li>
Venue: tba
</li>
<li>
</li>
</ul>

<center>
<img src="https://www.guide-des-landes.com/_bibli/annonces/1347/hd/plageducontis3.jpg"  width="30%" >
<img src="https://www.guide-des-landes.com/_bibli/annonces/1347/hd/plageducontis3.jpg"  width="30%" >
<img src="https://www.guide-des-landes.com/_bibli/annonces/1347/hd/plageducontis3.jpg"  width="30%" >
</center>
<!--![Beach](https://www.guide-des-landes.com/_bibli/annonces/1347/hd/plageducontis3.jpg "Plage")-->

[pablo]: /
[cyril]: http://www-igm.univ-mlv.fr/~nicaud/
[arnaud]: http://www-igm.univ-mlv.fr/~carayol/
[carine]: http://www-igm.univ-mlv.fr/~pivoteau/
[julien]: https://clementj01.users.greyc.fr/
[julieng]: https://courtiel.users.greyc.fr/
[matthieu]: https://dien.users.greyc.fr/
[conrado]: https://www.cs.upc.edu/~conrado/
[tuba]: https://dblp.org/pid/50/6924.html
[ligm]: http://ligm.u-pem.fr/accueil/

