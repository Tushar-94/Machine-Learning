# 🏠 Feature Engineering for House Prices
## Advanced Regression Techniques | Kaggle Project

## 📖 Introduction
This project is a complete feature engineering and modeling workflow built for the House Prices – Advanced Regression Techniques Kaggle competition.
It brings together the concepts learned in a Feature Engineering course and applies them to a real-world regression problem using the Ames Housing dataset.

The goal is to transform raw housing data into meaningful features that improve predictive performance and prepare a high-quality submission for Kaggle.

## 🛠️ Tech Stack
- Python
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing
Before feature engineering, the data is prepared to ensure consistency and usability:
- Load training and test datasets from CSV files
- Clean data to fix errors and inconsistencies
- Encode statistical data types (numerical & categorical)
- Handle missing values through imputation
- Split data into:
   - df_train → model training
   - df_test → final predictions for submission
     
All preprocessing steps are wrapped into reusable functions for efficiency and reproducibility.

### 2️⃣ Feature Utility Scores (Mutual Information)
To identify the most impactful features:
- Compute mutual information scores
- Measure the predictive power of each feature
- Visualize feature importance to guide feature creation
  
This helps focus effort on features with the highest potential.

### 3️⃣ Feature Creation
A modular feature engineering pipeline is built to:
- Transform raw features into model-ready inputs
- Create new features from existing variables
- Apply transformations consistently across datasets

This modular approach allows easy experimentation and extension.

### 4️⃣ Hyperparameter Tuning
To improve model performance:
- Tune XGBoost hyperparameters
- Optimize model complexity and learning behavior
- Reduce overfitting while improving generalization

### 5️⃣ Model Training & Submission
Final steps include:
- Generating the engineered feature set
- Training an XGBoost regression model
- Predicting house prices for the test dataset
- Exporting predictions to a CSV file ready for Kaggle submission


```python

```
