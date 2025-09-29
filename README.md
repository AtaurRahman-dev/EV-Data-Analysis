# EV Data Analysis

## Overview

This repository contains a **comprehensive analysis of Electric Vehicles (EVs)** registered in Washington State, including **Battery Electric Vehicles (BEVs)** and **Plug-in Hybrid Electric Vehicles (PHEVs)**. The dataset includes details such as **VIN, model year, make, model, electric range, base MSRP, location, and eligibility for clean alternative fuel incentives**.

The analysis includes **data cleaning, exploratory data analysis (EDA), visualizations, and predictive modeling** using Linear Regression to estimate the electric range of vehicles.

---

## Dataset

* **Source:** Washington State Department of Licensing (DOL)
* **Columns include:**

  * VIN, County, City, State, Postal Code
  * Model Year, Make, Model, Electric Vehicle Type
  * Clean Alternative Fuel Vehicle (CAFV) Eligibility
  * Electric Range, Base MSRP
  * Legislative District, DOL Vehicle ID, Vehicle Location
  * Electric Utility, 2020 Census Tract, Longitude, Latitude

---

## Objective

1. Clean and preprocess the dataset by handling missing values, duplicates, and inconsistencies.
2. Explore EV adoption trends, popular makes/models, electric range distribution, pricing, and regional patterns.
3. Visualize insights using bar charts, line graphs, scatter plots, pie charts, and geospatial maps.
4. Develop a **Linear Regression model** to predict **Electric Range** based on vehicle specifications.

---

## Contents

* `EV_Data_Analysis.ipynb` – Jupyter Notebook with all analysis, code, and visualizations.
* `README.md` – This file describing the project.
* `Data/` – Folder containing the dataset (if included).

---

## Key Features

* Data cleaning and preprocessing techniques.
* Exploratory data analysis with summary statistics.
* Visualizations of EV trends, adoption, and pricing.
* Linear Regression model to predict Electric Range.
* Interpretation of model metrics including **R² score** and feature influence.

---

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/AtaurRahman-dev/EV-Data-Analysis.git
```

2. Open the Jupyter Notebook (`EV-Data-Analysis.ipynb`).
3. Run all cells to reproduce the analysis and visualizations.

---

## License

This repository is for **educational purposes** and can be freely accessed.
