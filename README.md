# Nom du projet : Boîte à effets personnels sécurisée

## Introduction

Ce projet est la réalisation d'un **écosystème complet** pour une boîte à effets personnels physique, développée dans le cadre de mon année en **Terminale Sciences de l'Ingénieur (SI)**. Il a pour objectif de lier un système physique à des applications, en mettant en œuvre une architecture client-serveur et la programmation multi-plateforme.

## Fonctionnalités

Cet écosystème est composé de :

* **Une boîte physique** : Équipée de capteurs et d'un mécanisme de verrouillage contrôlé par une carte Arduino.
* **Un serveur central (C#)** : Gérant le stockage des données et la communication avec l'ensemble des applications.
* **Une application PC (Windows 11 en C#)** : Une interface utilisateur pour la gestion détaillée de la boîte (contrôle des accès, historique des événements, reset des mots de passe).
* **Une application mobile (C#)** : Une application pour une gestion simple et sécurisée à distance (fermeture, notifications).

## Architecture technique

L'ensemble de la partie logicielle est développée en **C#**.

* **Communication :** Le serveur gère les requêtes des applications PC et mobiles. La communication entre le serveur et le microcontrôleur Arduino est assurée elle aussi par le serveur.
* **Gestion des versions :** Le projet est hébergé sur GitHub pour un suivi rigoureux des versions et une collaboration facilitée.

## Technologies utilisées

* **Langage :** C#
* **Frameworks & environnements :**
    * Windows Forms (pour l'application PC)
    * .NET
* **Matériel & outils :**
    * Carte Arduino
    * Visual Studio 2022
    * GitHub

## Comment démarrer (Guide d'installation)

* **Prérequis :**
    * Visual Studio 2022
    * .NET Desktop Runtime
* **Étapes :**
    1.  Cloner ce dépôt : `git clone https://github.com/Meolys/Boite-a-effets-personnels-securisee.git`
    2.  Ouvrir la solution `à définir` dans Visual Studio.
    3.  Lancer le projet `à définir` en premier, puis l'application de votre choix.

## À propos

Ce projet a été réalisé par Méolys (sous pseudonyme afin de ne pas dévoiler mon identité sur internet) en Terminale Sciences de l'Ingénieur.

## Licence

Ce projet est sous licence MIT. Pour plus de détails, consultez le fichier `LICENSE`.
