# Unemployment Causality And Distribution Analysis

## Labour-Market Intelligence, Distributional Analytics, and Exploratory Unemployment Pattern Discovery in India

This repository presents a **data-driven unemployment analytics workflow** focused on uncovering **regional, structural, and distributional labour-market patterns in India** using Python-based exploratory analysis and visualization. The project brings together multi-source unemployment datasets and translates them into an interpretable analytical pipeline for studying **unemployment intensity, employment distribution, labour-force participation, regional dispersion, and macro-pattern variation across geography and area classifications**.

Rather than serving as a simple plotting notebook, the project is best positioned as a **labour-market intelligence and socio-economic analytics prototype** that combines **data cleaning, feature standardization, correlation profiling, distributional visualization, and region-level comparative analysis** into a compact but meaningful unemployment analytics workflow.

---

## Executive Overview

Understanding unemployment dynamics is central to labour economics, public policy, economic planning, and social-impact analysis. Unemployment is not merely a single national number; it is a structurally heterogeneous phenomenon influenced by **region, geography, labour participation patterns, urban-rural composition, and macroeconomic disruptions**.

This project explores those dynamics using unemployment datasets covering Indian states and regions. It builds an analytical workflow that examines:

- unemployment rate distribution
- employment-level variation
- labour participation intensity
- rural vs urban structure
- directional / zonal regional grouping
- region-wise unemployment comparisons
- visual pattern discovery through multivariate analytics

The overall result is a **decision-support style exploratory analysis** that can serve as a starting point for labour-market dashboards, public-policy analytics, or more advanced econometric modeling.

---

## Project Objective

The goal of this repository is to analyze unemployment in India through an interpretable and visually rich exploratory framework that helps answer questions such as:

- How is unemployment distributed across Indian regions?
- How do employment and labour participation relate to unemployment patterns?
- How do rural and urban unemployment structures differ?
- How do macro-regional groupings compare across the available data?
- What visual patterns emerge when unemployment, employment, and labour participation are analyzed together?

---
<img width="328" height="444" alt="{E97CEAAB-4D64-43EB-87D4-FE73CB42818D}" src="https://github.com/user-attachments/assets/ec36cbb4-79f8-403b-8f1a-4444f83a55a1" /> <img width="358" height="444" alt="{94731984-210D-48BF-AF53-BC5ECFFD9601}" src="https://github.com/user-attachments/assets/5d621a27-192a-4d0b-8cb1-8a7f44a404a2" />
  <img width="691" height="415" alt="{04405F3F-EC70-4F2F-AB11-F03EEF90346B}" src="https://github.com/user-attachments/assets/e3c4c3bd-d607-4701-8ba3-3529500a560c" />


---

## Data Assets

The project uses **two unemployment datasets**:

### 1. Historical State-Level Unemployment Dataset
This dataset includes:
- region
- date
- frequency
- estimated unemployment rate
- estimated employed population
- estimated labour participation rate
- area classification

This dataset supports **rural vs urban** decomposition and broader state-level distributional analysis.

### 2. Region-Extended Unemployment Dataset
This dataset includes:
- region
- date
- frequency
- estimated unemployment rate
- estimated employed population
- estimated labour participation rate
- macro-regional direction / zone
- longitude
- latitude

This dataset extends the analysis by adding **regional grouping** and **geospatial metadata**, making it more suitable for higher-level regional comparison.

---

## Analytical Workflow

### 1. Data Ingestion
The notebook loads both datasets into pandas from a Google Drive / Colab workflow.

### 2. Data Cleaning
The workflow drops null records and validates the cleaned datasets before analysis.

### 3. Schema Inspection
The notebook inspects data types, non-null counts, and memory footprint to confirm dataset integrity.

### 4. Correlation Profiling
Correlation heatmaps are generated to examine numeric relationships among:
- unemployment
- employment
- labour participation
- geographic coordinates where available

### 5. Distributional Visualization
The project uses multiple visualization layers to study how unemployment and employment are distributed across regions.

### 6. Multivariate Exploration
Pairplots are used to expose cross-variable relationships and cluster-like patterns.

### 7. Hierarchical Structural Analysis
Sunburst visualizations are used to analyze unemployment composition across:
- **Area → Region**
- **Direction / Zone → Region**

### 8. Region-Wise Comparison
Line-based comparative plots are used to observe how unemployment varies across named regions.

---

## Current Implementation Scope

The current notebook is strongest as an **exploratory labour-market distribution and comparison analysis**.

It includes:
- null handling
- schema validation
- correlation heatmaps
- employment and unemployment histograms
- pairplot-based multivariate exploration
- hierarchical sunburst visualizations
- comparative regional plotting

### Important Note
Although the repository title includes the term **“causality,”** the currently committed implementation does **not yet perform formal causal inference, Granger causality testing, structural modeling, or econometric identification**. At present, the repository is more accurately described as a **distributional and exploratory unemployment analytics project with strong potential for extension into causal labour-market analysis**.

---

## Why This Project Matters

This project is relevant to the intersection of:

- **Economic Data Analysis**
- **Public Policy Analytics**
- **Labour-Market Intelligence**
- **Socio-Economic Visualization**
- **Exploratory Data Science**
- **Regional Economic Analysis**
- **Data-Driven Decision Support**

It demonstrates the ability to transform raw unemployment data into an interpretable analytical workflow that surfaces macroeconomic and socio-economic structure through visual analytics.

---

## Technical Stack

### Core Environment
- Python
- Jupyter Notebook
- Google Colab

### Data & Analysis Libraries
- pandas
- NumPy
- scikit-learn

### Visualization Stack
- Matplotlib
- Seaborn
- Plotly Express

---

## Repository Structure

```text
Unemployment-Causality-And-Distribution-Analysis/
│
├── TASK2.ipynb
├── Unemployment in India (1).csv
└── Unemployment_Rate_upto_11_2020 (1).csv
