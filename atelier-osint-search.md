---
layout: slide
lang: FR
title:  "Search avancé"
transition: slide
order: 4
onhome: true
categories: [OSINT]
licence: "CC BY 3.0"
---

<section>
  <h1>{{page.title}}</h1>
</section>

<section data-markdown>
Google Dorking
================
</section>

<section data-markdown>
Opérateurs
----------

  * "expression exacte"
  * OR &#8680; ce terme OU l'autre terme : *Google OR vie privée*
  * \- &#8680; mot à exclure de la recherche : *Google -privacy*
  * \* &#8680; caractère joker : <em>rock * roll</em>
  * 10..20 &#8680; échelle :  *Sarkozy 2002..2003*
  * in  &#8680; conversion : *250 $ in €*
</section>

<section data-markdown>
Cibles
--------
  * intitle: Titre de la page
  * site:monsite.com ou site:.edu
  * inurl: termes précis dans l'url
  * intext: dansle corps de page
  * filetype:pdf
  * link:http://www.cfjparis.com/ (déprécié)
</section>

<section data-markdown>
Exemple de combinaisons
------
> "Macron" intitle:"top 5..10 facts" -site:youtube.com inurl:2015
</section>

<section data-markdown>
Des infos juteuses
---
>intitle:”curriculum vitae” “Tel * * *” “adresse *” “e-mail”
</section>

<section data-markdown>
À la recherche de plagiat
-------
> intext:"ma phrase pompée ailleurs" -site:monsite.com
</section>

<section data-markdown>
Apprendre à remonter le temps
----

* Utiliser le cache de Google
* Fouiller les archives d’Internet avec [Internet Archive Wayback Machine](https://web.archive.org/) ou [archive.today](https://archive.fo/)
* Remonter le temps avec [l’extension Way Back Machine](https://addons.mozilla.org/fr/firefox/addon/wayback-machine_new/?src=search)
* Suivre le trafic aérien avec [flightaware.com](https://fr.flightaware.com/) ou [flightradar24.com](https://www.flightradar24.com/)
* Suivre le trafic maritime avec [marinetraffic.com](https://www.marinetraffic.com/)
</section>
