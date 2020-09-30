<p align="center">
  <img alt="ColorFull Logo" src="https://i.imgur.com/maSGINc.png">
  <br>
  
<p align="center">
  Elégant, intuitif et plus puissant que jamais pour une navigation plus rapide et plus facile.
  <br>
  <a href="https://github.com/Hypersoby/Hal-Inrae-Scripts/issues/new?template=rapport-de-bug.md">Rapporter un bug</a>
  ·
  <a href="https://github.com/Hypersoby/Hal-Inrae-Scripts/issues/new?template=demande-de-fonctionnalit-.md">Demande de fonctionnalité</a>
  ·
  <a href="mailto:christopher.lallemant@inrae.fr?subject=Mail from our Website">Contactez moi</a>
  
## Prise en charge du navigateur

![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
IE 8 et plus ✖ | Prêt ✔ | Prêt ✔ | Prêt✔ | Prêt ✔ |  
  
# Sommaire
  - [Installation](#Installation)
    - [Pré-requis](#Pré-requis)
    - [Comment faire](#Comment-faire)
  - [Contenu](#Contenu) 
    - [Note de patch](#Note-de-patch)
    - [Mise à jour](#Mise-à-jour) 
  
  - [Aperçu](#Aperçu)
  
  
  - [Contribution et Développement](#Contribution-et-Développement)
  - [Notes](#notes)


# Installation

## Pré-requis

1. Installer [Stylus pour Firefox](https://addons.mozilla.org/fr/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/) ou [Cascadea pour Safari](https://cascadea.app/). Aucun support n'est disponible pour les navigateurs Internet Explorer et Edge.
2. Installer le script `principal` qui servira de `HUB` pour les extensions de couleur.
3. Installer les scripts `Mode nuit` et `Orange` pour profiter d'une variante de couleur.

[![Base](https://i.imgur.com/otg0kBH.png)](https://github.com/Hypersoby/Hal-Inrae-Scripts/raw/master/Principal.user.css)
[![Nuit](https://i.imgur.com/zKLsWz5.png)](https://github.com/Hypersoby/Hal-Inrae-Scripts/raw/master/Nuit.user.css)
[![Orange](https://i.imgur.com/kpYaQ5K.png)](https://github.com/Hypersoby/Hal-Inrae-Scripts/raw/master/Orange.user.css)

### Comment faire

1. Ouvrez le lien pour qui correspond à votre navigateur puis, installer le script en cliquant sur le bouton`ajouter`.
2. Une icône représentant un `S` s'ajoutera en haut de votre navigateur dans la barre de navigation. Si vous utilisez `Chrome` veuillez cliquer sur l'icône en forme de `puzzle` et ensuite vous devrez pouvoir épingler `Stylus` dans votre barre de navigation.
3. Pour télécharger le ou les scripts, il vous suffira de cliquer sur les boutons ci-dessus.
4. Une fois installé, rendez-vous sur le site `Hal Inrae` puis vous allez cliquer sur l'icône `S` de l'extension Stylus.
5. Cliquez sur la `case ☐` correspondant au(x) script(s) que vous voudrez activer pour l'appliquer sur le site.

# Contenu

## Note-de-patch

1. `Harmonisation` du site pour une navigation plus facile.
```
- Alignement d'éléments sur les boutons, taille des cadres/zonés de recherche, etc.
- Tous les boutons possèdent la même charte graphique désormais.
- Des éléments ont été modifié pour bien indiquer leurs fonctions 
(ajout/annuler/supprimer/valider) par un code couleur Vert et rouge
- La taille des zones de recherche est revue à la hausse pour une meilleure visibilité
- La page Mes dépôts est entièrement modifiée pour la clarté entre les éléments
- La page dépôts est plus condensée pour une meilleure lecture de l'information
- La taille des tableaux est aussi condensée pour l'harmonisation 
du reste du site, ainsi qu'une clarté générale.
- Une charte de couleurs est mise en place pour les menus
- Les champs concernant les affiliations, auteurs, ainsi que les menus et sous menu sur
la page dépôt sont revus à la hausse.
- La bannière principale sur l'accueil est modifié pour l'harmonisation du site
```
2. `Correction` de bug visuel nécessaire au bon fonctionnement du site
```
- Texte blanc non visible sur la sélection des affiliations.
- Cadre des affiliations qui se chevauchent lors de la modification/visualisation.
- Correction de faux bouton qui laisse croire qu'ils sont cliquables.
```
<p align="center">
  <img alt="TextBlanc" src="https://i.imgur.com/rKENzmx.png">
  <br>

3. `Ajout` d'éléments pour une meilleur expérience de navigation.
```
- Une bannière visible en haut de l'écran quand il y a un potentiel double lors d'un dépôt.
- Des logo/symboles supplémentaires dans les cadres de validations, d'erreurs, de doubles.
- Des animations sur ce même logo.
- Certains boutons qui n'avaient aucun style par rapport à la charte graphique sont revus au goût du jour.
- Animations de transition entre les couleurs lorsque le curseur passe sur des éléments (bouton, menu).
```

<p align="center">
  <img alt="alert" src="https://i.imgur.com/jvPKFDV.gif">
  <br>


4. `Chroma` sur le style pour la charte graphique.
```
- Un mode nuit. Sobre et reposant, il saura vous faires vite oubliez le style classique du portail Hal-Inrae.
- Orange. D'une belle teinte orange et d'un mode dont les couleurs sont plus appuyées pour une modernité inégalable.
```

## Mise à jour

1. Pour voir si un script est à jour, rendez-vous dans l'extension Stylus en cliquant sur `S` puis sur `Gestion`
2. Sur le panneau de droite qui contient les scripts, rendez-vous sur la ligne du script puis cliquez sur l'icône `⟲` pour vérifier si une mise à jour est possible. 

# Aperçu

![Aperçu](https://i.imgur.com/2XUcOQC.png)
![Aperçu2](https://i.imgur.com/LpmhLVM.png)
![Aperçu3](https://i.imgur.com/lwiIxNW.png)
![Aperçu4](https://i.imgur.com/Jd2i6fQ.png)

# Contribution et Développement

Si vous voulez contribuer à améliorer et déceler des bugs ou me contacter, veuillez voir ci-dessus les éléments prévus à cet effet

Créer et développer par <a href="mailto:christopherlallemant@inrae.fr?subject=Mail from our Website">Christopher Lallemant</a>

Remerciement spécial:

<a href="mailto:pascal.lallemant@inrae.fr?subject=Mail from our Website">Pascal Lallemant</a> qui à contribuer aux versions Alpha et Beta et à la détection de bugs. Et à
<a href="mailto:vincent.rappeneau@inrae.fr?subject=Mail from our Website">Vincent Rappeneau</a> pour la mise en place de ce projet


# Note

License GPLv3 -> Libre d'utilisation et de modification.
