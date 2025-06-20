# Projet d'Analyse des Performances RH en Python

## Contexte du Projet
Ce projet vise à analyser un dataset RH pour identifier les facteurs clés influençant la performance des employés et proposer des recommandations data-driven.

## Compétences et Outils Utilisés
- **Langage :** Python
- **Bibliothèques :** `pandas` (manipulation et nettoyage de données), `matplotlib` et `seaborn` (visualisation de données)
- **Méthodologies :** Statistiques descriptives, Analyse Exploratoire de Données (EDA), Détection d'outliers (méthode 1.5 * IQR)

## Analyse et Résultats Clés
### 1. Préparation des Données
* Gestion des valeurs manquantes (`ManagerID`, `DateofTermination`).
* Conversion de types (`PerformanceScore` en catégoriel ordonné).

### 2. Aperçu des Performances
* La majorité des employés sont "Fully Meets" (78%), mais 10% nécessitent une amélioration ("PIP" ou "Needs Improvement").

### 3. Facteurs d'Amélioration Identifiés
* **Engagement :** Forte corrélation positive entre le score d'engagement et la performance.
* **Ponctualité :** Les retards (`DaysLateLast30`) sont un indicateur clé de performance faible.
* **Localisation des problèmes :** Les départements "Sales" et "Production", et les postes "Network Engineer", "IT Manager - Infra", "Production Technician I/II" sont des points chauds de basse performance.
* **Projets Spéciaux :** Les employés peu performants ont moins accès aux projets spéciaux.

## Recommandations
* Mettre en place des programmes ciblés pour améliorer l'engagement.
* Développer des initiatives pour améliorer la ponctualité.
* Mener des audits spécifiques dans les départements et postes à risque.
* Offrir des opportunités de projets spéciaux aux employés en développement.

## Comment exécuter le projet (si pertinent)
1. Cloner ce dépôt : `git clone https://github.com/TonUtilisateurGitHub/TonDépôt.git`
2. Installer les dépendances : `pip install pandas matplotlib seaborn`
3. Ouvrir le notebook Jupyter : `jupyter notebook ton_notebook.ipynb`

## Auteur
Koneh Mouhamadou Bako