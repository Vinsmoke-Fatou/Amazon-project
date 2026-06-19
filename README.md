# E-Commerce Simulation Architecture

Ce projet propose une modélisation simplifiée d'une plateforme e-commerce. Il sert d'exercice pour structurer des données complexes et implémenter les fonctionnalités de base nécessaires à une application de vente en ligne.

## Fonctionnalités principales

- Gestion de catalogue : Ajout, affichage et recherche de produits.
- Panier d'achat : Ajout d'articles, gestion des quantités et calcul des totaux.
- Processus de commande : Simulation de la validation du panier et finalisation.

## Architecture du projet

Amazon-project/
├── src/
│   ├── models/       # Modèles de données (Produit, Panier, Commande)
│   ├── services/     # Logique métier et gestion des données
│   └── Main.java     # Point d'entrée de l'application
└── data/             # Fichiers de configuration ou données initiales

## Installation

1. Cloner le dépôt :
   git clone https://github.com/Vinsmoke-Fatou/Amazon-project.git
   cd Amazon-project

2. Compilation :
   Utilisez un IDE (IntelliJ, Eclipse) ou compilez manuellement via le terminal :
   javac -d bin src/**/*.java

3. Exécution :
   java -cp bin Main

## Technologies utilisées

- Java
- Concepts de programmation orientée objet (POO)
- Gestion des collections

---
Projet académique réalisé pour démontrer les capacités de conception d'un système logiciel complet.
