# Data Science & Business Analytics Portfolio

Welcome to my portfolio! This repository showcases my data science projects, highlighting data engineering, predictive modeling, and actionable business intelligence.

---

## Featured Project: Amazon Demand Forecasting & Sales Analysis

### 📌 Project Overview
This project focuses on optimizing supply chain efficiency and inventory management by predicting future product demand. Using historical Amazon transactional data, our team engineered a predictive pipeline to forecast sales volume, helping minimize stockouts and reduce overhead holding costs.

### 🛠️ Tech Stack & Methodologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Modeling Techniques:** Time-Series Forecasting / Regression Analysis, Linear Regression, Random Forest
* **Data Pipelines:** Feature engineering (rolling averages, seasonality indicators), data imputation, and outlier treatment.

### 💡 Key Insights & Business Impact
* **Trend Analysis:** Identified key seasonal spikes in specific product categories during Q4, matching historical holiday demand patterns.
* **Model Performance:** Successfully evaluated model forecasting accuracy using R² and RMSE metrics to substantially improve baseline predictions.
* **Strategic Recommendation:** Proposed a dynamic safety-stock replenishment model to prevent capital tie-up in low-velocity SKUs based on the 2023 demand forecast.

### 👥 Team & Contributions
This project was a collaborative team effort. My core responsibilities included:
* **Predictive Modeling:** Built and evaluated a Linear Regression model to forecast Amazon product demand for the year 2023.
* **Data Preprocessing & Feature Engineering:** Cleaned the raw transactional datasets, engineered rolling time-window variables, and handled missing values using Pandas to prepare data for modeling.
* **Model Validation:** Evaluated model performance metrics and generated final visualizations for the business report.

**Project Contributors:**
* **Tiwa Odumakinde** – Predictive Modeling (Linear Regression for 2023 Demand), Data Preprocessing & Feature Selection
* **Vimala Mehrota** – Model Training & Hyperparameter Tuning
* **Akhil Mishra** – Dashboard Development & Business Documentation


---

## Featured Project: Pokémon Stat & Clustering Analysis

### 📌 Project Overview
This project explores Pokémon base stats and elemental types using both **unsupervised clustering** and **supervised predictive modeling**. The goal is to identify distinct tier groupings among Pokémon profiles and build a machine learning model to evaluate how individual stats and types impact overall total performance.

### 🛠️ Tech Stack & Methodologies
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Unsupervised Learning:** K-Means Clustering (Segmentation & Profile Analysis)
* **Supervised Learning:** Multiple Linear Regression
* **Data Processing:** One-Hot Encoding (Type categorization), Feature Scaling, Train/Test Splitting

### 💡 Key Insights & Model Results
* **Cluster Segmentation:** Identified distinct performance tiers across Pokémon (e.g., high-speed glass cannons vs. defensive tanks).
* **Predictive Accuracy:** Achieved an $R^2$ score of **~92%** on test data, explaining over 92% of the variance in total stat scores.
* **Coefficient Interpretation:** Demonstrated that primary types like Psychic (`+46.67`) and Fairy (`+38.49`) carry significant positive premiums in stat allocation, while physical stats contribute steady incremental additions to total power.
