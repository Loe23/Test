# Analyse des Transports Publics Normands

Ce projet présente une analyse exploratoire des réseaux de transport publics en Normandie, basée sur les données issues de la base multimodale officielle.

## Objectifs

- Étudier la répartition des arrêts et les horaires
- Visualiser la couverture et la fréquence des services
- Identifier des axes d’amélioration possibles

## Méthodologie

Traitement et analyse des données avec Python, pandas et visualisation matplotlib/seaborn.

## Auteur

LOE Joel


root/
│
├── data/                         # Données brutes (non versionnées si volumineuses)
│
├── notebooks/                    # Jupyter Notebooks pour analyse et visualisation
│   ├── 01_import_and_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_visualization_folium.ipynb
│   └── README.md                 # Explication du notebook (optionnel)
│
├── outputs/                     # Résultats exportés (images, cartes HTML, rapports)
│   ├── carte_arrets_netex.html
│   └── figures/
│
├── scripts/                     # Scripts Python si applicable (pour pipeline, utils)
│   └── extract_data.py
│
├── README.md                    # Présentation du projet (détail ci-dessous)
├── requirements.txt             # Dépendances Python (folium, pandas, etc.)
└── LICENSE                     # Licence du projet (MIT, GPL, etc.)

