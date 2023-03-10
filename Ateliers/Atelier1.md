<p style="text-align:left;">
    [Retour au sommaire](../README.md)
    <span style="float:right;">
        [Atelier 2: Les biais cognitifs](Atelier2.md)
    </span>
</p>


<div style="text-align:center;">

# Atelier 1: Les méthodes scientifiques

</div>

Une méthode scientifique est une démarche qui permet de répondre à une question en utilisant des données et des observations. Elle est basée sur **l'observation**, **la répétabilité** et **la vérification des résultats**.

---

## Liens utiles

- Des slides résumants les notions présentées ci-dessous sont disponibles [ici](../fichiers/slides_atelier1.pdf)
- La page wikipedia sur les méthodes scientifiques est disponible [ici](https://fr.wikipedia.org/wiki/M%C3%A9thode_scientifique)

---

## Le raisonnement inductif <a href = "https://fr.wikipedia.org/wiki/Induction_(logique)" target = "_blank"> <img src = "../fichiers/icons/chain.png"  height = "15" width="15"/> </a>

La démarche **inductive**, aussi appelée approche **empirico-inductive**, est une méthode scientifique qui part de faits, de données brutes réelles et observables, pour aller vers l’explication de celles-ci.

À partir des phénomènes particuliers, on peut essayer de comprendre un phénomène général. On va du particulier au général.

La loi générale que l'on formule doit être vérfiée pour chacun des évènements préalables, mais elle peut à tout moment être démentie par un contre-exemple.

![Schema Inductive](images/schema_inductive.png)

*Extrait de “[Le raisonnement en sciences de l’ingénieur”, JL Prensier, T. Zenard, 2006, ENS Cachan](https://eduscol.education.fr/sti/sites/eduscol.education.fr.sti/files/ressources/pedagogiques/6217/6217-le-raisonnement-en-sciences-de-lingenieur-ens.pdf)"*

### Types de raisonnement inductif

Les types de raisonnement inductif comprennent la généralisation, la prédiction, le syllogisme statistique, l'argument de l'analogie et l'inférence causale.

#### La généralisation

Une généralisation (plus précisément, une généralisation inductive) part d'une prémisse concernant un échantillon pour aboutir à une conclusion concernant la population. L'observation obtenue à partir de cet échantillon est projetée sur une population plus large. <a href = "https://www.google.fr/books/edition/A_Practical_Study_of_Argument_Enhanced_E/_1UJzgEACAAJ?hl=fr" target = "_blank"> <img src = "../fichiers/icons/chain.png"  height = "10" width="10"/> </a>

<div class="theorem_atelier">
L'échantillon E de la population P possède l'attribut A.

Par conséquent, la population P l'attribut A.
</div>
<div class="exemple_atelier">

Supposons qu'il y ait 20 boules - noires ou blanches - dans une urne.

Pour estimer leur nombre respectif, vous tirez un échantillon de quatre boules et constatez que trois sont noires et une est blanche.

Une **généralisation inductive** serait qu'il y a 15 boules noires et cinq boules blanches dans l'urne.

</div>

La reliabilité de la généralisation inductive dépend de trois facteurs:

1. du nombre de personnes dans le groupe d'échantillonnage;
2. du nombre de personnes dans la population;
3. du degré de représentativité de l'échantillon par rapport à la population (ce qui peut être réalisé en prenant un échantillon aléatoire).

Plus la taille de l'échantillon est importante par rapport à la population et plus l'échantillon est représentatif de la population, plus la généralisation est forte.

La généralisation hâtive et l'échantillon biaisé sont des erreurs de généralisation.

##### Généralisation statistique <a href = "https://fr.wikipedia.org/wiki/Syllogisme_statistique" target = "_blank"> <img src = "../fichiers/icons/chain.png"  height = "15" width="15"/> </a>

Une généralisation statistique est un type d'argument inductif dans lequel une conclusion concernant une population est déduite à l'aide d'un échantillon statistiquement représentatif.

<div class="theorem_atelier">
Sur un échantillon aléatoire non négligeable de votants interrogés, 66 % soutiennent la mesure Z.

Par conséquent, environ 66 % des électeurs soutiennent la mesure Z. 
</div>


La mesure est très fiable, avec une marge d'erreur bien définie, à condition que l'échantillon soit important et aléatoire. Elle est facilement quantifiable.


##### Généralisation anecdotique <a href = "https://fr.wikipedia.org/wiki/Preuve_anecdotique" target = "_blank"> <img src = "../fichiers/icons/chain.png"  height = "15" width="15"/> </a>

Une généralisation anecdotique est un type d'argument inductif dans lequel une conclusion sur une population est déduite à l'aide d'un échantillon non statistique.En d'autres termes, la généralisation est basée sur des preuves anecdotiques.

<div class="exemple_atelier">
Jusqu'à présent, cette année, l'équipe de football de mon fils a remporté 6 matchs sur 10.

Par conséquent, à la fin de la saison, ils auront gagné environ 60 % des matchs.
</div>


Cette déduction est moins fiable (et donc plus susceptible de commettre l'erreur de la généralisation hâtive) qu'une généralisation statistique, d'abord parce que les événements de l'échantillon ne sont pas aléatoires, et ensuite parce qu'elle n'est pas réductible à l'expression mathématique.

D'un point de vue statistique, il n'existe tout simplement aucun moyen de connaître, de mesurer et de calculer les circonstances affectant les performances qui se produiront à l'avenir.

D'un point de vue philosophique, l'argument repose sur le présupposé que le fonctionnement des événements futurs sera le reflet du passé. En d'autres termes, il prend pour acquis l'uniformité de la nature, un principe non prouvé qui ne peut être dérivé des données empiriques elles-mêmes. Les arguments qui présupposent tacitement cette uniformité sont parfois qualifiés de "humiens", du nom du philosophe qui a été le premier à les soumettre à un examen philosophique. <a href = "https://www.routledge.com/Introduction-to-Logic/Gensler/p/book/9781138910591" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "10" width="10"/> </a>

#### La prédiction <a href = "https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=5b5825da8bc88727b8418d3c392f03f0acd1f6be" target = "_blank"> <img src = "../fichiers/icons/chain.png"  height = "10" width="10"/> </a>

Une prédiction inductive tire une conclusion sur un cas futur, actuel ou passé à partir d'un échantillon d'autres cas. Tout comme la généralisation inductive, une prédiction inductive s'appuie sur un ensemble de données composé de cas spécifiques d'un phénomène.
 
Mais au lieu de conclure par une déclaration générale, la prédiction inductive conclut par une déclaration spécifique sur la probabilité qu'une instance unique ait un attribut partagé par les autres instances.

<div class="theorem_atelier">
La proportion Q des membres observés du groupe G a l'attribut A.

Par conséquent, il existe une probabilité P que d'autres membres du groupe G aient l'attribut A lors de leur prochaine observation.
</div>


##### Syllogisme statistique <a href = "https://fr.wikipedia.org/wiki/Syllogisme_statistique" target = "_blank"> <img src = "../fichiers/icons/chain.png"  height = "15" width="15"/> </a>

Un syllogisme statistique part d'une généralisation sur un groupe pour aboutir à une conclusion sur un individu.

<div class="theorem_atelier">
La proportion Q des individus connus du groupe G possède l'attribut A.

L'individu I est un autre membre de G.

Par conséquent, il existe une probabilité correspondant à P que I possède l'attribut A.
</div>

<div class="exemple_atelier">
90 % des diplômés de l'école préparatoire Excelsior poursuivent leurs études à l'université.

Bob est diplômé de l'école préparatoire Excelsior.

Par conséquent, Bob ira à l'université.
</div>

Même si l'on ne peut pas être sûr que Bob ira à l'université, nous pouvons être pleinement assurés de la probabilité exacte de ce résultat (en l'absence d'autres informations).

En règle générale, le raisonnement inductif cherche à formuler une probabilité.

##### Inférence analogique <a href = "https://en.wikipedia.org/wiki/Argument_from_analogy" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>

Le processus d'inférence analogique consiste à noter les propriétés communes de deux ou plusieurs choses et à en déduire qu'elles partagent également d'autres propriétés :

<div class="theorem_atelier">
P et Q sont similaires en ce qui concerne les propriétés a, b et c.

L'objet P a été observé comme ayant une autre propriété x.

Par conséquent, Q possède probablement aussi la propriété x.
</div>


Le raisonnement analogique est très fréquent dans le sens commun, la science, la philosophie, le droit et les sciences humaines.

<div class="exemple_atelier">
Les minéraux A et B sont tous deux des roches ignées contenant souvent des veines de quartz et se trouvent le plus souvent en Amérique du Sud dans des zones d'ancienne activité volcanique.

Le minéral A est également une pierre tendre convenant à la fabrication de bijoux.

Par conséquent, le minéral B est probablement une pierre tendre adaptée à la fabrication de bijoux.
</div>

#### Quelle est l’utilité de la démarche inductive dans le domaine académique ?

La démarche inductive est utile lorsque vous étudiez un sujet ou un phénomène connu. La démarche inductive permet aussi de :

- cerner son sujet de recherche ;
- définir les attentes de son enquête ;
- trouver les causes du phénomène étudié ;
- donner une explication à des effets observés ;
- Etablir une conclusion apportant des explications scientifiques sur le sujet ou sur le phénomène étudié.

---

## Le raisonnement déductif <a href = "https://fr.wikipedia.org/wiki/Raisonnement_d%C3%A9ductif" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>

Le **raisonnement déductif** , aussi appelée **déduction logique** est une méthode de travail scientifique. Elle a pour but d’expliquer un phénomène en partant d’un sujet ou d’une hypothèse sur un phénomène. On ne part donc pas de faits observables (méthode inductive).

Les recherches entamées pour répondre à cette hypothèse permettent aussi au chercheur de développer d’autres hypothèses.

La confirmation ou la non-confirmation des hypothèses de travail doit permettre de trouver une explication au sujet ou au phénomène sur lequel se porte la recherche.

![Schema Deductif](images/schema_deductif.png)

*Extrait de “[Le raisonnement en sciences de l’ingénieur”, JL Prensier, T. Zenard, 2006, ENS Cachan](https://eduscol.education.fr/sti/sites/eduscol.education.fr.sti/files/ressources/pedagogiques/6217/6217-le-raisonnement-en-sciences-de-lingenieur-ens.pdf)"*

> “La déduction sert aux économistes comme elle sert aux astronomes, aux physiciens, etc.
 D’un certain principe A, on déduit les conséquences B, C, D etc. ; celles-ci se trouvent vérifiées par l’observation ou par l’expérience, et c’est cette vérification qui rend probable A ; ce n’est pas le moins du monde A qui prouve B, C, D”. (Vilfred, 1984).

#### Règles de déduction <a href = "https://en.wikipedia.org/wiki/Rule_of_inference" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>

##### Définitions

Le raisonnement déductif s'effectue généralement en appliquant des règles d'inférence.

Une règle d'inférence est une manière ou un schéma permettant de tirer une conclusion à partir d'un ensemble de prémisses.

Une règle d'inférence est valide si, appliquée à des prémisses vraies, la conclusion ne peut être fausse.

Un argument particulier est valide s'il suit une règle d'inférence valide.

Les arguments déductifs qui ne suivent pas une règle d'inférence valide sont appelés des sophismes formels.


##### Principales règles d'inférence <a href = "https://en.wikipedia.org/wiki/Rule_of_inference" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>


###### Modus ponens <a href = "https://fr.wikipedia.org/wiki/Modus_ponens" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>

Le **modus ponens** (également connu sous le nom d'**affirmation de l'antécédent** ou de **loi du détachement**) est la principale règle d'inférence déductive. Elle a pour forme :

<div class="theorem_atelier">

P → Q   (la première prémisse est une proposition conditionnelle)

P   (la deuxième prémisse est l'antécédent)

Q   (la conclusion déduite est le conséquent)

</div>

Voici un exemple d'argument utilisant le modus ponens:

<div class="exemple_atelier">
Si il pleut, alors il y a des nuages dans le ciel.

Il pleut.

Ainsi, il y a des nuages dans le ciel.

</div>

###### Modus tollens <a href = "https://fr.wikipedia.org/wiki/Modus_tollens" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "10" width="10"/> </a>

Le **modus tollens** (également connu sous le nom de **loi de la contraposée** ) est une règle d'inférence déductive.

Contrairement au modus ponens, le raisonnement avec le modus tollens va dans la direction opposée à celle du conditionnel. L'expression générale du modus tollens est la suivante :

<div class="theorem_atelier">

P → Q   (la première prémisse est une proposition conditionnelle)

¬ Q   (la deuxième prémisse est la négation du conséquent)

¬ P   (la conclusion déduite est la négation de l'antécédent)

</div>


Voici un exemple d'argument utilisant le modus tollens:

<div class="exemple_atelier">

Si il pleut, alors il y a des nuages dans le ciel.

Il n'y a pas de nuages dans le ciel.

Ainsi, il ne pleut pas.

</div>

###### Syllogisme Hypothétique <a href = "https://en.wikipedia.org/wiki/Hypothetical_syllogism" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "10" width="10"/> </a>

Un **syllogisme hypothétique** est une inférence qui prend deux énoncés conditionnels et forme une conclusion en combinant l'hypothèse d'un énoncé avec la conclusion d'un autre. En voici la forme générale :

<div class="theorem_atelier">

P → Q   (la première prémisse est une proposition conditionnelle)

Q → R   (la deuxième prémisse est une proposition conditionnelle)

P → R   (la conclusion déduite est une proposition conditionnelle)

</div>

Voici un exemple d'argument utilisant le syllogisme hypothétique:

<div class="exemple_atelier">
S'il y avait eu un orage, il aurait plu.

S'il avait plu, les choses auraient été mouillées.

Ainsi, s'il y avait eu un orage, les choses auraient été mouillées.

</div>

---

## Le raisonnement par abduction <a href = "https://fr.wikipedia.org/wiki/Abduction_(logique)" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>

Un **raisonnement par abduction** consiste, en observant un ou plusieurs faits **A1**, **A2**, **A3**, etc; dont on connaît une cause possible et la plus vraisemblable **B**, à prendre **B** comme hypothèse pour affirmer qu'elle est probablement la cause de **A1**, **A2**, **A3**, etc. en particulier.

<div class="exemple_atelier">

#### Exemple

*S'il pleut alors je prends mon parapluie. J'ai pris mon parapluie donc il pleut.*

Ce raisonnement est un raisonnement abductif. En effet, on a observé que lorsque il pleut, on prend son parapluie. Il est donc **plausible** de penser qu'il pleut. Cependant, on ne peut pas dire qu'il pleut **par déduction** car on ne peut pas déduire de la prise de son parapluie qu'il pleut.

On peut simplement dire qu'il pleut **probablement** par abduction.

</div>

---

## Résumé des 3 démarches

La démarche inductive est une méthode de travail scientifique qui consiste à partir de faits observables pour en déduire une hypothèse.

La démarche déductive est une méthode de travail scientifique qui consiste à partir d’une hypothèse pour en déduire des faits observables.

La démarche abductive est une méthode de travail scientifique qui consiste à déterminer la cause d’un phénomène à partir de lois générales.

| Induction        | Déduction         | Abduction |
|:-------------|:------------------|:------|
| Trouver une loi par généralisation d'observations / de corrélations particulières          | Déduire d'une conclusion à partir d’une loi/proposition considérée comme vraie| Poser la plausibilité d’une hypothèse à partir d’une loi / de constats |
| Socrate est un homme; Socrate est mortel; **Tous les hommes sont mortels** | Socrate est un homme; Tous les hommes sont mortels; **Socrate est mortel** | Tous les hommes sont mortels; Socrate est mortel; **Socrate est (plausiblement) un homme** |

---

## Démarche hypothético-déductive <a href = "https://fr.wikipedia.org/wiki/M%C3%A9thode_hypoth%C3%A9tico-d%C3%A9ductive" target = "_blank"> <img src = "../fichiers/icons/chain.png" height = "15" width="15"/> </a>

En sciences expérimentales, la **démarche hypothético-déductive** est une façon de conduire la recherche qui associe **théorie** et **pratique** selon une séquence définie.

#### 1. Observation / questionnement

On observe un fait. On se pose une question sur ce fait. 
La question doit pouvoir être répondue par l’intermédiaire d’observations concrètes.

#### 2. Élaboration d’une/des hypothèse(s)

Une hypothèse est une réponse imaginaire, mais basée sur un raisonnement intelligent, pour la question posée. Une hypothèse doit être testable, vérifiable, potentiellement réfutable.

#### 3. Déduction de prédictions

On prédit ce qui devrait arriver sous certaines conditions si l’hypothèse est valide.

#### 4. Définition d’expériences pour pouvoir tester les prédictions

On prédit ce qui devrait arriver sous certaines conditions si l’hypothèse est valide. On conçoit une/des expériences dont les conditions peuvent être créées de toute pièce en laboratoire ou sur le terrain ou en profitant des conditions créées par la nature (variations naturelles de l’environnement).

#### 5. Validation ou invalidation des prédictions (et donc hypothèses) par l’expérience

On exécute l’expérience, on recueille les données.
Si la prédiction ne se réalise pas, l’hypothèse est rejetée.
Si la prédiction se réalise, l’hypothèse est supportée (du moins pour l’instant).

#### 6. Communication des résultats à la communauté scientifique (voire à la société en général)

On publie les résultats dans des revues scientifiques, on les présente à des conférences, on les diffuse sur les réseaux sociaux, etc.
