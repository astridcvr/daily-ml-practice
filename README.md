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

| Column Name          | Description (EN)                                             | Description (FR)                                                            |
| -------------------- | ------------------------------------------------------------ | --------------------------------------------------------------------------- |
| **ORDERNUMBER**      | Unique identifier for each order.                            | Identifiant unique pour chaque commande.                                    |
| **QUANTITYORDERED**  | Number of units ordered.                                     | Nombre d’unités commandées.                                                 |
| **PRICEEACH**        | Price per unit.                                              | Prix par unité.                                                             |
| **ORDERLINENUMBER**  | Line number inside the order (useful for multi-item orders). | Numéro de ligne dans la commande (utile pour les commandes multi-articles). |
| **SALES**            | Total amount of the order line (quantity × price).           | Montant total de la ligne de commande (quantité × prix).                    |
| **ORDERDATE**        | Date when the order was created.                             | Date à laquelle la commande a été créée.                                    |
| **STATUS**           | Order status (e.g., Shipped, Cancelled).                     | Statut de la commande (ex. : Expédiée, Annulée).                            |
| **QTR_ID**           | Quarter of the year (1–4).                                   | Trimestre de l’année (1–4).                                                 |
| **MONTH_ID**         | Month number (1–12).                                         | Numéro du mois (1–12).                                                      |
| **YEAR_ID**          | Year of the order.                                           | Année de la commande.                                                       |
| **PRODUCTLINE**      | Product category (e.g., Classic Cars, Motorcycles).          | Catégorie du produit (ex. : Voitures Classiques, Motos).                    |
| **MSRP**             | Manufacturer’s Suggested Retail Price.                       | Prix de vente suggéré par le fabricant.                                     |
| **CUSTOMERNAME**     | Name of the customer/company.                                | Nom du client/de l’entreprise.                                              |
| **PHONE**            | Customer phone number.                                       | Numéro de téléphone du client.                                              |
| **ADDRESSLINE1**     | Customer address line 1.                                     | Adresse du client ligne 1.                                                  |
| **ADDRESSLINE2**     | Customer address line 2 (optional).                          | Adresse du client ligne 2 (optionnel).                                      |
| **CITY**             | City of the customer.                                        | Ville du client.                                                            |
| **STATE**            | State/Province (may be empty for some countries).            | État/Province (peut être vide selon les pays).                              |
| **POSTALCODE**       | Postal/ZIP code.                                             | Code postal.                                                                |
| **COUNTRY**          | Country of the customer.                                     | Pays du client.                                                             |
| **TERRITORY**        | Sales territory associated with the customer.                | Territoire de vente associé au client.                                      |
| **CONTACTLASTNAME**  | Last name of the contact person.                             | Nom de famille du contact.                                                  |
| **CONTACTFIRSTNAME** | First name of the contact person.                            | Prénom du contact.                                                          |
| **DEALSIZE**         | Size of the deal (e.g., Small, Medium, Large).               | Taille de la vente (ex. : Petite, Moyenne, Grande).                         |

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
