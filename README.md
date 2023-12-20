# Résumé des Exercices de Base de Données

Ce README fournit un résumé des compétences et connaissances acquises à travers une série d'exercices pratiques sur les bases de données relationnelles.

## Objectifs d'Apprentissage

Les exercices ont couvert plusieurs aspects importants de la manipulation et de la gestion des bases de données SQL, y compris :

- **Création et Modification de Tables :**
  - Comprendre la syntaxe pour la création de nouvelles tables.
  - Savoir comment ajouter, supprimer ou modifier des colonnes dans des tables existantes.
  - Maîtriser les commandes `CREATE TABLE`, `ALTER TABLE`.

- **Gestion des Relations entre Tables :**
  - Apprendre à établir des relations un-à-plusieurs et plusieurs-à-plusieurs.
  - Utiliser des clés étrangères pour lier des tables.
  - Créer des tables de liaison pour gérer des relations complexes.

- **Requêtes SQL Avancées :**
  - Écrire des requêtes pour interroger, filtrer et extraire des données de la base.
  - Utiliser des jointures pour combiner des données de plusieurs tables.

- **Bonnes Pratiques :**
  - Renforcer les bonnes pratiques dans la conception de bases de données.
  - Comprendre l'importance de la normalisation des données.
  - Pratiquer une écriture de requêtes SQL claire et efficace.

## Exemples de Commandes SQL

Voici quelques exemples de commandes SQL utilisées et pratiquées :

- Création de table :
  ```sql
  CREATE TABLE film (
      id INT PRIMARY KEY,
      nom VARCHAR(255) NOT NULL
  );
