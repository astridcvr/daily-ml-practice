Auteur / Author
Astrid Villalobos
Data Scientist in Training | Montréal, QC
[linkedin.com/in/astrid-villalobos](https://www.linkedin.com/in/astridcvr/)


<div align="center">

# Daily ML Practice  
**Práctica Diaria de Machine Learning – 1 Commit al Día**  
**Pratique Quotidienne en Apprentissage Automatique – 1 Commit par Jour**

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3-orange)

</div>

---

## Objectif / Objective
> **EN**: Improve ML skills with **1 small commit every day** – analyzing **e-commerce sales data**.  
> **FR**: Améliorer mes compétences en ML avec **1 petit commit par jour** – en analysant des **données de ventes e-commerce**.

---

## Dataset: Sample Sales Data (E-commerce)
- **Source**: [Kaggle - Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- **Archivo**: `data/SalesJan2009.csv` (subido localmente)
- **Variables**: `Order`, `Product`, `Quantity`, `Price`, `Country`, `Date`
- **Goal**: Predict sales, segment customers, forecast demand

---

## Règles du jeu / Game Rules
| Règle | Détail |
|------|--------|
| 1 commit par jour | Minimum 1 ligne de code |
| Bilingue | Commentaires en anglais + français |
| Progrès visible | GitHub activity = verte tous les jours |

---

## Plan Diario – 30 Días de Práctica

| Día | Tema (EN/FR) | Archivo | Objetivo |
|-----|-------------|--------|---------|
| 01 | Data Loading / Chargement | `notebooks/day_01_data_loading.ipynb` | Cargar CSV local |
| 02 | EDA / Analyse exploratoire | `notebooks/day_02_eda.ipynb` | Ventas por país |
| 03 | Cleaning / Nettoyage | `notebooks/day_03_cleaning.ipynb` | Manejar nulos |
| 04 | Feature Engineering / Ingénierie | `notebooks/day_04_features.ipynb` | Total por orden |
| 05 | Visualization / Visualisation | `notebooks/day_05_viz.ipynb` | Gráfico de barras |
| 06 | Model Training / Entraînement | `notebooks/day_06_model.ipynb` | Regresión lineal |
| 07 | Evaluation / Évaluation | `notebooks/day_07_eval.ipynb` | Métricas |
| ... | ... | ... | ... |
| 30 | Deployment / Déploiement | `notebooks/day_30_streamlit.ipynb` | App interactiva |

---

## Installation (EN/FR)

```bash
git clone https://github.com/astridcvr/daily-ml-practice.git
cd daily-ml-practice
python -m venv venv
source venv/bin/activate  # Linux/Mac
pip install -r requirements.txt
