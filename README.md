# 📊 Dashboard Commercial – Analyse des ventes en Europe de l'Ouest

## 📌 Contexte

Dans le cadre de ce projet, j'ai conçu un **tableau de bord commercial interactif sous Microsoft Excel** afin de répondre aux besoins du responsable des ventes de l'entreprise fictive **Zarigaual**.

L'objectif était de transformer des données de ventes brutes en un outil d'aide à la décision permettant de suivre les performances commerciales en Europe de l'Ouest et d'identifier les principales tendances de vente.

Les données utilisées proviennent d'un cas pratique proposé par **OpenClassrooms**.

---

## 🎯 Problématique métier

Le responsable commercial souhaitait disposer d'un tableau de bord capable de répondre aux questions suivantes :

- Quel est l'état des ventes de l'entreprise en Europe de l'Ouest depuis 2019 ?
- Comment évoluent les ventes par trimestre ?
- Quelles catégories de vêtements génèrent le plus de chiffre d'affaires ?
- Les pantalons de la collection 2018 se vendent-ils mieux que ceux de la collection 2020 ?
- Les objectifs commerciaux sont-ils atteints ?

---

## 📂 Source des données

- **Entreprise :** Zarigaual (données fictives)
- **Source :** OpenClassrooms
- **Période étudiée :** 2019 à 2021
- **Zone géographique :** Europe de l'Ouest

---

## 🧹 Préparation des données

Avant de réaliser les analyses, plusieurs étapes de préparation des données ont été effectuées afin de garantir leur qualité et leur fiabilité.

### Nettoyage des données

- Vérification de la qualité des données
- Identification des doublons
- Suppression des doublons
- Transformation du jeu de données en **Tableau Excel** pour faciliter les calculs et les analyses

### Enrichissement des données

- Création d'une colonne **Année** à partir de la date de vente
- Création d'une table de correspondance entre les codes produits et les libellés produits
- Utilisation de **RECHERCHEV** pour remplacer les codes produits par leurs noms (ex. : **PP234 → Jupe**)

---

## 📈 Analyse des données

Une feuille **Statistiques** a été créée afin de calculer les principaux indicateurs de performance (KPI).

### KPI calculés

- Chiffre d'affaires total
- Chiffre d'affaires par année
- Chiffre d'affaires par catégorie
- Chiffre d'affaires par produit
- Évolution des ventes par trimestre
- Évolution des ventes par catégorie et par trimestre
- Comparaison des ventes des pantalons des collections **2018** et **2020**

Pour réaliser ces analyses, plusieurs **Tableaux Croisés Dynamiques (TCD)** ont été créés afin de synthétiser les données.

---

## 📊 Tableau de bord

À partir des indicateurs calculés, un tableau de bord interactif a été conçu pour permettre au responsable commercial de suivre rapidement les performances de l'entreprise.

Le tableau de bord comprend notamment :

- 📈 Évolution du chiffre d'affaires par trimestre
- 🎯 Suivi des objectifs commerciaux
- 🥧 Répartition des ventes par catégorie de vêtements
- 🌍 Carte des ventes en Europe de l'Ouest
- 🎛️ Segments (Slicers) permettant de filtrer les analyses par période ou catégorie

---

## 🛠️ Outils et compétences

### Outils

- Microsoft Excel

### Fonctions Excel

- RECHERCHEV
- SOMME.SI.ENS
- NB.SI.ENS
- SI

### Analyse de données

- Nettoyage et préparation des données
- Enrichissement des données
- Construction de KPI
- Analyse des ventes
- Analyse temporelle
- Analyse comparative

### Visualisation

- Tableaux Croisés Dynamiques (TCD)
- Graphiques dynamiques
- Carte
- Segments (Slicers)
- Mise en forme conditionnelle
- Tableau de bord interactif

---

## 📈 Résultats

Ce tableau de bord permet au responsable commercial de :

- Suivre l'évolution des ventes entre 2019 et 2021.
- Identifier les catégories de vêtements les plus performantes.
- Comparer les performances des collections 2018 et 2020.
- Mesurer l'atteinte des objectifs commerciaux.
- Analyser les ventes par trimestre et par catégorie.
- Disposer d'une vision synthétique facilitant la prise de décision.

---

## 🎓 Compétences développées

Ce projet m'a permis de renforcer mes compétences en :

- Compréhension d'un besoin métier
- Préparation et fiabilisation des données
- Analyse de données avec Excel
- Construction de KPI
- Création de tableaux de bord interactifs
- Data storytelling et restitution des résultats

---

## 📸 Aperçu

> Ajouter ici une ou plusieurs captures d'écran du tableau de bord.

---

## 📁 Structure du projet

```text
Dashboard-Commercial-Zarigaual/
│
├── README.md
├── Dashboard_Commercial.xlsx
├── Data/
│   └── ventes_europe_ouest.xlsx
├── Images/
│   ├── dashboard.png
│   └── statistiques.png
└── Documentation/
    └── README.md
```

## 👤 Auteur

**Moïse Obiliki**

Passionné par la Data Analytics, je développe des projets permettant de transformer des données en tableaux de bord interactifs et en indicateurs d'aide à la décision.

**Compétences :** Excel • SQL • Python • Power BI • Looker Studio • BigQuery
