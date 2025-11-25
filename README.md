Auteur / Author
Astrid Villalobos
Data Scientist in Training | Montréal, QC
[linkedin.com/in/astrid-villalobos](https://www.linkedin.com/in/astridcvr/)


<div align="center">

# 🧠 Daily ML Practice  
**Daily Machine Learning Practice – 1 Commit per Day**  
**Pratique Quotidienne en Apprentissage Automatique – 1 Commit par Jour**

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)
![Activity](https://img.shields.io/github/commit-activity/m/astridcvr/daily-ml-practice?color=brightgreen)

</div>

---

## 🎯 Objective / Objectif  
> **EN:** Strengthen ML skills through **1 small daily commit**, using **sample sales data** to explore analysis, prediction, and automation. 
 
> **FR:** Renforcer les compétences en ML avec **1 petit commit quotidien**, en utilisant des **données d'exemple de ventes** pour explorer l'analyse, la prédiction et l'automatisation.

---

## 📊 Dataset – Sample Sales Data  
- **Source:** [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)  
- **File:** `data/sales_data_sample.csv`  
- **Variables:** `ORDERNUMBER`, `QUANTITYORDERED`, `PRICEEACH`, `SALES`, `COUNTRY`, etc.  
- **Goal:** Predict sales trends, segment customers, and forecast demand. 

---

## 📘 Data Dictionary / Dictionnaire des données

| Column Name      | Data Type         | Description (EN)                         | Description (FR)                                 |
| ---------------- | ----------------- | ---------------------------------------- | ------------------------------------------------ |
| ORDERNUMBER      | int               | Unique identifier for the order.         | Identifiant unique de la commande.               |
| QUANTITYORDERED  | int               | Number of units ordered.                 | Nombre d’unités commandées.                      |
| PRICEEACH        | float             | Price per individual unit.               | Prix par unité.                                  |
| ORDERLINENUMBER  | int               | Line number within the order.            | Numéro de ligne dans la commande.                |
| SALES            | float             | Total sales amount (quantity × price).   | Montant total des ventes (quantité × prix).      |
| ORDERDATE        | string → date     | Date the order was placed.               | Date à laquelle la commande a été passée.        |
| STATUS           | string (category) | Order status (e.g., Shipped, Cancelled). | Statut de la commande (ex. : Expédiée, Annulée). |
| QTR_ID           | int               | Quarter of the year (1–4).               | Trimestre de l’année (1–4).                      |
| MONTH_ID         | int               | Month number (1–12).                     | Numéro du mois (1–12).                           |
| YEAR_ID          | int               | Year of the order.                       | Année de la commande.                            |
| PRODUCTLINE      | string (category) | Product category.                        | Catégorie du produit.                            |
| MSRP             | float             | Manufacturer’s Suggested Retail Price.   | Prix de vente suggéré par le fabricant.          |
| CUSTOMERNAME     | string            | Customer or company name.                | Nom du client ou de l’entreprise.                |
| PHONE            | string            | Customer phone number.                   | Numéro de téléphone du client.                   |
| ADDRESSLINE1     | string            | Address line 1.                          | Adresse ligne 1.                                 |
| ADDRESSLINE2     | string            | Address line 2 (optional).               | Adresse ligne 2 (optionnel).                     |
| CITY             | string            | Customer city.                           | Ville du client.                                 |
| STATE            | string            | State or province.                       | État ou province.                                |
| POSTALCODE       | string            | Postal or ZIP code.                      | Code postal.                                     |
| COUNTRY          | string            | Customer country.                        | Pays du client.                                  |
| TERRITORY        | string            | Sales territory.                         | Territoire de vente.                             |
| CONTACTLASTNAME  | string            | Last name of customer contact.           | Nom de famille du contact client.                |
| CONTACTFIRSTNAME | string            | First name of customer contact.          | Prénom du contact client.                        |
| DEALSIZE         | string (category) | Size of the deal (Small, Medium, Large). | Taille de la vente (Petite, Moyenne, Grande).    |

---

## 🧩 Game Rules / Règles du jeu  
| Rule | Detail |
|------|--------|
| 1 commit per day | Minimum 1 line of code |
| Bilingual | Comments in English + French |
| Visible progress | GitHub activity = green every day |

---

## 🚀 **Quick Start – Execute in 1 Line**
```bash
python daily_practice.py
