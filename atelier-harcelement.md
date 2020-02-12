---
layout: slide
lang: FR
title:  "Le cyberharcèlement"
transition: slide
onhome: true
categories: [Atelier]
licence: "CC BY 3.0"
images: /assets/i/
order: 3
background: "#34495e"
---

<section data-background="{{page.images}}harcelement.jpg">
    <h1>{{page.title}}</h1>    
</section>



<section data-background="{{page.background}}">

<section data-markdown data-background="{{page.background}}">
    ## Comment s'en prémunir
</section>

<section data-markdown data-background="{{page.background}}">
Vérifiez votre présence sur Internet avec [namechecker](http://namechk.com/)
</section>

<section data-markdown data-background="{{page.background}}">
Utilisez des [requêtes avancées dans Google](https://slides.nothing2hide.org/atelier-investigation.html) : 
</section>

<section data-markdown data-background="{{page.background}}">
Pour voir si votre adresse traîne en ligne :

    "nom prénom" "adresse *"
</section>
<section data-markdown data-background="{{page.background}}">
Pour voir si votre numéro traîne en ligne :

    "nom prénom" "06 *"

    "nom prénom" "07 *"
</section>

<section data-markdown data-background="{{page.background}}">
Vérifiez les [options de confidentialité](https://twitter.com/settings/safety) de votre compte twitter

![Options de vie privée]({{page.images}}twitter-privacy.png)
</section>

<section data-markdown data-background="{{page.background}}">
Regardez [ce que les autres peuvent voir de votre profil](https://fr-fr.facebook.com/help/288066747875915) Facebook

![Options de vie privée]({{page.images}}facebook-privacy.png)
</section>

<section data-markdown data-background="{{page.background}}">
Vérifiez les [options de confidentialité](https://www.facebook.com/settings?tab=privacy) de votre compte Facebook
</section>
</section>





<section data-background="# {{page.background}}">
<section data-markdown data-background="#ff4242">
    ## Adoptez une stratégie
</section>
<section data-background="{{page.background}}">
    <h1>Anonyme ou pas ?</h1>
    <ul>
        <li>Identité réelle</li>
        <li><del>Anonymat</del></li>
        <li>Pseudonymat</li>
        <li>Identité collective</li>
    </ul>
</section>
<section data-background="{{page.background}}">
    <table>
        <tbody><tr>
            <th>
            </th>
            <th><b>Risque</b>
            </th>
            <th><b>Réputation</b>
            </th>
            <th><b>Effort</b>
            </th></tr>
            <tr>
            <td><b>Identité réelle</b>
            </td>
            <td>+
            </td>
            <td>+
            </td>
            <td>-
            </td></tr>
            <tr>
            <td><b>Anonymat</b>
            </td>
            <td>-
            </td>
            <td>-
            </td>
            <td>+
            </td></tr>
            <tr>
            <td><b>Pseudonymat</b>
            </td>
            <td>-
            </td>
            <td>+
            </td>
            <td>+
            </td></tr>
            <tr>
            <td><b>Identité collective</b>
            </td>
            <td>-
            </td>
            <td>+
            </td>
            <td>+
            </td></tr>
        </tbody>
    </table>
    <cite title="source"><a href="https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual#Comparing_strategies">Zen and the art of making tech work for you</a></cite>
</section>
</section>





<section data-background="{{page.background}}">

<section data-markdown data-background="#FF4242">
## Que faire quand on en est victime
</section>

<section data-markdown data-background="{{page.images}}twitter-harassment.jpg">
## Sur Twitter
</section>

<section data-markdown data-background="{{page.background}}">
### Réglages et notifications
Quelques réglages simples à mettre en œuvre contre le harcèlement sur Twitter. Conseils rédigés à partir du fil de [@samuellaurent](https://twitter.com/samuellaurent) sur le sujet. 
</section>

<section data-markdown data-background="{{page.background}}">
Dans les [paramètres de notifications](https://twitter.com/settings/notifications/advanced_filters), masquez les profils qui ne vous suivent pas, qui n'ont pas de photos et qui n'ont pas confirmé leur mail.

![Filtres avancés de twitter]({{page.images}}twitter-filtre-avances.jpg)

</section>

<section data-markdown data-background="{{page.background}}">
### Soft block
</section>

<section data-markdown data-background="{{page.background}}">
Bloquer puis débloquer immédiatement un compte permet de le supprimer de vos followers sans qu' il en soit informé. Vos messages ne remonteront plus dans la timeline du troll. 

Avec les paramétrages précédents, le soft block permet également d'expulser un compte de votre timeline (puisque vous ne faites apparaître que les comptes qui vous suivent).
</section>

<section data-markdown data-background="{{page.background}}">
### Pour ne pas perdre le contact
</section>

<section data-background="{{page.background}}">
<p>Afin de ne pas vous couper de l'interactivité offerte par Twitter, vous pouvez en contrepartie <a href="https://twitter.com/settings/safety">ouvrir vos messages privés</a>.</p>

<img src="{{page.images}}twitter-mp.png" alt="messages privés ouverts">

<aside class="notes">Les harceleurs recherchent l'attention, ils n'ont aucun intérêt à  écrire un message que personne ne verra à part vous.</aside>
</section>

<section data-markdown >
### Demetricator
</section>

<section data-markdown data-background="{{page.background}}">
[L'extension Demetricator](https://bengrosser.com/projects/twitter-demetricator/) permet de cacher les indicateurs de Twitter : nombre de followers, de likes et de retweets. Vous pouvez alors utiliser Twitter sans chiffres et subirez moins la pression du nombre de retweets, de likes et de commentaires.
</section>

<section data-markdown data-background="{{page.background}}">
### Blocktogether
</section>

<section data-background="{{page.background}}">
<p><a href="https://blocktogether.org/">Blocktogether</a> utilise l’api de Twitter pour bloquer automatiquement des comptes sur la base des listes de blocage d’utilisateurs de Twitter.</p>

<p>Chaque fois que cette liste est mise à jour, votre compte twitter bloquera automatiquement les nouveaux comptes ajoutés dans la liste. Lorsqu’un compte est débloqué, il est débloqué également pour tous les comptes Twitter ayant souscrit à cette liste.</p>

<aside class="notes"> Parmi les listes de blocage francophones nous vous conseillons celle de @laurentchemla.

Important : blocktogether ne bloquera jamais un compte que vous suivez déjà, même s’il se trouve dans la liste.

Vous pouvez aussi la jouer solo et télécharger puis importer dans votre compte Twitter cette liste de blocage. Vous ne bénéficierez cependant pas des évolutions de la liste.Lien externe </aside>
</section>

</section>




<section data-markdown data-background="#FF4242">
## Pour aller plus loin

* Le chapitre [Réseaux soucieux](https://wiki.nothing2hide.org/doku.php?id=protectionnumerique:reseauxsociaux#les_reseaux_sociaux) du guide de protection numérique de Nothing2Hide
* Les supports pédagogiques [Réseaux sociaux](https://slides.nothing2hide.org/atelier-reseauxsociaux.html#/) de Nothing2Hide
* Le guide de tactical tech : [Zen and the art of making tech work for you](https://gendersec.tacticaltech.org/wiki/index.php/Complete_manual)
</section>