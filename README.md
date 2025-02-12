# breast-cancer-detection-system

## Overview
This project utilizes Machine Learning techniques to classify breast cancer cases as Malignant (M) or Benign (B) based on medical diagnostic data. Using the UCI Machine Learning Repository dataset, various preprocessing steps, feature scaling, and classification algorithms are applied to build an accurate predictive model.

## Phases of Implementation
### Phase 0 — Data Preparation
The Breast Cancer dataset from the UCI Machine Learning Repository is used for training and testing.
The dataset is imported into Google Colab for preprocessing and model training.

### Phase 1 — Data Exploration
Necessary libraries are imported (pandas, numpy, seaborn, matplotlib).
The dataset is loaded into Google Colab for analysis.
Basic dataset inspection includes checking for missing values, data types, and feature distribution.

### Phase 2 — Handling Categorical Data
Categorical variables contain label values instead of numeric values.
These variables are encoded to facilitate numerical processing in Machine Learning algorithms.

### Phase 3 — Feature Scaling
Features in the dataset may vary in magnitudes, units, and range.
Since many Machine Learning models rely on Euclidean distance, it is necessary to scale features for uniformity.
Standardization or normalization is applied to transform data into a specific range.

### Phase 4 — Model Selection
Supervised Learning is used since the dataset contains labeled output variables (M or B).
The classification problem involves predicting whether a tumor is Malignant or Benign.
Several classification algorithms are tested to find the best-performing model.

## Machine Learning Approach
### Classification Algorithm Used: Supervised Learning
Outcome Variable (Y):
M → Malignant (Cancerous)
B → Benign (Non-cancerous)

The model is trained to accurately classify tumors based on input features.

## Technologies Used
- Python
- Google Colab
- Pandas, NumPy (Data Handling)
- Seaborn, Matplotlib (Data Visualization)
- Scikit-learn (Machine Learning Algorithms)
  
## Applications
✔️ Early detection of breast cancer
✔️ Assisting medical professionals in diagnosis
✔️ Automating cancer classification for efficiency
✔️ Enhancing predictive accuracy using ML techniques

Dataset : https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

# Model Summary
![image](https://github.com/user-attachments/assets/b831bc40-00b8-42ae-b68a-6f0cc2c0db13)

# Training and Validation Accuracy and Loss Values
![image](https://github.com/user-attachments/assets/a7a120a9-3789-4b73-b858-aa4ba2c26cf6)

In Model accuracy graph A validation accuracy is always greater than train 
accuracy that means our model is not overfitting. 
In Model accuracy graph A validation loss is also very lower than training loss so 
unless and until validation loss goes above than the training loss than we can keep 
training our model.

