# Regression Project – Predicting Average Temperature

## Project Aim
The aim of this project was to analyze and predict average temperature using agricultural and environmental data.  
The dataset was provided by the FAO and IPCC.  
The goal was to understand how activities in the agri-food sector influence temperature and climate.

---

## Steps Taken
1. Loaded and cleaned the dataset  
2. Renamed columns for easier use  
3. Handled missing values  
4. Performed Exploratory Data Analysis (EDA)  
5. Trained and tested three regression models  
6. Compared the model results and selected the best one  

---

## Models Used
- Linear Regression  
- Ridge Regression  
- Random Forest Regressor  

---

## Model Results
Linear Regression  →  R²: 0.516,  MAE: 0.285,  RMSE: 0.385  
Ridge Regression   →  R²: 0.517,  MAE: 0.286,  RMSE: 0.385  
Random Forest      →  R²: 0.640,  MAE: 0.244,  RMSE: 0.332  

The **Random Forest** model performed best with the highest R² and lowest errors.  

---

## Tools Used
- Python (VS Code / Jupyter Notebook)
- Trello (project management)
- GitHub (version control)
- Anaconda (environment setup)
- Google Slides (presentation deck)

---

## How to Recreate the Environment (Anaconda)
To make sure the code runs correctly, follow these steps:

1. **Install Anaconda**  
   Download from [https://www.anaconda.com](https://www.anaconda.com).

2. **Create a new environment**
   ```bash
   conda create -n regression_env python=3.11
