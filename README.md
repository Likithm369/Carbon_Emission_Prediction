🌍 Carbon Emission Prediction
(AI/ML Internship Project – June 2025 Batch)
📁 Project Description
This project was developed as part of the AI/ML Internship – June 2025 Batch. The primary goal was to analyze and prepare a climate dataset, focusing on CO₂ and other greenhouse gas emissions, and build a predictive model to forecast emission trends using machine learning techniques.

✅ Week 1 – Data Cleaning & Preparation (Completed on 18 June, 2025)
Worked with the original Excel dataset (Dataset.xlsx) without converting it to CSV

Loaded multiple sheets directly using pandas.read_excel()

Removed null values and unnecessary rows/columns

Explored the dataset’s structure to prepare it for ML use

Exported the cleaned version as data_clean.csv

No data merging or external transformation was done

📂 Files Included
data_preparation.ipynb → Data loading & cleaning notebook

Dataset.xlsx → Original provided dataset

data_clean.csv → Cleaned dataset

README.md → Summary notes

🛠 Tools Used
Python, Pandas, Jupyter Notebook

✅ Week 2 – Data Exploration & Visualization (Completed on 24 June, 2025)
Loaded data_clean.csv for analysis

Explored emission trends across countries and variables

Decoded column names and understood measurement units

Performed feature engineering by removing unimportant data

Visualized data using:

Correlation matrix heatmap

Scatterplots and histograms

Outlier detection through graphs

Identified dependencies and patterns within the dataset

📂 Files Included
data_exploration.ipynb → EDA, visualizations, and feature analysis

🛠 Tools Used
Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

✅ Week 3 – Predictive Modeling (Completed on 1 July, 2025)
Re-validated selected features based on Week 2 findings

Set CO₂ emission prediction as the target hypothesis

Chose final dependent and independent variables

Split dataset into training and testing sets

Applied Recursive Feature Elimination (RFE) with cross-validation

Trained a Random Forest Regressor with hyperparameter tuning

Evaluated the model using R² score and MAE to assess performance on test data

📂 Files Included
model_building.ipynb → ML model training and evaluation

Model/forecasting_co2_emmision.zip → Contains trained .pkl model file