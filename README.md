# Booki #
 
 Ce projet correspond au projet 2 de la formation développeur Web de OPENCLASSROOMS.


## Table des Matières

- [Introduction](#introduction)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Structure du Projet](#structure-du-projet)
- [Auteurs](#auteurs)
- [Exigences fonctionnelles](#exigences-fonctionnelles)
- [Outils et contraintes techniques](#outils-et-contraintes-techniques)


## Introduction 

L'objectif ici est d'intégrer l'interface du site Booki avec du code HTML et CSS à partir des maquettes disponibles sur [Figma](https://www.figma.com/file/aen32jonHhD7JnIEL2b3sE/Projet-2-FR---Booki?node-id=349%3A1)


## Installation

- Prérequis système : Ce e-portfolio est réalisé sous HTML et CSS.
- Installation des dépendances : Cloner ce repository et lancer `yarn install` pour installer les dépendances.


## Utilisation

- Utiliser  `yarn start` pour lancer l'application.
- Ouvrir [http://localhost:3000](http://localhost:3000) pour le  voir dans le navigateur.


## Structure du Projet

- assets/         # Dossier contenant les images
- css/            # Dossier contenant style.css
- index.html      # Point d'entrée de l'application

## Auteurs

- [GUIEBA Kévin](https://github.com/Kguie/)


## Exigences fonctionnelles 

- Le site doit être réalisé en desktop first.

- Un formulaire de recherche doit être utilisé.

- Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre).

- Les hébergements peuvent être filtrés par thématique, comme le budget ou l’ambiance avec des filtres qui changent d'apparence au survol

- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

## Outils et contraintes techniques 

- Trois maquettes ont été réalisées:

    ● Desktop :>=992 px pour les écrans d’ordinateurs ;

    ● Tablette: >=768 px pour les tablettes ;

    ● Mobile: tout ce qui est en dessous de 768 pour les téléphones portables.

- Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer une largeur maximum de 1 400 px.
- Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first),puis les tablettes et enfin les téléphones. 
    L’utilisation des Media Queries nous permettra de réaliser l’intégration pour les différents supports.
- Les icônes proviennent de la bibliothèque Font Awesome.
- Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
- La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.
- Il est recommandé d'utiliser Flexbox    

- Le code doit être valide aux validateurs W3C HTML et CSS.
- Le code HTML ne doit pas contenir de propriété CSS.
- Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la loupe).
- Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser le nom de l’élément lui-même.
- Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont identiques du point de vue de la mise en forme, alors utiliser une seule et même
    classe CSS, et non pas 4.

- La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.

- Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS 
- Aucun autre langage ne doit être utilisé 