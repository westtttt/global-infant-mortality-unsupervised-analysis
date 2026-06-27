# Global Infant Mortality Clustering Analysis

An end-to-end data mining project analysing global infant mortality trends from **1960–2021** using exploratory data analysis and unsupervised machine learning.

The project investigates how infant mortality has changed over time across countries and whether nations can be grouped into meaningful clusters based on long-term mortality characteristics.

---

## Overview

Infant mortality is one of the most widely used indicators of healthcare quality and socio-economic development.

This project analyses over sixty years of global infant mortality data to:

- Explore long-term global trends
- Compare countries and regions
- Identify inequalities in health outcomes
- Cluster countries using machine learning based on mortality behaviour

The entire analysis was completed in Python within a Jupyter Notebook.

---

## Dataset

The project combines two datasets:

- **Global infant mortality rates (1960–2021)**
- **Country metadata**
  - Region
  - Income group

Data preparation included:

- Reshaping wide-format data into long format
- Dataset integration
- Data cleaning
- Missing value assessment
- Feature engineering

---

## Exploratory Data Analysis

The notebook performs extensive EDA including:

- Global mortality trends over time
- Country-level trend analysis
- Regional comparisons
- Descriptive statistics
- Outlier detection
- Decade-by-decade distribution analysis

Key visualisations include:

- Line charts
- Regional trend comparisons
- Boxplots
- Summary statistics

---

## Machine Learning

The project applies **K-Means Clustering** to group countries with similar infant mortality characteristics.

Features include:

- Mean mortality rate
- Median mortality rate
- Standard deviation
- Minimum mortality rate
- Maximum mortality rate

Prior to modelling:

- Features were standardised using `StandardScaler`
- Cluster selection was evaluated using:
  - Elbow Method
  - Silhouette Score

The analysis identified **three distinct clusters** representing different long-term mortality profiles.

---

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## Repository Structure

```
.
├── Infant_Mortality_Analysis.ipynb
├── data/
│   ├── T1.csv
│   └── T2.csv
├── figures/
└── README.md
```

---

## Key Findings

- Global infant mortality has declined substantially between 1960 and 2021.
- Large disparities remain between countries and world regions.
- Countries naturally separate into distinct mortality profiles using unsupervised learning.
- Three clusters provided the strongest balance between cohesion and separation.

---

## Example Workflow

1. Load datasets
2. Reshape data into long format
3. Merge metadata
4. Perform exploratory data analysis
5. Engineer clustering features
6. Standardise variables
7. Determine optimal number of clusters
8. Train K-Means model
9. Interpret resulting country clusters

---

## Future Improvements

Potential extensions include:

- Hierarchical clustering
- DBSCAN
- Gaussian Mixture Models
- PCA for dimensionality reduction
- Time-series clustering methods
- Interactive dashboards using Plotly

---

## Report

The accompanying report explains:

- Data preparation
- Exploratory analysis
- Clustering methodology
- Results
- Interpretation
- Literature review

---

## Author

**Will West**

MSc Data Analytics  
University of Huddersfield
