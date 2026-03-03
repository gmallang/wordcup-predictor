# 2026 FIFA World Cup Predictor

A machine learning model that predicts the outcome of the 2026 FIFA World Cup using historical international football data.

## How it works
Data was cleaned by removing friendly matches and converting dates. Features were engineered from 49,000+ historical matches including win rate, recent form, average goals scored/conceded, goal differential, and head-to-head records. Two models were trained and compared — Random Forest (54%) and XGBoost (58%) — with XGBoost selected for the final simulation. The model was applied to simulate the full 2026 World Cup tournament including group stage and knockout rounds.

## Tech Stack
Python, pandas, scikit-learn, XGBoost

## How to run it
1. Clone the repo
2. Download `results.csv` from [Kaggle](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017) and place it in the `data/` folder
3. Run `pip install -r requirements.txt`
4. Open and run `notebooks/04_tournament_simulator.ipynb`

## Results
France beats Spain in the 2026 World Cup Final. XGBoost model achieves 58% prediction accuracy.