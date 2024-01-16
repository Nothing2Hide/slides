Chiffrement ou anonymat ?
=======


-   Avec WhatsApp, Messenger ou Telegram, le contenu de votre message
    est chiffré (plus ou moins selon l\'application) mais pas les
    adresses des correspondants
-   Les métadonnées suffisent. Ex :
    [Verizon](http://www.theguardian.com/world/2013/jun/06/nsa-phone-records-verizon-court-order),
    les [fadettes du
    Monde](http://www.lemonde.fr/societe/article/2013/11/14/fadettes-du-monde-philippe-courroye-devant-le-csm_3513762_3224.html)


Ces outils vous permettent de vous fondre dans la masse. Ils ne protègent pas autant vos échanges que des outils qui les chiffreraient de bout en bout mais ils vous permettent de conserver un bon degré d'anonymat.



Communications anonymes
=========


### La boite morte

Une boite morte est un emplacement permettant à des personnes d’échanger secrètement des messages sans avoir besoin de se rencontrer physiquement. Ce principe peut se transposer dans le monde numérique :  


1. Créez une boite mail d'un service mainstream
2. 1. partagez en les identifiants avec votre interlocuteur
3. Échangez des messages uniquement  le dossier brouillon.

Avec une boite morte les emails ne circulent pas sur Internet. La seule chose que pourra voir votre FAI est que vous vous connectez à un service de mail mainstream. Attention, les messages dans la boite ne sont pas chiffrés et sont potentiellement accessibles à l'opérateur du service (Google pour Gmail par exemple).


### Documents partagés en ligne

![](https://cryptpad.fr/customize/CryptPad_logo_hero.svg?ver=5.6.0-b)

CryptPad est un service équivalent à google doc...en mieux. 


Vous pouvez l'utiliser selon le même principe qu'une boite morte, en plus sécurisé. 


Les documents sont stockés de manière chiffrée et l'hébergeur du service ne peut accéder au contenu de vos documents sans la clé de chiffrement.


Celle-ci se trouve dans l'url après le caractère #. Par convention tout ce qui se trouve après un # dans l'url n'est pas accessible au serveur) 

> https://cryptpad.fr/pad/#/2/pad/edit/**J6KGLGTPSH1lJyc0U1U2zFLz**/


Notez bien que toute personne ayant accès à l'adresse de votre doc en ligne pourra en lire le contenu.



Communications sécurisées
=========


### emails ?

Les mails ne sont pas sécurisés. Ils circulent encore sur Internet en clair, c'est  à dire que le contenu peut en être lu par votre FAI comme le facteur le ferait avec celui d'une carte postale. 


Pour remédier à ce problème simplement, utilisez les services mail <a href="https://protonmail.com/">ProtonMail</a> ou <a href="https://tutanota.com/">Tutanota</a>.


**Attention**, seuls les mails envoyés de Protonmail  à Protonmail ou de Tutanota à Tutanota sont chiffrés automatiquement. Pour un  e-mail chiffré destiné à un destinataire externe, un mot de passe pour le chiffrement et le déchiffrement de l'e-mail doit être  échangé. 


![La fonctionnalité external encryption de Protonmail pour envoyer un message chiffré  à une adresse autre que proton](/assets/i/protonmail.png)


![Signal](https://wiki.nothing2hide.org/lib/exe/fetch.php?media=fiches_pedagogiques:2b236f00f769018f1e71c4dc1f9bad04.png)


[Signal](https://signal.org/) est une application pour smartphone qui protège vos messages en les chiffrant sur votre téléphone et en les déchiffrant sur le téléphone du ou des destinataires. C'est le chiffrement de bout en bout (End To End Encrpytion). Ainsi même si les serveurs de Signal se font pirater, le contenu de vos échanges ne pourra être dévoilé. 


Signal ne conserve pas les métadonnées au-delà de la période requise pour la circulation du message. Il ne s’agit que d’une rétention temporaire, d’ordre technique.


Attention toutefois, les messages envoyés sont stockés sur les téléphones et si ceux ci sont saisis physiquement et déverrouillés, il sera alors possible d'accéder à vos messages. C'est pour cette raison que Signal (ainsi que d'autres applications) proposent une fonctionnalité très utile : les messages éphémères vous permettant de définir un délai de suppression automatique pour vos messages envoyés.


![Messages éphémères sur Signal](/assets/i/signal-msg-ephemere.png)


Vous utilisez une autre application ? Discord, WhatsApp, iMessage, Telegram, etc. ? Vérifiez si votre application utilise le chiffrement de bout en bout et quelles données celle-ci laisse filtrer sur vos échanges en consultant ce [tableau](https://www.messenger-matrix.de/messenger-matrix-en.html).



Communications anonymes et sécurisées
=============


Wire
---
[Wire](https://wire.com/en/ "https://wire.com/en/"): Wire est un outil de communication sécurisé qui présente l'avantage de ne nécessiter aucun numéro de téléphone.


Briar
---
[Briar](https://briarproject.org/download-briar/ "https://briarproject.org/download-briar/") : Briar est une application CPT (communication **C**hiffrée en **P**air-à-pair via **T**or). Avec Briar les communications circulent de smartphones en smartphones sans passer par un serveur central et utilisent le réseau Tor.


Olvid
---
[Olvid](https://olvid.io/) :  Un simple pseudo suffit pour se créer un compte. Sur Olvid les communications **et** les métadonnées sont chiffrées de bout en bout. L’application est certifié CSPN par l’Agence nationale de la sécurité des systèmes d’information (ANSSI). Olvid propose une version gratuite avec quelques fonctionnalités en moins (pas d'appels vocaux).


<img src="/assets/i/careful.gif" alt="On n'est jamais trop prudent" title="On n'est jamais trop prudent" width="" height="500" />

On n'est jamais trop prudent !


TNO
===

Trust No One

-   Prontmail + Tor
-   Protonmail + VPN
-   Cryptpad + Tor
-   Dropbox + Veracrypt
