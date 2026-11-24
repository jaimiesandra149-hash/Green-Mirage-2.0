# 🌍 GREEN MIRAGE 2.0

<div align="center">

### GLOBAL ENERGY TRANSITION INTELLIGENCE SYSTEM

**Beyond Renewable Growth. Understanding the Energy Transition.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)](https://matplotlib.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)

**DATA SCIENCE · MACHINE LEARNING · ENERGY ANALYTICS**

</div>

---

## 🔍 THE QUESTION BEHIND THE PROJECT

> Are countries genuinely transitioning away from fossil fuels, or are renewable energy sources simply expanding alongside growing energy demand?

Renewable energy adoption is increasing around the world. But an increase in renewable energy does not automatically mean that fossil fuel dependence is decreasing.

**Green Mirage 2.0** explores this distinction using historical energy data, statistical analysis, country comparisons, and machine learning.

The project looks beyond renewable energy growth to investigate broader changes in the global energy system.

## ⚡ PROJECT AT A GLANCE

| Research Component | Approach |
|:---|:---|
| Energy trend analysis | Exploratory Data Analysis |
| Country comparisons | Five-country case study |
| Feature development | Feature Engineering |
| Country segmentation | K-Means Clustering |
| Dimensionality reduction | Principal Component Analysis |
| Renewable share prediction | Linear Regression |
| Nonlinear prediction | Random Forest Regression |
| Model evaluation | MAE, RMSE, R² |

---

## 🌎 COUNTRIES UNDER INVESTIGATION

The comparative case study focuses on five countries:

| Country | Region |
|:---|:---|
| 🇮🇳 India | Asia |
| 🇨🇳 China | Asia |
| 🇩🇪 Germany | Europe |
| 🇧🇷 Brazil | South America |
| 🇺🇸 United States | North America |

The clustering and predictive modelling workflows additionally use eligible global country observations where sufficient data is available.

---

## 🧠 RESEARCH METHODOLOGY

### 01 — Data Collection & Preparation

Historical energy data is obtained from Our World in Data.

The preprocessing workflow includes:

- Dataset inspection and exploration.
- Missing-value analysis.
- Duplicate removal.
- Numerical data preparation.
- Selection of relevant energy indicators.

### 02 — Exploratory Data Analysis

The project investigates:

- Renewable energy share trends.
- Fossil fuel energy share trends.
- Changes in energy consumption.
- Country-level differences.
- Energy growth patterns over time.

### 03 — Feature Engineering

Additional indicators are developed to examine relationships between renewable and fossil energy.

| Feature | Purpose |
|:---|:---|
| Renewable–fossil share gap | Compare the two energy shares |
| Renewable-to-fossil ratio | Examine their relative proportions |
| Per-capita energy consumption | Explore energy use relative to population |
| GDP per capita | Include an economic indicator where available |
| Year-over-year growth | Examine changes over time |

### 04 — Unsupervised Machine Learning

**K-Means Clustering**

Countries are grouped according to similarities in selected energy characteristics.

The workflow includes:

- Feature selection.
- Missing-value imputation.
- Standardisation.
- Cluster selection using silhouette scores.
- PCA-based cluster visualisation.

### 05 — Predictive Modelling

The project explores one-year-ahead renewable energy share prediction.

Three approaches are compared:

| Model | Role |
|:---|:---|
| Linear Regression | Regression model |
| Random Forest | Nonlinear regression model |
| Previous-Year Baseline | Persistence benchmark |

The models use a chronological train-test split to evaluate predictions on later target years.

### 06 — Model Evaluation

Predictive performance is assessed using:

- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error
- **R²:** Coefficient of Determination

The models are compared against the previous-year baseline rather than being evaluated in isolation.

---

## 📊 PROJECT OUTPUTS

The analysis generates visualisations and exported research tables.

| Output | Contents |
|:---|:---|
| Visualisations | Energy trends, country comparisons and model charts |
| Country summaries | Comparative energy indicators |
| Clustering results | Country-level cluster assignments |
| Model results | Prediction and evaluation metrics |
| Feature analysis | Variables used in the predictive workflow |

**Explore the project files:**

- 📈 [Visualisations](visualizations/)
- 📁 [Research Results](results/)
- 💻 [Research Notebook](notebooks/)

---

## 🛠️ TECHNOLOGY STACK

| Technology | Application |
|:---|:---|
| Python | Core programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Scikit-learn | Machine learning and evaluation |
| Google Colab | Notebook development and execution |

---

## 📂 PROJECT STRUCTURE

```text
GREEN-MIRAGE-2.0/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── Green_Mirage_2.0.ipynb
│
├── visualizations/
│   └── Generated charts and figures
│
└── results/
    └── Exported CSV files
```

---

## 📚 DATA SOURCE

**Our World in Data — Energy**

https://ourworldindata.org/energy

The project uses historical country-level energy indicators from this dataset.

---

## 🔭 FUTURE SCOPE

- Analyse absolute fossil fuel consumption alongside renewable energy growth.
- Expand comparative analysis to additional countries.
- Include additional economic and environmental indicators.
- Explore more advanced time-series forecasting methods.
- Develop an interactive energy transition analytics dashboard.

---

## ⚠️ LIMITATIONS

- Historical trends do not guarantee future outcomes.
- Country comparisons are affected by differences in data availability.
- Clustering depends on the selected features and preprocessing.
- Predictive performance depends on the available observations.
- Feature importance does not establish causation.
- Increasing renewable energy share alone does not demonstrate an absolute reduction in fossil fuel consumption.

---

<div align="center">

### 🌱 LOOK BEYOND THE GROWTH.

**Understand the transition.**

*Green Mirage 2.0 — Exploring what the global energy numbers actually reveal.*

</div>

