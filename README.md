# Marketplace Demand Forecasting + Supply Simulator

## Project Overview
This project builds a demand forecasting model and simulates marketplace supply decisions under different capacity policies.

## Key Components
- Random Forest demand forecasting model
- Marketplace queue simulation
- Capacity policy comparison (-10%, Base, +10%, +20%)
- Cancellation penalty sensitivity analysis
- Profit optimization analysis

## Business Question
What is the optimal capacity level under different cancellation penalties?

## Results Summary
- +10% capacity optimal for low cancellation penalties (< ~$7.45)
- +20% capacity optimal when penalty per cancellation is high
- Clear tradeoff between capacity cost and cancellation loss

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SciPy

## How to Run
Install requirements:

pip install -r requirements.txt

Then run the notebook.

---

Author: Pooja Chavan Patil
