# Fetal Health Classification Using Random Forest

This project classifies fetal health status into three categories — **Normal**, **Suspicious**, and **Pathological** — using a **Random Forest** classifier.

## Objective

To build a classification model using the **Fetal Health dataset** from Kaggle that can help in early detection and classification of fetal health conditions based on 22 features collected from Cardiotocography (CTG) recordings.

- Dataset: [Kaggle - Fetal Health Classification](https://www.kaggle.com/datasets/andrewmvd/fetal-health-classification)
- Records: 2,126 samples  
- Target Classes: 
  - 1.0 - Normal
  - 2.0 - Suspicious
  - 3.0 - Pathological

## Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

## Data Preprocessing

- **Null Values**: No null values in the dataset
- **Duplicate Check**: Performed
- **Feature Standardization**: Applied to ensure consistent scale across features

## Model Training & Evaluation

- **Model Used**: Random Forest Classifier
- **Feature Importance**: Assessed to identify key contributing features
- **Correlation Matrix**: Used to visualize feature relationships

### Results

- **Training Accuracy**: 92.7%
- **Testing Accuracy**: 94.3%
- **Test Set Prediction (423 records)**:
  - 338 predicted as **Normal**
  - 33 predicted as **Suspicious**
  - 28 predicted as **Pathological**

## Conclusion

The Random Forest model effectively classifies fetal health status with high accuracy and provides insight into feature importance, making it a reliable tool for early fetal health screening.
