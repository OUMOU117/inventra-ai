# INVENTRA AI — Prototype V0.1

## Présentation

INVENTRA AI est un prototype Python consacré à la conception
logicielle, à la génération de solutions et à la vérification
de prototypes.

Le projet explore un processus comprenant l'analyse d'un problème,
la proposition de solutions, leur comparaison, la conception d'une
architecture et la génération d'un prototype vérifiable.

**Statut : prototype expérimental.**

Cette version utilise principalement des règles programmées.
Elle ne possède pas encore de modèle d'IA générative intégré.

## Fonctionnalités actuelles

- Analyse structurée d'un problème logiciel.
- Proposition de plusieurs approches possibles.
- Comparaison des solutions à partir de critères explicites.
- Création d'une architecture technique préliminaire.
- Génération d'un prototype Python d'analyse de fichiers CSV.
- Vérification du prototype à l'aide de tests automatiques.

## Architecture

Le prototype s'organise autour des composants suivants :

1. Problem Analyzer : analyse le problème.
2. Idea Engine : propose différentes solutions.
3. Solution Evaluator : compare les propositions.
4. Architecture Designer : prépare un plan technique.
5. Prototype Builder : génère le code du prototype.
6. Test Engine : vérifie les résultats lorsque les tests sont disponibles.
7. Improvement Engine : prépare les améliorations à partir des erreurs détectées.
8. Project Manager : organise les informations du projet.

Les capacités réellement disponibles dépendent de l'implémentation
présente dans la version V0.1.

## Prototype CSV

Le prototype généré vise à analyser la qualité d'un fichier CSV.

Il peut notamment rechercher :
- les cellules manquantes ;
- les lignes dupliquées ;
- le nombre de lignes et de colonnes ;
- certaines erreurs de format.

Il peut produire un rapport structuré sur la qualité des données.

## Technologies

- Python
- Google Colab
- Bibliothèques standard de Python
- Tests automatisés

Aucune clé API n'est nécessaire pour le noyau initial.

## Utilisation

1. Ouvrir le notebook INVENTRA AI dans Google Colab.
2. Exécuter les cellules dans l'ordre.
3. Examiner les solutions proposées.
4. Générer le prototype disponible.
5. Exécuter les tests et examiner les résultats.

## Limites

Cette version ne constitue pas encore une IA générative autonome.

Les propositions sont produites à partir de règles et de critères
programmés. Les évaluations ne prouvent pas qu'une solution est
nouvelle ou supérieure aux technologies existantes.

La génération de code reste limitée au prototype prévu dans cette
version. Les tests ne garantissent pas l'absence de tous les bugs.

## Évolutions envisagées

- Intégration éventuelle d'un modèle d'IA.
- Génération de prototypes logiciels plus variés.
- Amélioration des évaluations.
- Tests plus complets.
- Comparaison des versions successives.
- Création d'une interface utilisateur.

Chaque évolution devra être testée avant d'être considérée comme stable.

## Version

- Projet : INVENTRA AI
- Version : 0.1
- Statut : prototype expérimental
- Environnement initial : Google Colab
