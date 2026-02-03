# Fixed-Bed Column Adsorption Analysis

This repository contains a Python toolkit for analyzing breakthrough curves in fixed-bed adsorption columns. It reads experimental data from Excel and fits non-linear kinetic models.

## Features
* **Automated Data Loading:** Reads `column_data.xlsx` using pandas.
* **Non-Linear Regression:** Fits **Thomas** and **Yoon-Nelson** models to experimental data.
* **Performance Metrics:** Calculates $R^2$ and model parameters ($k_{Th}$, $q_0$, $\tau$).
* **Publication-Quality Plots:** Generates high-resolution figures.

## Mathematical Models
1. **Thomas Model:** Used to calculate the maximum solid-phase concentration ($q_0$) and rate constant ($k_{Th}$).
2. **Yoon-Nelson Model:** Used to predict the time required for 50% adsorbate breakthrough ($\tau$).

## 📦 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
