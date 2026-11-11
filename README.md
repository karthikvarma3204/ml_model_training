# Predictive Modeling — Linear Regression Exercise

An introductory regression notebook using pandas and scikit-learn.

## What it does
- Loads a CSV with three numerical input variables and a numeric target
- Splits records into training and test sets
- Fits a LinearRegression model
- Calculates MAE and MSE
- Saves a fitted model to `ml_model.pkl`

## Run
```bash
python -m pip install -r requirements.txt
jupyter notebook ml_model_training.ipynb
```

## Files
- `ml_model_training.ipynb` — analysis and training steps
- `ml_dataset.csv` — illustrative data
- `ml_results.txt` — previously recorded results
- `ml_model.pkl` — existing serialized model

Do not load serialized models from untrusted sources. This is a small learning example with generic synthetic-style features, not a validated production forecasting system.
