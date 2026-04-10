# Exoplanet Habitability Prediction AI

Machine learning system for analyzing exoplanet candidates using NASA data and predicting potential habitability.

---

## Overview

This project implements an end-to-end machine learning pipeline for analyzing exoplanet candidates using real data from NASA Exoplanet Archive.

The system retrieves astrophysical data via API, processes and engineers features, and applies machine learning models to estimate the potential habitability of exoplanets.

The project focuses on combining data engineering, feature processing, and model optimization to simulate real-world scientific data analysis workflows.

---

## Data Source

- NASA Exoplanet Archive API
- Real-time retrieval of candidate exoplanet data
- Filtering based on candidate status

---

## Key Features

- Automated data retrieval via API (requests)
- Data preprocessing and cleaning
- Feature selection and engineering
- Feature normalization (StandardScaler)
- Categorical encoding (One-Hot, Label Encoding)
- Synthetic data balancing using SMOTE
- Binary classification for habitability prediction
- Model training and evaluation
- Hyperparameter optimization (GridSearchCV)
- Visualization and exploratory analysis

---

## Machine Learning Pipeline

1. Data Collection  
   - Fetching candidate exoplanet data from NASA API  

2. Data Preprocessing  
   - Cleaning missing values  
   - Selecting relevant astrophysical features  

3. Feature Engineering  
   - Creating derived features  
   - Generating binary labels (habitability threshold)  

4. Data Transformation  
   - Feature scaling  
   - Encoding categorical variables  

5. Data Balancing  
   - SMOTE oversampling for class imbalance  

6. Model Training  
   - Random Forest classifier  

7. Hyperparameter Optimization  
   - GridSearchCV for tuning model parameters  

8. Evaluation  
   - Classification report (precision, recall, F1-score)  

9. Prediction  
   - Generating habitability predictions for candidate exoplanets  

---

## Experiments

The project includes multiple experimental approaches:

- Different feature configurations  
- Binary classification strategies  
- Synthetic data generation for training stability  
- Hyperparameter tuning across multiple configurations  

---

## Example Output

- Predictions for real NASA exoplanet candidates  
- Classification of planets as:
  - **Habitable**
  - **Not Habitable**

---

## Tech Stack

- Python  
- Pandas / NumPy  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Seaborn / Matplotlib  
- Requests (API integration)  

---

## Research Focus

- Scientific data analysis using real-world datasets  
- Habitability estimation based on astrophysical features  
- Handling imbalanced datasets in classification tasks  
- Feature engineering for space-related data  
- Model optimization and evaluation  

---

## Applications

- Exoplanet habitability research  
- Scientific data analysis pipelines  
- Machine learning in astrophysics  
- Space data exploration  

---

## Limitations

- Some experiments use synthetic features for demonstration purposes  
- Model accuracy may be influenced by simplified assumptions  
- Further validation on curated datasets is required  

---

## Future Work

- Use real labeled habitability datasets  
- Apply deep learning models for sequence and pattern analysis  
- Improve feature engineering using domain knowledge  
- Deploy as an interactive analysis tool  
- Integrate visualization dashboards  

---

## Author

Svetlana Rumyantseva  
AI Systems Engineer
