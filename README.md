# 🛒 Jumia Products Scraping Data

<div style="width:100%;text-align: center; background-color:white;"> <img align=middle src="https://github.com/Abdulrahmankhaled11/jumia-scraping/blob/main/photo.png" width="700px" height="300px">
  
## 📘 Description

Ce projet consiste à **extraire automatiquement les informations de produits à partir du site Jumia** (plateforme e-commerce très populaire en Afrique).  
L’objectif est de **collecter des données** comme le nom du produit, le prix, l’image, la marque, les avis et la note moyenne, afin de pouvoir les **analyser ou visualiser ultérieurement**.

Ce script illustre l’usage du **web scraping** en Python avec les bibliothèques `requests`, `BeautifulSoup`, `requests_html`, `pandas` et `csv`.

---

## 🚀 Fonctionnalités principales

- Extraction de **plusieurs pages** de produits Jumia.  
- Collecte automatique de :
  - 🏷️ Nom du produit  
  - 💰 Prix  
  - 🖼️ URL de l’image  
  - 🏢 Marque  
  - ⭐ Nombre d’avis et note moyenne  
- Sauvegarde des données dans :
  - Un fichier **Excel (.xlsx)**  
  - Un fichier **CSV (.csv)**  
- Compatible avec plusieurs domaines Jumia (`jumia.ma`, `jumia.com.eg`, etc.)

---

## 🧠 Technologies utilisées

- **Python 3.x**
- **requests** → pour envoyer des requêtes HTTP  
- **BeautifulSoup4** → pour parser le code HTML  
- **requests_html** → pour charger les pages dynamiques  
- **pandas** → pour structurer et exporter les données en Excel  
- **csv** → pour exporter les données sous format CSV  

---

## 📂 Structure du projet
Voici la structure complète du dépôt :

Web-Scraping-Jumia/
│
├── 📜 README.md # Documentation principale du projet
├── 📦 requirements.txt # Liste des librairies Python nécessaires
├── 📜 main_scraper.py # Script principal qui exécute tous les modules
│

│ ├── scraping_ma.py # Script de scraping pour Jumia Maroc
│ ├── scraping_eg.py # Script de scraping pour Jumia Égypte
│ └── utils.py # (Optionnel) Fonctions utilitaires : sauvegarde, logs, etc.
│
├── 📊 data/ # Dossier contenant les données collectées
│ ├── Jumia_products.csv # Résultats du scraping Jumia Égypte
│ ├── XIAOMI_Redmi_products.xlsx # Résultats du scraping Jumia Maroc
│ └── raw/ # (Optionnel) Données brutes avant nettoyage
│
├── 🧪 notebooks/ # Dossier pour tes analyses ou tests dans Jupyter
│ └── analysis.ipynb # Exemple d’analyse des produits collectés
└── 🗂️ docs/ # Documentation supplémentaire
├── screenshots.png # Captures d’écran des résultats / dashboards
└── architecture_diagram.png # (Optionnel) Schéma du fonctionnement du projet

