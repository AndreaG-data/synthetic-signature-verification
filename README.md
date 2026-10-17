# Synthetic Signature Generation for Online Biometric Verification

## 🇬🇧 English

### Project Overview

This research project was conducted during an international internship at **TecnoCampus Mataró-Maresme, Spain**, as part of my Mathematical Engineering and Data Science studies at Polytech Clermont.

The objective was to investigate whether synthetic handwritten signatures generated using deep learning could improve biometric verification systems by reducing the number of genuine signatures required during enrollment.

### Methodology

The project involved:

- Preprocessing online handwritten signatures from the MCYT database.
- Developing an autoencoder to generate synthetic signatures.
- Evaluating signature similarity using Dynamic Time Warping (DTW).
- Extracting statistical features from signature trajectories.
- Implementing Random Forest and diagonal Linear Discriminant Analysis (diagLDA) classifiers.
- Comparing enrollment configurations using genuine and synthetic signatures.

### Key Results

- Achieved **99.03% identification accuracy** using DTW with five genuine reference signatures.
- **52.10% of synthetic signatures** were accepted as genuine under the selected DTW verification threshold.
- Synthetic signatures preserved important biometric characteristics but did not provide sufficient variability to improve enrollment performance.

### Technologies and Methods

Python · Deep Learning · Autoencoders · Machine Learning · Dynamic Time Warping · Random Forest · diagLDA · Statistical Analysis

### Project Files

- **Jupyter Notebook:** Experiments, evaluation metrics and visualizations.
- **Internship Report:** Complete methodology, results and discussion.

---

## 🇫🇷 Français

### Présentation du projet

Ce projet de recherche a été réalisé lors d'un stage international au **TecnoCampus Mataró-Maresme, en Espagne**, dans le cadre de ma formation en Génie Mathématique et Data Science à Polytech Clermont.

L'objectif était d'étudier si des signatures manuscrites synthétiques générées par Deep Learning pouvaient améliorer les systèmes de vérification biométrique en réduisant le nombre de signatures authentiques nécessaires lors de l'enrôlement.

### Méthodologie

Le projet comprenait :

- Le prétraitement des signatures manuscrites dynamiques de la base MCYT.
- Le développement d'un autoencodeur pour générer des signatures synthétiques.
- L'évaluation de la similarité des signatures avec Dynamic Time Warping (DTW).
- L'extraction de caractéristiques statistiques des trajectoires.
- L'implémentation de classifieurs Random Forest et diagLDA.
- La comparaison de différentes configurations d'enrôlement utilisant des signatures authentiques et synthétiques.

### Principaux résultats

- **99,03 % de taux d'identification** avec DTW et cinq signatures authentiques de référence.
- **52,10 % des signatures synthétiques** acceptées comme authentiques au seuil de vérification DTW sélectionné.
- Les signatures générées présentaient une similarité biométrique importante avec les signatures réelles, mais n'apportaient pas suffisamment de variabilité pour améliorer les performances d'enrôlement.

### Technologies et méthodes

Python · Deep Learning · Autoencodeurs · Machine Learning · DTW · Random Forest · diagLDA · Analyse statistique

### Fichiers du projet

- **Notebook Jupyter :** Expériences, métriques d'évaluation et visualisations.
- **Rapport de stage :** Méthodologie complète, résultats et discussion.
