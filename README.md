# worldcup2026-elo-model-predictor
Monte Carlo simulation model that predicts FIFA World Cup 2026 outcomes using ELO ratings.  Simulates all 104 matches across 100,000 tournament runs to generate win probabilities  for all 48 teams — covering group stage tiebreakers, Round of 32, and full knockout bracket. Built in Python with NumPy, Pandas, and Matplotlib.

# ⚽ FIFA World Cup 2026 — ELO Prediction Model

A Monte Carlo simulation model using ELO ratings to predict 
the winner of the 2026 FIFA World Cup.

## How it works
- Each of the 48 teams is assigned an ELO rating
- Win probability between any two teams is calculated using the ELO formula
- The full tournament is simulated 100,000 times
- Results show each team's probability of lifting the trophy

## Results
![Predictions Chart](elo%20predictor%20chart.png)

## Run it yourself
Open the notebook in Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19cntEXtI-kKXzjss-6fl6B7_ri3Odr4v?usp=sharing)
