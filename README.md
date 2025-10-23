# 🛒 Jumia Products Scraping Data

<div style="width:100%;text-align: center; background-color:white;"> <img align=middle src="https://github.com/Abdulrahmankhaled11/jumia-scraping/blob/main/photo.png" width="700px" height="300px">
  
## Description

Ce projet consiste à **extraire automatiquement les informations de produits à partir du site Jumia** (plateforme e-commerce très populaire en Afrique).  
L’objectif est de **collecter des données** comme le nom du produit, le prix, l’image, la marque, les avis et la note moyenne, afin de pouvoir les **analyser ou visualiser ultérieurement**.

Ce script illustre l’usage du **web scraping** en Python avec les bibliothèques `requests`, `BeautifulSoup`, `requests_html`, `pandas` et `csv`.

---

## Fonctionnalités principales

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

## Technologies utilisées

- **Python 3.x**
- **requests** → pour envoyer des requêtes HTTP  
- **BeautifulSoup4** → pour parser le code HTML  
- **requests_html** → pour charger les pages dynamiques  
- **pandas** → pour structurer et exporter les données en Excel  
- **csv** → pour exporter les données sous format CSV  

---
└── architecture_diagram.png # (Optionnel) Schéma du fonctionnement du projet

