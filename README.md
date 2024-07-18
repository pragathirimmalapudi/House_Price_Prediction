**Bangalore House Price Prediction**<br />

**Project Overview**
This project focuses on predicting house prices in Bangalore using machine learning techniques. The dataset used for this project includes various attributes such as location, size, total square footage, number of bathrooms, and price.<br />

**Project Structure**<br />
**1. Data Collection**
Data sourced from Kaggle: Bangalore House Prices Dataset
Ensure your kaggle.json is added to Google Drive for dataset access.<br />
**2. Data Cleaning**
Removed unnecessary columns and handled missing values to prepare the data for analysis.<br />
**3. Feature Engineering**
Created new features like 'bhk' (bedrooms + hall + kitchen) and 'price_per_sqft'.<br />
**4. Outlier Detection and Removal**
Removed outliers using domain knowledge and statistical techniques.<br />
**5. Dimensionality Reduction**<br>
Applied dimensionality reduction to manage less frequent locations.<br />
**6. Model Building**<br>
Trained a Linear Regression model, selected for its performance over other algorithms tested.<br />
**7. Deployment**<br>
Saved the trained model using pickle and deployed a web interface using Gradio for predicting house prices based on location, square footage, bathrooms, and bedrooms.<br />

**Acknowledgments**<br>
Dataset: Kaggle - Bangalore House Prices Dataset<br />
Libraries Used: pandas, numpy, matplotlib, scikit-learn, Gradio<br />
