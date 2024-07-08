# School-Management-System-MADRASTY
![school](https://github.com/youssefreg/School-Management-System-MADRASTY/assets/112189559/9d2ca45f-4dd0-4441-920a-14d68342788a)



Bienvenue sur le projet "School-Management-System-MADRASTY" ! Ce projet est une application de gestion scolaire développée avec Spring Boot pour le backend et Angular pour le frontend.

## Table des matières

- [Introduction](#introduction)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Contribuer](#contribuer)
- [Licence](#licence)

## Introduction

"**School-Management-System-MADRASTY**" est une plateforme de gestion scolaire conçue pour faciliter la gestion des établissements scolaires. Ce projet utilise **Spring Boot** pour la partie serveur et **Angular** pour la partie cliente.

## Fonctionnalités

- Gestion des étudiants (inscription, mise à jour, suppression)
- Gestion des enseignants
- Gestion des cours et des emplois du temps
- Gestion des notes et des évaluations
- Interface d'administration pour gérer les utilisateurs et les permissions

## Prérequis

Assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 12+)
- [Angular CLI](https://angular.io/cli)
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) (version 11+)
- [Maven](https://maven.apache.org/) (version 3.6+)
- [MySQL](https://www.mysql.com/) (ou toute autre base de données relationnelle)

## Installation

### Backend (Spring Boot)

1. Clonez le dépôt :

    ```bash
    git clone https://github.com/votre_nom_d_utilisateur/School-Management-System-MADRASTY.git
    ```

2. Accédez au répertoire backend :

    ```bash
    cd School-Management-System-MADRASTY/backend
    ```

3. Configurez la base de données MySQL dans `src/main/resources/application.properties` :

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/votre_base_de_données
    spring.datasource.username=votre_nom_d_utilisateur
    spring.datasource.password=votre_mot_de_passe
    ```

4. Compilez et démarrez le serveur :

    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

### Frontend (Angular)

1. Accédez au répertoire frontend :

    ```bash
    cd ../frontend
    ```

2. Installez les dépendances :

    ```bash
    npm install
    ```

3. Démarrez l'application Angular :

    ```bash
    ng serve
    ```

4. Ouvrez votre navigateur et accédez à `http://localhost:4200`.

## Utilisation

1. Accédez à l'interface utilisateur via votre navigateur à `http://localhost:4200`.
2. Inscrivez-vous ou connectez-vous pour commencer à utiliser l'application.
3. Utilisez les différentes fonctionnalités pour gérer les étudiants, les enseignants, les cours, etc.

## Contribuer

Les contributions sont les bienvenues ! Veuillez suivre les étapes suivantes pour contribuer :

1. Forkez le projet.
2. Créez votre branche de fonctionnalité (`git checkout -b fonctionnalité/AmazingFeature`).
3. Commitez vos modifications (`git commit -m 'Ajoutez une fonctionnalité incroyable'`).
4. Poussez à la branche (`git push origin fonctionnalité/AmazingFeature`).
5. Ouvrez une Pull Request.

## Licence

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.
