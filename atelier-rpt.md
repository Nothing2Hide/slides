---
layout: slide
lang: FR
title:  "RPT N2H : Smartphones et sécurité"
transition: slide
onhome: false
categories: [Sécurité numérique]
licence: "CC BY 3.0"
---

<section>
<section data-markdown>
La base : ~~Mots de passe~~
---------------------------

Votre mot de passe est-il [suffisamment
robuste](https://nothing2hide.org/fr/verifier-la-robustesse-de-votre-mot-de-passe/) ?
</section>

<section data-markdown>
-   Oubliez les ~~mots de passe~~, utilisez des [phrases de
    passe](https://www.xkcd.com/936/)
-   Plus votre phrase de passe comporte de caractère, plus elle sera
    difficile à craquer
-   Évitez les titres de films, de romans ou toute information
    personnelle facile à deviner
-   **Utilisez une phrase différente par service**
-   Aidez-vous de gestionnaires de mot de passe :
    [Bitwarden](https://bitwarden.com/),
    [Dashlane](https://www.dashlane.com/) ou
    [KeePass](http://keepass.info/)
</section>

<section data-markdown>
Activez la **double authentification** sur vos comptes

-   [Google](https://myaccount.google.com/security)
-   [Microsoft](https://docs.microsoft.com/fr-fr/microsoft-365/admin/security-and-compliance/set-up-multi-factor-authentication?view=o365-worldwide)
-   [Apple](https://www.moyens.net/comment/comment-verifier-qui-a-acces-a-votre-iphone-et-a-votre-compte-apple/)
-   [Twitter](https://twitter.com/settings/account/login_verification)
-   [Facebook](https://www.facebook.com/settings?tab=security&section=approvals&view)
-   [Instagram](https://help.instagram.com/566810106808145)

N'oubliez pas de télécharger les codes de secours.
</section>
</section>

<section>
<section data-markdown>
Applications droits et permissions
----------------------------------

Comme sur un poste informatique on n'installe pas n\'importe quelle
application sur son Smartphone. Il faut vérifier les droits que réclame
une application sur votre smartphone. Ex : est-il normal qu'une
application lampe de poche réclame l'accès à vos contacts ?
</section>
<section data-markdown>
Il y a 2 écosystèmes d'applications majeurs aujourd'hui qui sont Android
et Apple.

1.  Apple est réputé pour ses contrôles et validations avant la mise à
disposition public.
2.  Android (Google) hélas beaucoup moin
</section>  
<section data-markdown>
![description](/assets/i/android-permissions.png "tool tip")
</section>
<section data-markdown>
Selon votre version Android (6 et supérieur), il vous faudra chercher le
plus souvent dans Paramètres \> Applications \> ( parfois Paramètres
avancés) \> Autorisation des applis.
</section>
<section data-markdown>
Afin de vérifier les droits que s\'octroie sur votre téléphone une
application Android, allez faire un tour sur le projet [Exodus
Privacy](https://exodus-privacy.eu.org/fr/page/what/).
</section>
</section>

<section>
<section data-markdown>
Chiffrement et smartphone
-------------------------

-   Protéger l\'ouverture de votre smartphone Android ou
  [iOS](https://support.apple.com/fr-fr/HT204060) avec un mot de passe
-   Éviter les shémas (Android), les empreintes ou la reconnaissance
  faciale
</section>
<section data-markdown>
Android
-------

Le chiffrement de vos données est activé par défaut depuis **Android 6.0
Marshmallow**. Le chiffrement se fait de façon invisible lorsque le
configurateur vous demande de choisir un verrouillage d\'écran : schéma,
code PIN ou mot de passe. Reconnaissance faciale et empreinte digitale
ne rentrent pas dans le lot !
</section>
<section data-markdown>
iPhone
------

Depuis **iOS 8** les données personnelles sur les téléphones d\'Apple
sont chiffrées par défaut lorsque le téléphone est verrouillé par un
code ou par Touch ID.

Il est possible de configurer un effacement automatique après 10
tentatives infructueuses de déverouillage.
</section>
<section data-markdown>
![](/assets/i/ios-erasing.webp){height="600"}
</section>
  
<section data-markdown>
Des données partout
-------------------

Rappelez-vous, votre smartphone contient des données à plusieurs
endroits :

-   Sur la carte sim
-   Dans la mémoire du téléphone
-   Sur la carte SD
-   Dans les \"nuages\" si vous utilisez une service de cloud icloud ou
  Google drive
</section>
  
<section data-markdown>
Tella : un coffre fort local
----------------------------

[Tella](https://play.google.com/store/apps/details?id=org.hzontal.tella&hl)
est une application android qui permet de prendre des photos et vidéos
et de les stocker chiffrées, de les camoufler, voire des les effacer en
cas d\'urgence.
</section>
<section>
<img src="/assets/i/tella-installation.gif" alt="Installation de Tella" title="Installation de Tella" width="" height="600" />
</section>
<section>
<img src="/assets/i/tella-video.gif" alt="Prise d'images, de vidéos ou de sons dans Tella" title="Prise d'images, de vidéos ou de sons dans Tella" width="" height="600" />
</section>
<section>
<img src="/assets/i/tella-import.gif" alt="Import de fichiers dans Tella" title="Import de fichiers dans Tella" width="" height="600" />
</section>
</section>

<section>
<section data-markdown>
Un mouchard de poche
============
</section>
<section data-markdown>
En veille
---------

-   Vous êtes identifié de manière unique sur le réseau GSM
    avec le numéro unique de votre carte SIM (IMSI) et celui de votre téléphone(IMEI).
-   Votre téléphone se borne régulièrement auprès des antennes relais en
    transmettant ces deux informations
-   Votre opérateur téléphonique a la capacité technique de localiser la
    celulle réseau dans laquelle vous vous situez (de quelques mètres à
    plusieurs kilomètres)
</section>
<section data-markdown>
[De nombreux logiciels](http://www.gsmespion.com/) peuvent transformer
votre smartphone en micro espion. Ils doivent cependant être installés
sur votre téléphone.
</section>
<section data-markdown>
![puce espionne]({{site.url}}{{site.baseurl}}/assets/i/iphone-puce.jpg "Puce espionne")
<aside class="notes">
Pour à peine 15$ on peut acheter du matériel espion sur Alibaba. Ici une puce trouvée dans l'iphone d'un activiste russe.
</aside>
</section>
<section data-markdown>
Éteint
------

La batterie, branchée, est toujours une source d\'énergie. Avec la
collaboration l\'opérateur téléphonique, qui lui peut accéder aux
paquets envoyés à la carte SIM (Application Protocol Data Unit), le
téléphone peut théoriquement être activé.
</section>
<section data-markdown>
Batterie démontée
-----------------

-   Sans batterie, pas d\'énergie, pas de signaux transmis, pas de
    surveillance.
-   Problème : peu de téléphones disposent encore d\'une batterie
    amovible
</section>
</section>


<section>
<section data-markdown>
Communications
==========
</section>
<section data-markdown>
Le réseau GSM
----------------
L'algorithme de chiffrement du réseau GSM est compromis depuis
longtemps. Les communications téléphoniques et SMS ne sont pas
sécurisées.
</section>
<section data-markdown>
4G / WiFI
----
- [Signal](https://signal.org/) pour [Android](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms) et [Iphone](https://itunes.apple.com/us/app/signal-private-messenger/id874139669?mt=8) 
- [Wire](https://wire.com/en/) pour [iOS](https://itunes.apple.com/app/wire/id930944768?mt=8) ou [Android](https://play.google.com/store/apps/details?id=com.wire)
- Évitez [Whatsapp](https://www.whatsapp.com/) pour les communications sensibles
- Telegram est à banir
</section>
</section>

<section>
<section data-markdown>
Contrôler ses données à distance
===
</section>
<section data-markdown>
Android
---

1.  Allez dans la section [appareils](https://myaccount.google.com/device-activity) de sécurité de votre compte Google
2.  faites sonner votre smartphone, localisez-le ou effacez les données à distance
</section>
<section data-markdown>
iOS
---
Le service de localisation [icloud.com/find/](https://www.icloud.com/find/) vous permet de localiser tout appareil Apple (iphone, ipad, mac, airpods) et d'effacer des données à distance si besoin.
</section>
</section>

<section>
    <section>
        <h2>Autre option</h2>
    </section>
    <section data-background="{{site.url}}{{site.baseurl}}/assets/i/dumbphone.jpg">
        <aside class="notes">Burner phone. Image issue de <a href="http://in30minutes.com">In 30 Minutes guides</a> sous licence CC 2.0</aside>
    </section>
</section>

<section data-background="{{site.url}}{{site.baseurl}}/assets/i/questions-willsmith.gif" data-background-transition="zoom">
    <h1>Questions ?</h1>
</section>

