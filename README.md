# AQI Predictor 🌫️

Predicts Air Quality Index (AQI) for Indian cities using Machine Learning.

## Results
| Model | MAE | R2 Score |
|-------|-----|----------|
| Linear Regression | 31.54 | 0.80 |
| Random Forest | 20.36 | 0.88 ✅ |
| XGBoost | 21.53 | 0.88 |

## Key Findings
- PM2.5 and CO together explain 83% of AQI
- Random Forest performed best with R2 = 0.88
- Lucknow and Patna among most polluted cities

## Dataset
[Air Quality Data in India](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
29,531 rows of real Indian city data (2015-2020)

## Tech Stack
Python, Scikit-learn, XGBoost, Pandas, Matplotlib, Joblib

## How to Run
1. Clone this repo
2. Upload city_day.csv in Colab
3. Run all cells in aqi_predictor.ipynb
