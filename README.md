# Etude-de-Sant-Publique
# 🌍 Projet 3 – Analyse de la disponibilité alimentaire mondiale

Ce projet de data science vise à explorer la **disponibilité alimentaire** par pays et par origine (végétale ou animale), à partir de données ouvertes de la FAO, en les combinant avec des données de population.

---

## 📊 Objectif

- Fusionner les données alimentaires d’origine **animale** et **végétale**
- Croiser avec les données de **population mondiale**
- Calculer la disponibilité alimentaire par habitant
- Réaliser des **analyses ciblées par pays et produits alimentaires**
- Répondre à des **questions sur les stocks, pertes, productions, etc.**

---

## 📁 Données utilisées

- `fr_animaux.csv` – données alimentaires d’origine animale
- `fr_vegetaux.csv` – données alimentaires d’origine végétale
- `fr_population.csv` – données de population mondiale

---

## 🧪 Traitements réalisés

- Nettoyage des colonnes et filtres utiles
- Fusion et ajout d'une colonne `origine` (animal / végétal)
- Agrégation par zone, année, produit, origine, et type d’élément
- Croisement avec la population (`merge`) pour faire des calculs par habitant
- Calcul de la **population mondiale**
- Extraction d’exemples par pays (ex: Arménie)

---

## 🧠 Quelques analyses abordées

- Quelle est la disponibilité alimentaire en kcal/personne/jour ?
- Quelle est la part des aliments d'origine végétale vs animale ?
- Quelle est la contribution des céréales comme le blé ?
- Quels sont les produits les plus transformés ou perdus ?
- Quels pays présentent des carences ou surplus alimentaires ?

---

## 📦 Technologies utilisées

- Python 3
- Pandas
- Numpy
- Matplotlib
- Jupyter Notebook

---

## ▶️ Lancer le projet

1. Ouvrir `Projet3-python.ipynb` dans Jupyter Notebook
2. S'assurer d'avoir les fichiers `.csv` dans le même dossier
3. Lancer les cellules pas à pas

---

## 📄 Auteurs & Sources

- Données : FAOSTAT (Organisation des Nations unies pour l’alimentation et l’agriculture)
- Réalisé dans le cadre d’un projet Python d’analyse exploratoire

---

