# Open Access Publication Analysis and Classification

## Overview
This project explores **Open Access (OA)** publication data to uncover trends, relationships, and predictive patterns in global research accessibility.  
By combining multiple OA-related datasets, the project performs **data preprocessing, exploratory data analysis (EDA), and machine learning-based classification** to identify key factors influencing OA adoption across journals, countries, and publication years.

The study focuses on:
- How Open Access adoption varies across regions and time
- Which factors predict OA levels or license types
- How machine learning can classify and interpret OA publication patterns

---

## Objectives
- Integrate and preprocess multiple OA datasets for analysis  
- Perform exploratory and statistical analysis to identify patterns  
- Build classification models to predict:
  - **OA License Type** (e.g., Gold, Green, Hybrid, etc.)
  - **OA Level** (High vs. Low OA adoption)
- Visualize global and temporal OA trends

---

## Project Structure

| Notebook | File Name | Description |
|-----------|------------|-------------|
| **01_Data_Preprocessing_and_License_Classification.ipynb** | Data integration, cleaning, and initial modeling for classifying publications based on OA license attributes. |
| **02_Data_Preprocessing_and_OA_Level_Classification.ipynb** | Advanced EDA and ML modeling for classifying journals into high or low OA adoption groups. |
| **03_Country_and_Trend_Analysis.ipynb** | Visualization of OA publication trends by country and year, and analysis of different OA types (Gold, Hybrid, Bronze, Green, etc.). |

---

## Methodology
1. **Data Collection & Preprocessing**
   - Combined multiple CSV datasets: articles, URLs, licenses, and mapping files  
   - Handled missing values, encoding, and feature engineering  

2. **Exploratory Data Analysis**
   - Distribution plots, correlation heatmaps, and OA trends visualization  
   - Analysis by publication year and country  

3. **Modeling & Evaluation**
   - Applied Decision Tree, Random Forest, Gradient Boosting, KNN, XGBoost, and LightGBM  
   - Evaluated models using R², MAE, Accuracy, and Confusion Matrices  
   - Classified data based on OA license type and OA adoption level  

4. **Trend & Country Analysis**
   - Identified top publishing countries  
   - Visualized OA growth patterns and type distribution  

---

## Tech Stack
- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, lightgbm, shap  
- **Environment:** Jupyter Notebook  

---

## Key Insights
- OA adoption shows steady growth over years across major research countries.  
- License type and publication metadata significantly influence OA accessibility.  
- Decision Tree and Ensemble models performed effectively for OA classification tasks.  
- Clear distinction between **Gold OA** dominance and varying **country-level OA patterns**.  

---

## Conclusion
The project provides a comprehensive view of global Open Access trends and builds predictive models to understand the factors driving OA adoption.  
It combines **EDA, data modeling, and visualization** to offer actionable insights into the evolving landscape of scholarly publishing.
