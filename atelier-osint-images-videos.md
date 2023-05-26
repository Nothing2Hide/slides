---
layout: slide
lang: FR
title:  "Images et vidéos"
transition: slide
order: 2
onhome: true
categories: [OSINT]
licence: "CC BY 3.0"
---

<section>
  <h1>{{page.title}}</h1>
</section>

<section>
  <section data-markdown>
  Objectifs
  ================
  </section>
  <section data-markdown>
  * Comprendre les métadonnées
  * Utiliser la recherche inversée
  * Analyser le contexte d’une image ou d’une vidéo
  </section>
</section>

<section>
  <section data-markdown>
  Les fake news sont partout
  ================
  </section>
  <section data-markdown>
  Bruxelles 2016
  ----
  Suite à l’attentat à l’aéroport de Zaventem/Bruxelles, [une vidéo de caméra de surveillance](https://www.youtube.com/watch?v=mauYfrcudlY) a commencé à circuler.  
  Elle a été reprise par tous les médias. **Fake ou pas fake ?**
  </section>
</section>

<section>
  <section data-markdown>
  Les Les métadonnées
  ================
  Comment obtenir des informations sur une image à partir de ses métadonnées.
  </section>
  <section data-markdown>
  Tout fichier informatique, en plus de ses données, comprend des informations descriptives appelées “métadonnées”. Elles sont présentes dans les fichiers :
  * pdf
  * jpg, png
  * docx, odt, etc.
  </section>
  <section data-markdown>
  Lire les métadonnées d’une image
  ----
  Directement dans votre navigateur avec une extension : 
  *  [exif viewer](https://addons.mozilla.org/fr/firefox/search/?q=exifViewer) dans firefox
  *  [exif viewer](https://chrome.google.com/webstore/detail/exif-viewer-pro/mmbhfeiddhndihdjeganjggkmjapkffm) dans Chrome
  *  En ligne avec le site [Jeffrey image Meta Data Viewer](http://exif.regex.info/down.html)
  </section>
  <section data-markdown>
  Exercice
  ----
  Lire les métadonnées de cette [image](/i/assets/img-full-of-data.jpg).
  </section>
  <section data-markdown>
  Depuis [la “mésaventure” de John McAfee](https://www.wired.com/2012/12/how-vice-got-john-mcafee-caught/), la plupart des services d’hébergement d’images et tous les réseaux sociaux, suppriment aujourd’hui les métadonnées des images.
  </section>
</section>

<section>
  <section data-markdown>
  Recherche inversée
  ================
  Identifier le premier site de publication d’une image ou d’une photo.
  </section>
  <section data-markdown>
  Vérifier l'antériorité d'une image ou d'une vidéo avec
  * [TinEye](https://tineye.com/)
  * [Google Image](https://images.google.com/)
  * [Yandex](https://yandex.ru/images/)
  * [Karmadecay](http://karmadecay.com/) (reddit)
  * [Citizen evidence](https://citizenevidence.amnestyusa.org/) pour les vidéos
  </section>
</section>

<section>
  <section data-markdown>
  Fake ou non ?
  ================
  </section>
  <section data-markdown>
    ![Pilote](/assets/i/osint-pilote.jpg)
  </section>
  <section data-markdown>
  ![Ukraine](/assets/i/enfant_3.jpg)
  </section>
  <section data-markdown>
  ![Requin](/assets/i/osint-requin.jpg)
  </section>
</section>

<section>
  <section data-markdown>
  Analyser le contexte
  ================
  Les outils c’est bien, mais ça ne fait pas tout. Débunker une photo manipulée, c’est surtout une histoire d’observation.
  </section>
  <section data-markdown>
    ![Chine](/assets/i/osint-contexte.png)
  </section>
  <section data-markdown>
    ![Iran](/assets/i/osint-iran.png)
    
	La scène était présentée comme se déroulant en Iran, en décembre 2009. Cette photo est intéressante car elle offre plusieurs détails permettant de la vérifier.   
	</section>

  <section data-markdown>
		Les boucliers de la police iranienne sont-ils de cette couleur ? Les trottoirs de Téhéran peints en jaune ? Les jeunes Iraniens habillés de cette façon ? Quel temps fait-il en Iran en décembre ?
	</section>
  <section data-markdown>
    Pour connaître la météo en tout lieu et tout temps : [wunderground.com](https://wunderground.com)
  </section>
  <section data-markdown>
    D’après la légende sur YouTube, [cette vidéo](https://www.youtube.com/watch?time_continue=43) montre un groupe de réfugiés attaquer une voiture de police à Erfurt, une ville du centre de l’Allemagne. Deux détails pouvaient néanmoins faire tiquer.
  </section>
  <section data-markdown>
  1. La couleur des voitures de plice. Une simple recherche sur Internet vous permet de découvrir que ce ne sont pas les couleurs utilisées par la ville de Erfurt ;
  1. En écoutnat bine la vidéo on entend que les soit disant réfugiés parlent tous en allemand.
  </section>
  <section data-markdown>
  Cette photo montre quelques détails qui permettent de localiser tèrs précisément la prise de vue à l'aide de Google Maps.
  </section>
  <section data-markdown>
    ![china town](/assets/i/osint-chine.png)
  </section>
  <section data-markdown>
    ![Linden New-Jersey](/assets/i/osint-linden.png)
    Le 17 septembre 2016, l'explosion d'une bombe blesse 29 personnes à New York. Deux jours plus tard un suspect est arrêté à Linden dans le New Jersey. Tout de suite après l’arrestation, une photo circule. Ainsi qu’une vidéo. Cette photo est-elle vraiment une photo de l'arrestation du poseur de bombe ?
  </section>
</section>

<section>
  <section data-markdown>
  Pour aller plus loins
  ================
  * [Videos visual verification guide](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_videos.pdf)
  * [Photo visual verification guide](https://firstdraftnews.org/wp-content/uploads/2017/03/FDN_verificationguide_photos.pdf?x40896)
</section>
