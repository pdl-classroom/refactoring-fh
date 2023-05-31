# Refactoring

## Introduction

Un bon refactoring est un refactoring qui ne change pas le comportement du code.
De plus, un bon refactoring est effectué en plusieurs étapes, chacune d'entre elles étant validée par des tests unitaires.
Dans ce laboratoire, vous allez appliquer des refactorings un par un sur un code existant en vous assurant que son comportement ne change pas et que les tests unitaires passent toujours.

## Travail à réaliser

Les objectifs de ce laboratoire sont de:

1. Configurer une action github pour exécuter les tests unitaires à chaque push.
2. Configurer sonar cloud pour analyser le code à chaque push et corriger les éventuels problèmes qui apparaitraient au cours ce laboratoire.
3. Appliquer les refactorings un par un en committant chaque changement:
   - Identifier un "bad smell";
   - Créer une branche pour corriger le "bad smell";
   - Corriger le "bad smell";
   - Vérifier que les tests unitaires passent toujours;
   - Ajouter un test unitaire (si cela est justifié);
   - Committer votre changement et ajouter un message justifiant le changement ("bad smell" identifié, description du changement, code impacté, etc.);
   - Pousser votre changement sur github;
   - Vérifier que l'action github a bien été exécutée et que les tests unitaires passent;
   - Merger votre branche dans la branche `main`;
   - Recommencer jusqu'à ce qu'il n'y ait plus de "bad smell" à corriger.

Nous nous attendons à ce vous effectuiez une dizaine de commits pour ce laboratoire.
