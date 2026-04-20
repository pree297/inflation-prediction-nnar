# Inflation Prediction System

This is a final year project for building an inflation prediction system using machine learning and actual monthly CPI data.

## Features

- Predict annual average inflation using monthly data
- Preprocess and clean the provided CSV dataset
- Train a stronger regression model on real inflation statistics
- Streamlit app for interactive prediction

## Setup

1. Create virtual environment: `python -m venv venv`
2. Activate: `venv\Scripts\activate` (Windows)
3. Install dependencies: `pip install -r requirements.txt`
4. Run training: `python model-training.py`
5. Run app: `streamlit run app.py`

## Files

- `app.py`: Streamlit web app for prediction
- `model-training.py`: Script to preprocess the CSV and train the model
- `models/`: Saved trained model file
- `data/`: Dataset folder containing the inflation CSV

## Requirements

- Python 3.8+
- streamlit
- pandas
- numpy
- scikit-learn
- joblib
- matplotlib