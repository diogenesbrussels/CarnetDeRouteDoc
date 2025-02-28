## Introduction

Ce document décrit l'application Carnet de Route 3.0 et ses concepts clés.

## Description

L'application Carnet de Route 3.0 (CdR 3.0) est conçue pour aider les travailleurs de rue et les travailleurs sociaux à enregistrer et à gérer leurs activités auprès des habitants dans le cadre de divers projets. Elle vise à centraliser les données et à les rendre accessibles aux utilisateurs en fonction de leurs rôles et missions.

Voici les principaux objectifs de l'application:

- Suivi des interactions
- Organisation des activités de soutien
- Interface mobile-first
- Sécurité et centralisation des données
- Personnalisation par organisation
- Gestion des accès basés sur les rôles

L'application offre une vue d'ensemble de l'activité des travailleurs, en suivant les interactions et en organisant les activités de soutien, tout en assurant que toutes les données pertinentes soient accessibles aux utilisateurs en fonction de leurs rôles.

## Concepts clés

Cette section décrit les différents concepts qui composent l'application, il ne s'agit pas d'une liste exhaustive. Merci de vous reporter à la documentation d'aide pour l'utilisation de l'application ou la documentation de développement pour obtenir plus de détails sur le volet technique.

### Habitants

Dans l'application, un habitant représente une personne qui sont rencontrées ou reçoivent de l'aide dans le cadre de différents projets.
Voici quelques points clés concernant le concept d'habitant :

- Les habitants sont au cœur du système, car les utilisateurs suivent les interactions ou les activités qui leur sont liées.
- Chaque habitant peut être associé à un ou plusieurs projets.
- Le profil de l'habitant stocke des informations essentielles telles que les informations personnelles, l'historique des activités et les informations spécifiques liés au(x) projet(s).

En résumé, l'habitant est la pierre angulaire de l'application, permettant de suivre et de gérer les interactions liées à chaque individu. Des modules peuvent être ajoutés pour étendre les profils des habitants avec des champs ou des fonctionnalités spécialisées. Par exemple, il peut y avoir un module pour suivre les activités liées à la santé ou au logement.

### Projets

Dans l'application, un projet est un cadre dans lequel les utilisateurs organisent les activités.
Voici les aspects clés concernant le concept de projet :

- Les projets impliquent des travailleurs qui participent au projet.
- Ils contiennent des activités réalisées pour, avec ou sans les habitants par les utilisateurs.
- Un projet peut inclure plusieurs habitants et offre une vue d'ensemble de toutes les activités associées, ce qui facilite le suivi des résultats au niveau du projet.
- Le suivi par projet permet enregistrement de toutes les activités, qu'elles impliquent ou non des habitants.
- L'interface, les options disponibles sont personnalisés en fonction des projets.

Un projet sert de cadre pour organiser les activités et les interactions avec les habitants, permettant aux utilisateurs de gérer et de suivre le parcours. Les projets permettent de suivre un résumé et l'historique des activités et personnalise l'interface et les modules.

### Modules

### Activités

### Utilisateurs

### Ressources

L'application embarque plusieurs type de ressources qui sont utilisées couramment :

- Liste des lieux, espaces et rues (uniquement Bruxelles actuellement)
- Liste des organisations du secteur social (via social.brussels)
- Liste des pays et nationalités

Ces ressources peuvent être modifiées et adaptées en fonction du besoin des utilisateurs.

### Vie privée

Le respect de la vie privée, du secret professionnel et du règlement général sur la protection des données (RGPD) fait partie intégrante de la conception de l'application. Une combinaison de bonnes pratiques, d'outils techniques et de concepts permettent de minimiser les risques liés à la gestion de données personnelles :

- Accès par authenfication et sur base de rôles
- Accès aux données segmenté en fonction de l'habitant, l'utilisateur, les projets et modules
- Enregistrement des activités des utilisateurs
- Gestion des fichiers déposés par les utilisateurs
- Système de masquage ou de minimisation des données personnelles
- Extraction de données anonymisées ou pseudo-anonymisées pour les analyses statistiques
- Système de génération de tableau des données utilisées par l'application permettant de faciliter la conformité RGPD

### Interface

L'interface utilisateur de l'application est conçue avec une approche "mobile-first", visant à assurer une utilisation facile et rapide. Cette conception est particulièrement adaptée aux travailleurs de rue, en tenant compte des environnements difficiles et des ressources limitées.

Bien que l'application soit pensée pour les appareils mobiles, elle est également accessible sur ordinateur via un navigateur web. Cette adaptation permet aux utilisateurs de bénéficier d'une expérience cohérente sur les deux plateformes, tout en offrant des fonctionnalités supplémentaires pour la gestion de projet et la création de rapports sur la version bureau.

Une attention particulière est accordée à la réduction du nombre de clics et d'interactions nécessaires pour rechercher, visualiser les informations et en ajouter/modifier.

### Personnalisation

### Autres

#### Notes

#### Demandes

### Reporting et rapports d'activités

## Aperçu / Démonstration

La version 3.0 est en cours de développement est n'est pas encore disponible. Vous pouvez prendre contact avec nous pour obtenir des informations et un aperçu de notre application en version 2.0.

## Contact

Pour toute demande ou questions relative à l'application Carnet de Route, merci de prendre contact via <it@diogenes.brussels>
