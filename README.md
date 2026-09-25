# 🇱🇰 Sri Lanka Census AI
## Machine Learning-Based Socioeconomic District Profiling Using the 2024 Population & Housing Census

An end-to-end machine learning and exploratory analytics project that analyzes district-level socioeconomic patterns in Sri Lanka using data extracted from the **Census of Population and Housing 2024 Final Report** published by the Department of Census and Statistics, Sri Lanka.

The project combines:

- Exploratory Data Analysis
- Feature Engineering
- Principal Component Analysis (PCA)
- K-Means Clustering
- Hierarchical Clustering
- Isolation Forest Anomaly Detection
- Geospatial Visualization
- Explainable District Profiling

---

## 🎯 Project Objective

The main objective of this project is to identify and analyze socioeconomic patterns among Sri Lanka's 25 districts using official 2024 Census indicators.

Instead of manually assigning districts to categories, machine learning techniques are used to discover similarities and differences based on demographic, education, digital access, employment, migration, household, housing and infrastructure indicators.

---

## 📊 Dataset

The dataset was constructed from district-level tables published in the:

**Census of Population and Housing 2024 – Final Report**

Published by:

**Department of Census and Statistics, Sri Lanka**

The final machine-learning dataset contains:

- **25 districts**
- **53 variables**
- Demographic indicators
- Population density
- Urban/rural population
- Education levels
- Computer literacy
- Digital literacy
- Employment and unemployment
- Migration
- Household characteristics
- Housing characteristics
- Drinking-water access
- Cooking fuel
- Sanitation indicators

A separate data dictionary is included to document the meaning and source of the variables.

---

## 🧹 Data Preparation

The original Census report was published in PDF format.

Relevant district-level tables were extracted and combined into a single structured dataset.

The preprocessing pipeline included:

1. Extracting district-level Census indicators
2. Standardizing district names
3. Converting numerical values and percentages
4. Combining multiple Census tables
5. Validating district totals
6. Checking missing values
7. Removing redundant variables for clustering
8. Standardizing ML features using `StandardScaler`

---

## 🧠 Selected Machine Learning Features

A balanced subset of socioeconomic variables was selected for clustering.

### Demography

- Average annual population growth
- Population density
- Urban population percentage
- Population below age 18
- Disability rate

### Education & Digital Access

- No-schooling percentage
- G.C.E. A/L or higher education percentage
- Computer literacy
- Digital literacy

### Economy

- Unemployment rate
- Net migration rate

### Household Structure

- One-person households
- Female-headed households

### Housing

- Household-member-owned housing
- Permanent housing units

### Infrastructure

- Drinking water within housing unit
- Gas used for cooking
- Water-sealed toilet access

---

## 🔬 Machine Learning Pipeline

```text
2024 Census Final Report
          ↓
District-Level Data Extraction
          ↓
Data Validation & Cleaning
          ↓
Feature Selection
          ↓
StandardScaler
          ↓
Principal Component Analysis
          ↓
K-Means Clustering
          ↓
Hierarchical Clustering
          ↓
Cluster Profiling
          ↓
Isolation Forest
          ↓
Geospatial Visualization

## 🌐 Live Demo

Explore the interactive Sri Lanka district cluster map here:

[🔗 View Interactive Map](https://hiru-stack.github.io/sri-lanka-census-ai/)

Created and done by Hirusha Jayasundara
