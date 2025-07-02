# MoiraAlfred_20211486_w1911178_FinalSubmission
A predictive analytics system that forecasts undergraduate academic performance by integrating traditional student data with macroeconomic indicators using machine learning models. A machine learning pipeline for predicting student academic classifications using survey data. This project involves data preprocessing, feature engineering, model training, and interpretability techniques.

## Overview

This project aims to build a predictive model that classifies students into academic performance categories. The model is trained using self-reported survey data, incorporating various personal, educational, and environmental attributes. It is designed to assist educators, policymakers, and academic advisors in identifying at-risk students early.

## Dataset

- Data was collected through a structured online survey  
- Features include demographics, study behavior, academic background, and socioeconomic context  
- The dataset is tabular and primarily composed of categorical and ordinal variables  
- The target variable is the academic classification (e.g., First Class, Second Class Upper, etc)

## Preprocessing

- Cleaned and standardized raw data from the CSV format  
- Renamed attributes for clarity and usability  
- Handled missing values and invalid entries  
- Encoded categorical variables using label encoding and binarization techniques  
- Applied balancing techniques to address class imbalances  
- Engineered new features where appropriate  

## Feature Selection

- Identified and removed redundant or low-variance features  
- Selected high-importance features using statistical tests and model-based metrics  
- Ensured dimensionality is optimized for performance without overfitting  

## Modeling Approach

- Compared multiple classification algorithms  
- Evaluated models based on accuracy, precision, recall, and F1-score  
- Tuned hyperparameters using cross-validation  
- Selected the best-performing model for deployment and interpretation  

## Interpretability

- Used SHAP (Shapley Additive Explanations) to analyze model behavior  
- Visualized feature impact on predictions to enhance trust and transparency  
- Provided individual-level and global explanation plots  

## Objectives

- Identify students at risk of poor academic performance  
- Provide actionable insights into the drivers of academic success  
- Promote data-driven decision-making in educational planning  

## Limitations

- Based on self-reported data, which may include bias or inconsistency  
- Not generalizable across all institutions or educational systems without validation  
- Future versions may integrate behavioral or historical academic data for stronger predictions  

## License

This project is licensed under the MIT License
