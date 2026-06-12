# 🎬 Cinematic Data Unveiled: An Exploratory Analysis
> *Decoding box office trends, audience preferences, and cinematic history across 19,800+ movies.*

[![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Data_Visualization-4C4C4C?style=flat-square&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

---

## 📌 Executive Summary

This project is a deep dive into the global film industry using purely **Exploratory Data Analysis (EDA)** and **Data Visualization**. Instead of predictive modeling, this notebook focuses on extracting actionable insights, cleaning messy real-world text data, and presenting findings through compelling visual storytelling.

**Dataset Scope:** ~19,800 cinematic records spanning multiple decades.  
**Core Objective:** To understand the relationship between movie runtimes, user ratings, critical reception, and global box office gross.

---

## 🔍 The Analytical Process

This notebook follows a rigorous data analysis workflow, broken down into four key phases:

### 1️⃣ Data Wrangling & Cleaning
* **Missing Value Imputation:** Handled nulls in financial columns (`gross_income`) and metadata (`certificate`).
* **Data Type Conversion:** Transformed string-based monetary values and text-heavy columns into clean, computable numeric types.
* **Feature Parsing:** Extracted meaningful categories from nested text fields (e.g., separating multi-genre tags).

### 2️⃣ Univariate Analysis
* Analyzed the isolated distributions of `duration`, `rating`, and `votes` to establish baselines.
* Identified outliers in box-office revenues using robust statistical summaries.

### 3️⃣ Bivariate & Multivariate Analysis
* Investigated the correlation between **IMDb Ratings** and **Box Office Gross**.
* Grouped data to find the most commercially successful **Directors** and **Genres** across different eras.

### 4️⃣ Data Storytelling (Visuals)
* Leveraged `Matplotlib` and `Seaborn` to create beautiful, publication-ready charts (Bar plots, Scatter plots, Distribution plots, and Heatmaps).

---

## 🗄️ Data Dictionary

A quick look at the core variables analyzed in this dataset:

| Feature | Type | Description |
| :--- | :--- | :--- |
| `name` | `String` | The official title of the movie. |
| `certificate` | `Categorical` | Age rating / Certification (e.g., PG-13, R). |
| `duration` | `Numeric` | Total runtime of the movie in minutes. |
| `genre` | `String` | Comma-separated list of genres associated with the film. |
| `rating` | `Numeric` | Average user rating (e.g., IMDb score). |
| `votes` | `Numeric` | Total number of user votes accumulated. |
| `gross_income`| `Numeric` | Total box office revenue. |
| `directors_name`| `String` | The primary director(s) of the movie. |

---

## 🚀 How to Run Locally

Want to explore the data yourself? Follow these steps:

**1. Clone the repository:**
```bash
git clone [https://github.com/Yash-Shukla11/movies-data-analysis.git](https://github.com/Yash-Shukla11/movies-data-analysis.git)
