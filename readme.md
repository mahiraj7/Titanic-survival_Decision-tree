# Titanic Survival Prediction using Decision Tree

This is a beginner-friendly machine learning project that predicts whether a Titanic passenger survived.

## Algorithm
Decision Tree Classifier

## Dataset
Titanic Dataset (Kaggle)

## Input Features
- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

## Target
- Survived

## Files
- `train_model.py` → train the ML model
- `app.py` → Streamlit web app
- `data/train.csv` → Titanic dataset
- `models/decision_tree_model.pkl` → saved model
- `models/feature_columns.pkl` → saved training columns
- `models/median_age.pkl` → saved median age for missing values

## How to Run

### Install requirements
```bash
pip install -r requirements.txt
Train model
python train_model.py
Run Streamlit app
streamlit run app.py