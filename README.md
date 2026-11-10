# Asthma Patient Data Challenge: ML Prediction, Regression & Synthetic Data

## 📌 Project Overview
This repository contains a comprehensive Machine Learning project based on real-world asthma patient data. The project is divided into three core parts focusing on predictive modeling, count regression, and privacy-preserving synthetic data generation for healthcare applications.

## 🚀 Key Objectives & Methodology

### Part 1: Exacerbation Binary Classification
* **Objective:** Predict the occurrence of asthma exacerbations within a year (`post_index_exacerbations365` recoded as binary `0` or `1`).
* **Deliverable:** A robust Python script and resulting prediction CSV (`patid`, `prediction`). Evaluated using F1-score and precision.

### Part 2: Exacerbation Count Regression
* **Objective:** Predict the exact number of asthma exacerbations (integer) over the year and assess treatment influence.
* **Deliverable:** A regression pipeline and output CSV. Evaluated using Poisson log-likelihood metrics.

### Part 3: Privacy-Preserving Synthetic Data Generation
* **Objective:** Generate realistic synthetic health data while ensuring individual privacy and data confidentiality.
* **Methodology:** Implementation of advanced generative approaches (inspired by Guillaudeux et al., 2023).
* **Evaluation:** Evaluated combining **Wasserstein distance** (distribution resemblance), correlation preservation, and **nearest-neighbor distance** (privacy metric).

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Core Libraries:** `pandas`, `numpy`, `scipy`, `scikit-learn`, `statsmodels`

---
*Author: Redouane Kenniche* | *Master 2 Health Data Intelligence Student*
