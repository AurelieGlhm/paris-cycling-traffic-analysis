# Analyse du trafic cycliste à Paris

## Contexte
Ce projet a été réalisé dans le cadre de ma formation en **Analytics Engineering** chez DataScientest.  
Il vise à analyser et modéliser le trafic cycliste à Paris à partir des données issues de capteurs urbains.

---

## Objectif
- Analyser les variations du trafic cycliste à Paris  
- Identifier les facteurs influençant la fréquentation (temps, météo, localisation, calendrier)  
- Construire un modèle de prédiction du trafic  
- Développer une application interactive pour explorer les données  

---

## Données
- Données de comptage des vélos (capteurs urbains)  
- Données calendaires (jours fériés, vacances scolaires)  
- Données contextuelles utilisées pour enrichir l’analyse  

> Les fichiers volumineux (datasets et modèles) ne sont pas versionnés afin de garantir un repository léger et reproductible.

---

## Structure du projet

```
paris-cycling-traffic-analysis/
├── data/
├── src/
│   ├── config.py
│   ├── homePage.py
│   ├── modelisation.py
│   ├── utilsGraph.py
│   ├── utilsPreprocess.py
│   └── utilsPython.py
├── reports/
│   └── rapport_cyclisme_paris.pdf
├── models/
├── images/
├── requirements.txt
└── README.md
```
---

## Pipeline
1. Collecte et intégration des données
2. Nettoyage et préparation des données
3. Analyse exploratoire et visualisation
4. Feature engineering
5. Entraînement de modèles de machine learning
6. Déploiement d’une application interactive avec Streamlit

---

## Modélisation
Plusieurs modèles ont été testés pour prédire le trafic cycliste :
- Random Forest Regressor
- XGBoost
- Prophet

Objectif : prédire le volume de trafic en fonction de variables temporelles et contextuelles.

---

## Application interactive
Une application a été développée avec Streamlit pour :
- visualiser les données
- explorer les tendances
- tester les prédictions

---

# Résultats
- Identification des facteurs clés influençant le trafic cycliste
- Modèle capable d’anticiper la fréquentation
- Outil d’aide à la décision pour la gestion des mobilités urbaines

---

## Reproductibilité
Les jeux de données et les modèles entraînés ne sont pas inclus dans ce repository en raison de leur volume.

Le projet met l’accent sur :
- la structuration du pipeline de données
- les étapes de préparation et de modélisation
- la logique d’analyse et de prédiction

Le code peut être exécuté avec des données équivalentes.

---

## Accès rapide
- [Rapport PDF](reports/rapport_cyclisme_paris.pdf)
- [Scripts Python](src/)
