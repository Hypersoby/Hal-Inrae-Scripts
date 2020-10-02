<p align="center">
  <img alt="ColorFull Logo" src="https://i.imgur.com/maSGINc.png">
  <br>
  
<p align="center">
  Elégant, intuitif et plus puissant que jamais pour une navigation plus rapide et plus facile. 
   <br>
   Seulement disponible pour portail hal inrae. Les scripts ne sont pas incompatibles avec les sites de collection, vous devrez alors les désactiver.
   <br>
  <a href="https://github.com/Hypersoby/Hal-Inrae-Scripts/issues/new?template=rapport-de-bug.md">Rapporter un bug</a>
  ·
  <a href="https://github.com/Hypersoby/Hal-Inrae-Scripts/issues/new?template=demande-de-fonctionnalit-.md">Demande de fonctionnalité</a>
  ·
  <a href="mailto:christopher.lallemant@inrae.fr?subject=Mail from our Website">Contactez moi</a>
  

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![Generic badge](https://img.shields.io/badge/Version-1.0-<COLOR>.svg)](https://shields.io/) [![CSS](https://img.shields.io/badge/Language-CSS-red.svg)](https://shields.io/)
  
## Prise en charge du navigateur

![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png) |![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png)
--- | --- | --- | --- | --- |
Chrome ✔ | Firefox ✔ | Opera ✔ | Safari ✔ |  IE 8 et plus ❌ |
  
# Sommaire
  - [Comment faire](#Comment-faire-?)
  - [Contenu](#Contenu) 
    - [Note de patch](#Note-de-patch)
    - [Mise à jour](#Mise-à-jour) 
  - [Aperçu](#Aperçu)
  - [Contribution et Développement](#Contribution-et-Développement)


# Comment faire ?

1. Installer [Stylus pour Firefox](https://addons.mozilla.org/fr/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/) ou [Cascadea pour Safari](https://cascadea.app/). Aucun support n'est disponible pour les navigateurs Internet Explorer et Edge.

1. Cliquez sur le lien qui correspond à votre navigateur puis, installer le script en cliquant sur le bouton`ajouter/installer`.
![ajout](https://i.imgur.com/8LEySe4.png)
2. Une icône représentant un `S` s'ajoutera en haut de votre navigateur dans la barre de navigation. 
![Firefox](https://i.imgur.com/28AipgL.png)

*Si vous utilisez `Chrome` cliquer sur l'icône en forme de `puzzle` et ensuite épinglez `Stylus` dans votre barre de navigation.*
![Chrome](https://i.imgur.com/a6PzHSY.png)

3. Pour télécharger et installer le ou les scripts, il vous suffira de cliquer sur les liens `Script Principal` / `Script Mode Nuit` / `Script Orange` ci-dessous puis de cliquer sur installer sur le panneau de gauche. /!\ Ensuite vous pourrez fermer l'onglet /!\

Important : Il faut forcément installer Principal pour que le reste fonctionne.

Liens des Téléchargements. 

Pour le script Principal : ![Script Principal](https://github.com/Hypersoby/Hal-Inrae-Scripts/raw/master/Principal.user.css)

Pour le Mode Nuit : ![Script Mode Nuit](https://github.com/Hypersoby/Hal-Inrae-Scripts/raw/master/Nuit.user.css)

Pour le Orange : ![Script Orange](https://github.com/Hypersoby/Hal-Inrae-Scripts/raw/master/Orange.user.css)
 
4. Une fois installé, rendez-vous sur le site `Hal Inrae` puis vous allez cliquer sur l'icône `S` de l'extension Stylus.
![Hal](https://i.imgur.com/6Wsf1nH.png)
5. Cliquez sur la `case ☐` correspondant au(x) script(s) que vous voudrez activer pour l'appliquer sur le site. 

/!\ Attention /!\ Le script principal doit être tout le temps activé. Pour changer de `Style de couleur` vous devrez ainsi cocher soit entre `Mode nuit` soit `Orange` en faisant bien attention de ne pas désactiver le `Principal`.

# Contenu

1. `Harmonisation` du site pour une navigation plus facile.
```
- Alignement d'éléments sur les boutons, taille des cadres/zonés de recherche, etc.
- Tous les boutons possèdent désormais la même charte graphique.
- Des éléments ont été modifié pour bien indiquer leurs fonctions 
(ajout/annuler/supprimer/valider) par un code couleur Vert et rouge
- La taille des zones de recherche est revue à la hausse pour une meilleure visibilité
- La page Mes dépôts est entièrement modifiée pour la clarté entre les éléments
- La page dépôts est plus condensée pour une meilleure lecture de l'information
- Une charte de couleurs est mise en place pour les menus
- Les champs concernant les affiliations, auteurs, ainsi que les menus déroulants et sous menu déroulant sur
la page dépôt sont plus grands et plus larges
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


4. `Style de couleur` pour varier les nuances.
```
- Un mode nuit. Sobre et reposant, il saura vous faire passer du côté obscur en un claquement de doigts.
- Orange. D'une belle teinte orange et d'un mode dont les couleurs sont plus appuyées pour une modernité inégalable.
```

## Note de patch

![Voir les logs de mise à jours](http:www.exemple.com) -> 404 pour le moment

## Mise à jour

1. Pour voir si un script est à jour, rendez-vous dans l'extension Stylus en cliquant sur `S` puis sur `Gestion`

![S](https://i.imgur.com/lmYa50c.png)
![Gestion](https://i.imgur.com/TKGpDNo.png)

2. Sur le panneau de droite qui contient les scripts, rendez-vous sur la ligne du script puis cliquez sur l'icône `⟲` pour vérifier si une mise à jour est possible. 

![Update](https://i.imgur.com/CEODpLJ.png)

# Aperçu 

<p align="center">
| Principal | Orange | Mode Nuit |
<br>
  
![Aperçu](https://i.imgur.com/2XUcOQC.png)
![Aperçu4](https://i.imgur.com/Jd2i6fQ.png)
![Aperçu2](https://i.imgur.com/LpmhLVM.png)
![Aperçu3](https://i.imgur.com/lwiIxNW.png)



# Contribution et Développement

Si vous voulez contribuer à améliorer et déceler des bugs ou me contacter, veuillez voir ci-dessus les éléments prévus à cet effet

Créer et développer par <a href="mailto:christopherlallemant@inrae.fr?subject=Mail from our Website">Christopher Lallemant</a>

Remerciement spécial:

<a href="mailto:pascal.lallemant@inrae.fr?subject=Mail from our Website">Pascal Lallemant</a> qui à contribuer aux versions Alpha et Beta et à la détection de bugs. Et à
<a href="mailto:vincent.rappeneau@inrae.fr?subject=Mail from our Website">Vincent Rappeneau</a> pour la mise en place de ce projet
