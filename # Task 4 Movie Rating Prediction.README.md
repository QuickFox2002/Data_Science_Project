# Task 4: Movie Rating Prediction

## Objective
Predict how a user might rate a movie they have not yet rated.

## Dataset
- **Source:** [MovieLens Latest Small ratings.csv](https://raw.githubusercontent.com/smanihwr/ml-latest-small/master/ratings.csv)
- Loaded directly from GitHub (no local download required)
- Columns:
  - `userId` — Unique user identifier
  - `movieId` — Unique movie identifier
  - `rating` — Rating given by the user (0.5–5.0)
  - `timestamp` — Unix timestamp of rating

## Methodology
1. Load dataset from GitHub.
2. Encode `userId` and `movieId` into numeric values for modeling.
3. Train a **RandomForestRegressor** to predict ratings.
4. Evaluate using **RMSE** (Root Mean Squared Error).
5. Make example predictions for a specific user and movie.

## How to Run
Install dependencies:
```bash
pip install pandas numpy scikit-learn
