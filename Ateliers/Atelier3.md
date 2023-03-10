<p style="text-align:left;">
    [Retour au sommaire](../README.md)
</p>

# Atelier3 - Communication et interprétation des données

## Interprétation des données

### Le Quartet d'Anscombe <a href="Anscombe, Francis J. (1973) Graphs in statistical analysis. American Statistician, 27, 17–21" target="_blank"><img src="images/chain.png" width="15" height="15" /></a>

Le quartet d'Anscombe est un ensemble de quatre jeux de données statistiques qui ont été créés par Francis Anscombe en 1973. Il a été utilisé pour illustrer l'importance de la visualisation des données et de la description statistique des données.

Les quatre jeux de données ont la même moyenne, la même [variance](https://fr.wikipedia.org/wiki/Variance_(math%C3%A9matiques)), la même [corrélation](https://fr.wikipedia.org/wiki/Corr%C3%A9lation_(statistiques)) et la même [régression linéaire](https://fr.wikipedia.org/wiki/R%C3%A9gression_lin%C3%A9aire).

Chaque ensemble de données contient 11 points. Les quatres ensembles présentent ces propriétés statistiques:

| Propriété | Valeur |
|-----------|--------|
| Moyenne de x | 9 |
| Moyenne de y | 7.5 |
| Variance de x | 11 |
| Variance de y | 4.125 |
| Corrélation de x et y | 0.816 |
| Equation de la droite de régression linéaire | y = 3 + 0.5 x |
| Somme des carrés des erreurs relativement à la moyenne | 110,0 |
| - | - |

Voici les quatres ensembles de données:

![Quartet d'Anscombe](images/Anscombe.svg)
*Ces quatre ensembles de données possèdent les mêmes propriétés statistiques simples, mais leurs représentations graphiques sont très différentes.*
*Source: [Wikipedia](https://en.wikipedia.org/wiki/Anscombe%27s_quartet)*

* Le premier graphique en nuage de points (*scatterplot* en anglais) (en haut à gauche) semble être une relation linéaire simple, correspondant à deux variables corrélées où y pourrait être modélisé comme une gaussienne dont la moyenne dépendrait linéairement de x.

* Le second graphique (en haut à droite) ; bien qu'une relation entre les deux variables soit évidente, elle n'est pas linéaire et le [coefficient de corrélation de Pearson](http://www.biostat.ulg.ac.be/pages/Site_r/corr_pearson.html) n'est pas pertinent. Une régression plus générale et le coefficient de détermination correspondant seraient plus appropriés.

* Dans le troisième graphique (en bas à gauche), la relation modélisée est linéaire, mais devrait avoir une ligne de régression différente (une régression robuste aurait été nécessaire). La régression calculée est contrebalancée par une valeur aberrante qui exerce une influence suffisante pour abaisser le coefficient de corrélation de 1 à 0,816.

* Enfin, le quatrième graphique (en bas à droite) montre un exemple où un point à fort effet de levier suffit à produire un coefficient de corrélation élevé, même si les autres points de données n'indiquent aucune relation entre les variables.

Malgré des représentations, on peut voit danss le tableau de données ci-dessous que les données sont très similaires.


| x | y | x | y | x | y | x | y |
|---|---|---|---|---|---|---|---|
| 10.0 | 8.04 | 10.0 | 9.14 | 10.0 | 7.46 | 8.0 | 6.58 |
| 8.0 | 6.95 | 8.0 | 8.14 | 8.0 | 6.77 | 8.0 | 5.76 |
| 13.0 | 7.58 | 13.0 | 8.74 | 13.0 | 12.74 | 8.0 | 7.71 |
| 9.0 | 8.81 | 9.0 | 8.77 | 9.0 | 7.11 | 8.0 | 8.84 |
| 11.0 | 8.33 | 11.0 | 9.26 | 11.0 | 7.81 | 8.0 | 8.47 |
| 14.0 | 9.96 | 14.0 | 8.10 | 14.0 | 8.84 | 8.0 | 7.04 |
| 6.0 | 7.24 | 6.0 | 6.13 | 6.0 | 6.08 | 8.0 | 5.25 |
| 4.0 | 4.26 | 4.0 | 3.10 | 4.0 | 5.39 | 19.0 | 12.50 |
| 12.0 | 10.84 | 12.0 | 9.13 | 12.0 | 8.15 | 8.0 | 5.56 |
| 7.0 | 4.82 | 7.0 | 7.26 | 7.0 | 6.42 | 8.0 | 7.91 |
| 5.0 | 5.68 | 5.0 | 4.74 | 5.0 | 5.73 | 8.0 | 6.89 |


Le quartet est encore souvent utilisé pour illustrer l'importance d'examiner un ensemble de données sous forme de graphique avant de commencer à les analyser en fonction d'un type de relation particulier, et l'inadéquation des propriétés statistiques de base pour décrire des ensembles de données réalistes.

---

## La pré-attention <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6513732/" target="_blank"><img src="images/chain.png" width="15" height="15" /></a>

La pré-attention est la capacité de l'oeil à se concentrer sur un élément spécifique d'une image. Elle est utilisée pour sélectionner un élément spécifique d'une image, et pour déterminer la position de cet élément dans l'image.

L'applet Javascript ci-dessous vous permettra d'expérimenter les trois différentes recherches de détection de cibles : couleur, forme et conjonction.

Comme dans les figures ci-dessus, la cible est un cercle rouge. Les éléments d'arrière-plan sont soit des cercles bleus (lors des recherches de couleur), soit des carrés rouges (lors des recherches de forme), soit des cercles bleus et des carrés rouges (lors des recherches de conjonction). Le curseur "Durée d'exposition" vous permet de contrôler la durée d'affichage de chaque écran (de 100 à 1000 msec).

Le curseur "Elements per Display :" vous permet de contrôler le nombre total d'éléments dans chaque affichage (d'un minimum de 10 à un maximum de 70). Le curseur "Nombre d'essais" vous permet de contrôler le nombre d'affichages à effectuer.
