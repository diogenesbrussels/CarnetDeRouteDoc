## Introduction

Ce document décrit l'application Carnet de Route 3.0 et ses concepts clés.

## Description

L'application Carnet de Route 3.0 (CdR 3.0) est conçue pour aider les travailleurs de rue et les travailleurs sociaux à enregistrer et à gérer leurs activités auprès des habitants dans le cadre de divers projets. Elle vise à centraliser les données et à les rendre accessibles aux utilisateurs en fonction de leurs rôles et missions.

Voici les principaux objectifs de l'application :

- Suivi des interactions
- Organisation des activités de soutien
- Interface mobile-first
- Sécurité et centralisation des données
- Personnalisation par organisation
- Gestion des accès basée sur les rôles

L'application offre une vue d'ensemble de l'activité des travailleurs, en suivant les interactions et en organisant les activités de soutien, tout en assurant que toutes les données pertinentes soient accessibles aux utilisateurs en fonction de leurs rôles.

## Concepts clés

Cette section décrit les différents concepts qui composent l'application. Il ne s'agit pas d'une liste exhaustive. Merci de vous reporter à la documentation d'aide pour l'utilisation de l'application ou à la documentation de développement pour obtenir plus de détails sur le volet technique.

### Habitants

Dans l'application, un habitant représente une personne qui est rencontrée ou qui reçoit de l'aide dans le cadre de différents projets.
Voici quelques points clés concernant le concept d'habitant :

- Les habitants sont au cœur du système, car les utilisateurs suivent les interactions ou les activités qui leur sont liées.
- Chaque habitant peut être associé à un ou plusieurs projets.
- Le profil de l'habitant stocke des informations essentielles telles que les informations personnelles, l'historique des activités et les informations spécifiques liées au(x) projet(s).

En résumé, l'habitant est la pierre angulaire de l'application, permettant de suivre et de gérer les interactions liées à chaque individu. Des modules peuvent être ajoutés pour étendre les profils des habitants avec des champs ou des fonctionnalités spécialisées. Par exemple, il peut y avoir un module pour suivre les activités liées à la santé ou au logement.

### Projets

Dans l'application, un projet est un cadre dans lequel les utilisateurs organisent les activités.
Voici les aspects clés concernant le concept de projet :

- Les projets impliquent des travailleurs qui y participent.
- Ils contiennent des activités réalisées pour, avec ou sans les habitants par les utilisateurs.
- Un projet peut inclure plusieurs habitants et offre une vue d'ensemble de toutes les activités associées, ce qui facilite le suivi des résultats au niveau du projet.
- Le suivi par projet permet l'enregistrement de toutes les activités, qu'elles impliquent ou non des habitants.
- L'interface et les options disponibles sont personnalisées en fonction des projets.

Un projet sert de cadre pour organiser les activités et les interactions avec les habitants, permettant aux utilisateurs de gérer et de suivre le parcours. Les projets permettent de suivre un résumé et l'historique des activités et personnalisent l'interface et les modules.

### Modules

Le fonctionnement sous forme de modules permet au Carnet de Route de s'adapter en fonction de l'usage de chaque organisation et de chaque projet au sein d'une organisation.
Les modules peuvent être attachés aux habitants, aux activités ou à l'application pour étendre les possibilités comme, par exemple : un module Housing First lié à l'habitant, un module lié aux activités pour collecter certaines informations spécifiques ou encore à l'application pour permettre une visualisation des données.
Les modules sont activés en fonction des projets de l'utilisateur, ce qui permet de simplifier l'interface et de séparer ou partager des informations entre utilisateurs de différents projets.

### Activités

Les activités permettent d'enregistrer les interactions avec ou pour les habitants, mais également d'autres types d'activités telles que des observations, concertations ou activités de groupes.
Elles contiennent notamment les informations suivantes : date de l'activité, habitant(s) lié(s), lieu(x), organisation(s), projet, notes...
Le formulaire permettant les ajouts et modifications d'activités est conçu de manière à être le plus aisé possible à compléter : il s'adapte en fonction de l'utilisateur, de ses projets, du type d'activité choisi et propose des suggestions liées à l'utilisateur, mais également à l'habitant concerné.

### Utilisateurs

Les utilisateurs sont les personnes qui accèdent à l'application. Un rôle leur est attribué (**Basic**, **Power** ou **Admin**).
Tous les utilisateurs font partie d'un ou plusieurs projets qui déterminent les modules qui leur seront accessibles. Ils peuvent personnaliser la langue d'affichage et leur interface en fonction de leurs besoins.
Les utilisateurs **Power** peuvent gérer les utilisateurs de leurs projets et accéder aux panneaux de contrôle du projet.
Les utilisateurs **Admin** peuvent gérer l'application de manière globale et modifier les paramètres de l'application.

### Ressources

L'application embarque plusieurs types de ressources qui sont utilisées couramment :

- Liste des lieux, espaces et rues (uniquement Bruxelles actuellement)
- Liste des organisations du secteur social (via social.brussels)
- Liste des pays et nationalités

Ces ressources peuvent être modifiées et adaptées en fonction des besoins des utilisateurs.

### Vie privée

Le respect de la vie privée, du secret professionnel et du règlement général sur la protection des données (RGPD) fait partie intégrante de la conception de l'application. Une combinaison de bonnes pratiques, d'outils techniques et de concepts permet de minimiser les risques liés à la gestion de données personnelles :

- Accès par authentification et sur base de rôles
- Accès aux données segmenté en fonction de l'habitant, l'utilisateur, les projets et modules
- Enregistrement des activités des utilisateurs
- Gestion des fichiers déposés par les utilisateurs
- Système de masquage ou de minimisation des données personnelles
- Extraction de données anonymisées ou pseudo-anonymisées pour les analyses statistiques
- Système de génération de tableau des données utilisées par l'application, permettant de faciliter la conformité RGPD

### Interface

L'interface utilisateur de l'application est conçue avec une approche "mobile-first", visant à assurer une utilisation facile et rapide. Cette conception est particulièrement adaptée aux travailleurs de rue, en tenant compte des environnements difficiles et des ressources limitées.

Bien que l'application soit pensée pour les appareils mobiles, elle est également accessible sur ordinateur via un navigateur web. Cette adaptation permet aux utilisateurs de bénéficier d'une expérience cohérente sur les deux plateformes, tout en offrant des fonctionnalités supplémentaires pour la gestion de projet et la création de rapports sur la version bureau.

Une attention particulière est accordée à la réduction du nombre de clics et d'interactions nécessaires pour rechercher, visualiser les informations et en ajouter/modifier.

### Personnalisation

L'application est personnalisable en fonction de l'organisation. Ainsi, chaque instance (copie) peut adapter les paramètres suivants :

- Nom et logo
- Langues disponibles
- Fichiers de traduction (permettant une adaptation au vocabulaire métier de l'organisation)
- Activation de modules

### Autres

#### Notes

Les notes peuvent être déposées par les utilisateurs et partagées avec d'autres travailleurs appartenant au même projet. Elles peuvent être liées à des activités, des habitants, des organisations...

#### Demandes

Un système d'enregistrement des demandes (appels téléphoniques, emails) permet de gérer et d'effectuer le suivi nécessaire. Il permet d'utiliser les autres ressources (habitants, organisations, lieux, ...) pour aider les travailleurs à y apporter le suivi approprié.

### Reporting et rapports d'activités

## Aperçu / Démonstration

La version 3.0 est en cours de développement et n'est pas encore disponible. Vous pouvez prendre contact avec nous pour obtenir des informations et un aperçu de notre application en version 2.0.

## Contact

Pour toute demande ou question relative à l'application Carnet de Route, merci de prendre contact via <it@diogenes.brussels>
