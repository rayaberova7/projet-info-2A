---
title: "TP1 Projet Informatique 2A - Introduction"
author: "Raya Berova"
date: "08/29/2025"
date-format: "D MMMM YYYY"
format:
  revealjs:
    theme: solarized
    slide-number: true
    transition: slide
    controls: true
    chalkboard:
      theme: whiteboard
    lang: fr-FR
    slide-tone: false
    ascii: true
css: ../custom.css
---

# Sujet du TP1

- Durée : 3 heures
- Objectif : se familiariser avec les outils modernes de développement
  - Onyxia (environnement cloud)
  - PostgreSQL (gestion de bases de données)
  - DBeaver (interface graphique pour bases de données)
  - VSCode (éditeur de code)
  - Git (gestion de version)

---

# Organisation du TP

1. Présentation des outils
2. Installation / accès aux environnements
3. Exercices pratiques
4. Questions & échanges

---

# Onyxia

- Plateforme cloud pour lancer des environnements R, Python, etc. (comme Google Cloud)
- Avantages :
  - Pas d'installation locale
  - Accès à des ressources importantes (CPU, RAM...)
  - Environnement reproductible pour tous
- Démonstration 🔍 https://datalab.sspcloud.fr/ (création de compte avec firstname.lastname@eleve.ensai.fr)

---

# VSCode

- Éditeur de code universel
- Extensions utiles pour :
  - Python / R / SQL
  - Git intégré
  - Notebooks
- Démonstration 🔍 

---

# Git

- Gestion de versions (historique)
- Travailler à plusieurs sur un projet
- Synchroniser son travail avec une plateforme distante
-> Indispensable pour le travail collaboratif et reproductible 

---

## Git en pratique

- Créer un compte GitHub
- Créer un dépot Git
- Démonstration 🔍 

---

## Concepts clés

- `git clone <url depot git>` → récupérer le code
- `git add <chemin de fichier>` → préparer les modifications
- `git commit -m <message>` → sauvegarder les changements localement
- `git push` → envoyer sur le dépôt distant
- `git pull` → récupérer les nouveautés du dépôt distant

- Démonstration 🔍 

---

# Branches

Chacun travaille de son côté puis le code est mis en commun

- `git branch <nom de la branche>` → créer la branche en copiant la main
- `git checkout <nom de la branche>` → se mettre sur la branche pour développer
- `git push -u origin <nom de la branche>` → envoyer la branche sur le dépôt distant
- `git checkout main` + `git pull` + `git merge --strategy-option=theirs <nom de la branche>` → fusionner la main avec la branche

- Démonstration 🔍

---

# Outils utiles

- README.md
- .gitignore
- Commandes terminal `cd` et `ls`
- Fichiers .md pour les notes
- Issues git

---

# PostgreSQL

- Système de gestion de base de données relationnelle
- Stocker, organiser et interroger des données
- Concepts clés :
  - Tables, lignes, colonnes
  - SQL : SELECT, INSERT, UPDATE, DELETE

---

# DBeaver

- Interface graphique pour PostgreSQL et autres SGBD
- Avantages :
  - Visualiser rapidement les bases
  - Exécuter des requêtes SQL facilement
  - Import / export de données

---

# Questions ?

---
