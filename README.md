# Laravel Book Review

Une application de gestion des critiques de livres, développée dans le cadre de l'apprentissage du cours **Master Laravel and PHP: Build 5 Real-World Projects! Learn PHP From Scratch!** sur Udemy.

## Description

Cette application permet d'afficher une liste de livres avec leurs notes moyennes et leurs critiques associées. Les utilisateurs peuvent explorer, filtrer les livres par popularité ou notes, et ajouter des critiques avec des évaluations pour chaque livre.

### Fonctionnalités principales

- **Affichage des livres :**
  - Liste des livres disponibles avec titre, auteur, et moyenne des notes.
  - Système de pagination pour naviguer entre les livres.

- **Critiques :**
  - Ajouter des critiques pour chaque livre avec une évaluation (notation par étoiles).
  - Voir toutes les critiques associées à un livre.

- **Filtrage :**
  - Trier les livres par :
    - Derniers ajouts.
    - Livres les plus populaires (dernier mois ou 6 derniers mois).
    - Livres les mieux notés (dernier mois ou 6 derniers mois).
  - Recherche de livres par titre.

---

## Technologies utilisées

- **Framework :** Laravel
- **Base de données :** MySQL
- **Frontend :** Blade Templates avec Tailwind CSS
- **Gestion des packages :** Composer


---

## Prérequis

- PHP >= 8.1
- Composer
- MySQL

---

## Installation

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/laravel-book-review.git
   cd laravel-book-review
