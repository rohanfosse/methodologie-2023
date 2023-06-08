# UE Methodologie Scientifique - 2022/2023

Ce dépôt contient les ressources pour l'UE Méthodologie Scientifique de l'Université de Bordeaux. Il a été mis en place par [Alexandre Blanché](https://www.labri.fr/perso/ablanche/), [Guy Melançon](https://www.labri.fr/profil/Melancon_ID1094543956) et [Rohan Fossé](https://rohanfosse.com).

Le GitHub et la page Web ont été créée par [Rohan Fossé](https://rohanfosse.com).

## Site Web

Le cours de méthodologie présenté ici est disponible en ligne à l'adresse suivante: [https://rohanfosse.com/methodologie](https://rohanfosse.com/methodologie)

Il est cependant possible d'héberger ce site sur votre propre serveur ou votre propre GitHub Pages.

### Héberger le site sur votre propre serveur

Le site Web est disponible dans le dossier `SiteWeb` de ce dépot.

Pour héberger le site Web sur votre propre serveur, vous aurez besoin d'un serveur Web (Apache, Nginx, etc.) et d'un interpréteur PHP (PHP 7.4 ou supérieur).

#### Installation

Le site Web a été créé avec [Jekyll](https://jekyllrb.com/), un outil qui permet de générer des sites Web statiques à partir de fichiers Markdown.

Pour installer Jekyll, vous aurez besoin de [Ruby](https://www.ruby-lang.org/en/) et de [RubyGems](https://rubygems.org/).

Pour installer Jekyll, exécutez la commande suivante, après avoir installé Ruby et RubyGems:

```bash
gem install jekyll bundler
```

#### Générer le site Web

Pour générer le site Web, exécutez la commande suivante dans le dossier `SiteWeb`:

```bash
jekyll build
```

Le site Web sera généré dans le dossier `_site`.

#### Héberger le site Web

Pour héberger le site Web, copiez le contenu du dossier `_site` dans le dossier de votre serveur Web.

### Héberger le site sur GitHub Pages

Le site Web est disponible dans le dossier `SiteWeb` de ce dépot. Il est possible de l'héberger sur GitHub Pages.

#### Mise en place de GitHub Pages

Pour cela, il faudra faire un fork de ce dépôt, puis activer GitHub Pages dans les paramètres du dépôt. L'onglet "Pages" des paramètres du dépôt permet de choisir la branche et le dossier à utiliser pour héberger le site Web.

Attention cependant, votre dépôt sera public. Si vous souhaitez que votre dépôt soit privé, il faudra utiliser un compte GitHub payant.

Après avoir activé GitHub Pages, le site Web sera disponible à l'adresse suivante: https://votre-nom-d-utilisateur-github.github.io/methodologie-2023/ (en remplaçant `votre-nom-d-utilisateur-github` par votre nom d'utilisateur GitHub).

L'URL du site Web peut être personnalisée en ajoutant un nom de domaine personnalisé. Pour cela, il faudra ajouter un fichier `CNAME` à la racine du dépôt, contenant le nom de domaine personnalisé. Il faudra ensuite configurer le nom de domaine personnalisé dans les paramètres du dépôt.

#### Mise à jour du site Web

Le site Web sera automatiquement mis à jour à chaque fois que vous ferez un `git push` sur votre dépôt.

#### Changer le thème du site Web

Le thème du site Web peut être changé en modifiant la variable `theme` dans le fichier `_config.yml`. La liste des thèmes disponibles est disponible à l'adresse suivante: https://pages.github.com/themes/

## Licence

Le contenu de ce dépôt est disponible sous la licence [MIT](https://opensource.org/licenses/MIT). Cela signifie simplement que vous pouvez utiliser, modifier et redistribuer le contenu de ce dépôt, à condition de citer les auteurs originaux et de conserver la même licence.

