# Electric Vehicle Range Prediction

## Project Overview
This project focuses on predicting the driving range of electric vehicles (EVs) based on their mechanical specifications and features. Using a dataset of real-world EV registrations, a machine learning model was developed to estimate the electric range for various vehicle types.

## Objective
- Predict the **electric range** of EVs using features like model year, make, model, battery type, and other mechanical specifications.  
- Provide insights into which vehicle features most influence range performance.  
- Demonstrate proficiency in **data analysis, preprocessing, and predictive modeling** applied to mechanical systems.

## Dataset
- Source: [Kaggle – Electric Vehicle Data](https://www.kaggle.com/datasets/rithurajnambiar/electric-vehicle-data)  
- Contains **real-world electric vehicle specifications** including:  
  - Model Year  
  - Make and Model  
  - Electric Vehicle Type (BEV or PHEV)  
  - Base MSRP  
  - Electric Range  

- Split into **train and test sets** for model development and evaluation.

## Approach
1. **Data Cleaning & Preprocessing**  
   - Selected relevant mechanical features for range prediction.  
   - Categorical features (`Make`, `Model`, `Electric Vehicle Type`) were one-hot encoded.  
   - Ensured train and test datasets had consistent feature alignment.  

2. **Modeling**  
   - Trained a **Random Forest Regressor** to predict EV range.  
   - Evaluated model performance using **Mean Squared Error (MSE)** and **R² score**.  

3. **Results**  
   - Model achieved **R² ≈ 0.99**, indicating very high prediction accuracy.  
   - Visualized predicted vs actual ranges to verify performance.  
   - Analyzed **feature importance** to identify which mechanical and battery specifications influence EV range the most.

## Usage
A **predictive function** was implemented to estimate EV range for new vehicle specifications:
