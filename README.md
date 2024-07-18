**Bangalore House Price Prediction**

**Project Overview**
This project focuses on predicting house prices in Bangalore using machine learning techniques. The dataset used for this project includes various attributes such as location, size, total square footage, number of bathrooms, and price.

**Project Structure**
**1. Data Collection**
Data sourced from Kaggle: Bangalore House Prices Dataset
Ensure your kaggle.json is added to Google Drive for dataset access.
**2. Data Cleaning**
Removed unnecessary columns and handled missing values to prepare the data for analysis.
**3. Feature Engineering**
Created new features like 'bhk' (bedrooms + hall + kitchen) and 'price_per_sqft'.
**4. Outlier Detection and Removal**
Removed outliers using domain knowledge and statistical techniques.
**5. Dimensionality Reduction**
Applied dimensionality reduction to manage less frequent locations.
**6. Model Building**
Trained a Linear Regression model, selected for its performance over other algorithms tested.
**7. Deployment**
Saved the trained model using pickle and deployed a web interface using Gradio for predicting house prices based on location, square footage, bathrooms, and bedrooms.

**Acknowledgments**
Dataset: Kaggle - Bangalore House Prices Dataset
Libraries Used: pandas, numpy, matplotlib, scikit-learn, Gradio
