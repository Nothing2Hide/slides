## Avant de commencer 🗳️

- Utilisez-vous une IA générative dans votre travail ?
- Si oui, pour quoi faire ? (recherche, résumé, traduction, rédaction…) ?

Note:
5 min. Recueillir les usages réels du public : cela permet d'adapter les exemples tout au long de la session. Annoncer le plan ensuite.



# L'IA : des stats et non de la magie

Note:
12 minutes. Objectif : casser l'anthropomorphisme. Tout le reste de la présentation découle de cette partie.


**L'IA** est un système informatique capable **d'imiter certaines fonctions cognitives humaines** dans un domaine très précis.


**L'IA** repose sur :

- des **algorithmes** (suites d'instructions logiques)
- des **données massives** pour l'apprentissage
- des **[réseaux de neurones artificiels](https://fr.wikipedia.org/wiki/R%C3%A9seau_de_neurones_artificiels)** (modèles probabilistes)

Note:
Un réseau de neurones artificiels est un système informatique dont la conception est inspirée à l'origine du fonctionnement des neurones mais qui, par la suite, s'est rapproché des méthodes statistiques. Les réseaux de neurones artificiels sont généralement optimisés par des méthodes d'apprentissage de type probabiliste.


## Ce que **l'IA** n'est pas

❌ L'IA **ne comprend pas** ce qu'elle fait

❌ L'IA **ne ressent rien**

✅ L'IA **optimise** une tâche sur la base de **statistiques**

Note:
Un LLM prédit le mot suivant le plus PROBABLE, pas le plus VRAI. Le plus vraisemblable n'est pas le plus pertinent, et surtout pas le plus vrai. 


## Quiz

1. 🤔 Un robot est forcément une IA
1. 🤔 Facebook utilise l'IA
1. 🤔 Mon micro-onde contient de l'IA
1. 🤔 Mon téléphone contient de l'IA
1. 🤔 Une IA forte et autonome existe aujourd'hui

Note:
Quiz interactif — faire répondre dans le chat ou via sondage.
Réponses : Non (un robot est une machine mécanique, l'IA un logiciel) / Oui (Yann LeCun a longtemps dirigé le pôle IA de Meta) / Non (tâche fixe, sans apprentissage) / Oui (reconnaissance faciale, vocale, prédiction de texte) / Non (objectif scientifique encore très difficile).


## Comment apprend une IA ?

1. On fournit des **milliers d'exemples** (textes, images, sons…)
2. L'IA identifie des **motifs statistiques**
3. Elle **ajuste ses paramètres**
4. On **valide** avec de nouveaux exemples


### 🎮 Démo

[Quick Draw de Google](https://quickdraw.withgoogle.com)

Note:
L'IA n'a aucune idée de ce qu'est un chien, elle compare votre dessin aux millions de dessins de son entraînement.
Démo en partage d'écran, 2 min max : quickdraw.withgoogle.com. Très efficace pour montrer la reconnaissance de patterns sans compréhension.


## Les LLM : la révolution 2022-2023

ChatGPT, Claude, Gemini, Mistral...


- Ils génèrent du texte, des images, du code
- Ils sont entraînés sur des **quantités astronomiques** de données issues d'internet
- Ils sont accessibles à tous via des interfaces simples


⚠️ Bluffants, mais ils **inventent parfois** des informations : les « hallucinations »

Note:
Transition : « le plus probable ≠ le plus vrai » — c'est exactement le mécanisme qui produit les hallucinations. Partie 2.



# Les hallucinations


**Une hallucination** est une **affirmation** plausible mais non fondée : ni sur les connaissances du modèle, ni sur les documents fournis. Et donc souvent **fausse**.


<acronym title="École Polytechnique Fédérale de Lausanne">L'EPFL</acronym> a réalisé un benchmark sur les [hallucinations des LLM](https://halluhard.com/index.html). Il comporte 950 questions réparties dans quatre domaines&nbsp;: ⚖️ Juridique, 🔬 Recherche, 🏥 Médical et 💻 Programmation.


<strong class="r-fit-text">30 %</strong>


C'est le taux d'hallucination du meilleur modèle testé. 


Sans recherche web ce taux s'élève à **60 %**


Dans le domaine de la recherche, certains modèles dépassent **90 %**



# IA et journalisme


## L'IA n'est pas une source

- Elle propose le plus **probable**, pas le plus **vrai**
- Elle ne fait pas la différence entre vrai et faux


## Calcul coût/bénéfice

Parfois, la quantité d'informations à vérifier dans une production générée par IA est telle que :

- **le gain de temps est proche de zéro**
- **le risque d'erreur n'est pas acceptable**


## L'IA peut être une aide...

...pour l'analyse de documents : [Google Notebook LM](https://notebooklm.google.com/?) est un outil précieux. On peut aussi mentionner le [projet Spinoza](https://rsf.org/fr/projet-spinoza) de RSF ou le chatbot de factchecking [Vera](https://www.askvera.org/).
 


# IA et données sensibles


> Évitez d'entrer dans les IA des informations confidentielles :
> sur **l'entreprise**, sur votre **vie privée**, sur vos **enquêtes en cours**.


Les CGU par défaut des outils grand public autorisent l'usage de vos conversations pour l'entraînement

Note:
Rappeler les CGU : OpenAI utilise par défaut les conversations pour améliorer les modèles (désactivable dans les paramètres) ; Google peut faire examiner certaines données par des humains. Toujours vérifier les réglages.


Aux États-Unis, le **Cloud Act** permet aux autorités américaines d’accéder aux données stockées par les entreprises technologiques américaines, **quelle que soit la localisation géographique des serveurs**.


⚠️ **L'identité d'une source glissée dans un prompt peut finir dans un modèle ou dans une fuite**


## Lumo (Proton) 🇨🇭


- **Aucun journal** de conversations côté serveur
- **Chiffrement à connaissance nulle** : même Proton ne peut pas lire vos échanges
- **Pas d'entraînement** des modèles sur vos conversations
- Aucun envoi à des tiers américains ou chinois


## Les autres outils

**[Duck.ai](https://duck.ai/) (DuckDuckGo)** — accès anonymisé, sans compte, engagement contractuel de non-entraînement

**[Vibe](https://chat.mistral.ai/) (Mistral AI)** 🇫🇷 — acteur européen, RGPD, désactivation de l'entraînement possible

**Les modèles locaux** 🏆 garantie maximale. Mais 💰💰💰.


**Plus l'enquête est sensible, plus l'outil utilisé doit être proche de la machine :** Hébergement Local → Hébergement en Europe ET chiffré (Lumo) → Hébergé en Europe (Mistral) → Tous les autres modèles → [ChatGPT](https://www.numerama.com/cyberguerre/2191051-anthropic-mis-dehors-par-trump-openai-prend-sa-place-avec-les-memes-garanties.html)


Dans tous les cas :

- **Anonymiser** avant de soumettre
- **Ne jamais** mentionner une source nommément



# Conclusion


1. 🎲 L'IA donne une réponse **probable**, pas forcément vraie
2. 🔍 On vérifie tout, on ne publie rien de brut
3. 🔒 On protège ses sources comme si chaque prompt était public


# Questions
