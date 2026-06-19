# Détection de clusters infectieux, démo pédagogique

Petite démo interactive accompagnant la présentation du métier de médecin hygiéniste à une stagiaire de seconde.

## À quoi ça sert

Montrer concrètement comment on repère le début d'une épidémie hospitalière à partir de données de laboratoire, en faisant tourner un vrai script Python directement dans le navigateur.

## Lancer la démo

Ouvre simplement [https://jetpod.github.io/detection-clusters-demo/](https://jetpod.github.io/detection-clusters-demo/).

Tu peux :

- Modifier le seuil de cas qui déclenche une alerte (3 par défaut)
- Modifier la fenêtre de temps (48 h par défaut)
- Voir en direct quelles alertes sont générées sur le jeu de données factice

## Données

Toutes les données utilisées sont **inventées**. Aucun patient réel n'est concerné. Le jeu de données contient 11 résultats de laboratoire fictifs avec deux clusters volontairement glissés :

- Klebsiella pneumoniae en Réanimation (3 cas en 48 h)
- Clostridioides difficile en Médecine (4 cas en 48 h)

## Technologie

- HTML + CSS + JavaScript
- Python exécuté dans le navigateur via [Pyodide](https://pyodide.org)
- Aucun serveur, aucune donnée envoyée nulle part

## Auteur

Dr Jean-Etienne PODIK, médecin de santé publique, hygiéniste hospitalier.
