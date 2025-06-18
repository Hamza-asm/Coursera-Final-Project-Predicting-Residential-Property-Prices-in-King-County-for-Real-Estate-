# King County House Price Prediction

A complete end-to-end pipeline in Jupyter Notebook for exploring, visualizing, and modeling home-sale prices in King County, Washington (Seattle area). This project covers data ingestion, cleaning, feature engineering, exploratory analysis, and development of multiple regression models (Linear, Polynomial, Ridge) with robust evaluation.

---



## 🚀 Project Overview

Seattle’s King County housing market provides rich, real-world data for practicing predictive modeling. In this repository, you will:

1. **Load & preprocess** raw sales data.  
2. **Engineer features** (date conversions, new attributes).  
3. **Explore relationships** via summary statistics and visualizations.  
4. **Train regression models**:  
   - Simple and multiple **Linear Regression**  
   - **Polynomial Regression** with Scikit-learn `Pipeline`  
   - **Ridge Regression** for regularization  
5. **Evaluate** using R² scores, train/test splits, and cross-validation.  
6. **Compare** model performance and discuss trade-offs.
   
   Note: This project was completed as the final project for the Coursera Data Analytics with Python course.

---

## 📂 Dataset

- **Source:** Kaggle “House Sales in King County, USA”  
- **Records:** ~21,000 home sales (2014–2015)  
- **Key columns:**  
  - `price` (target)  
  - `bedrooms`, `bathrooms`, `sqft_living`, `floors`, `waterfront`, `view`, `condition`, `grade`  
  - Geographic: `lat`, `long`, `zipcode`  
  - Temporal: `date`, `yr_built`, `yr_renovated`  
- **Location:** Place `kc_house_data.csv` under `data/` (not committed due to size).

---

## 🔑 Key Findings

- Strong positive correlation between square footage (sqft_living) and price.

- Waterfront properties command a significant price premium.

- Location (latitude, longitude, zipcode) clusters reveal regional price differences.
