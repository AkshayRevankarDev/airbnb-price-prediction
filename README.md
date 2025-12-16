# Airbnb Price & Booking Prediction (Extra Credit)

This project explores temporal dynamics in Airbnb data across four major cities (Austin, Chicago, Santa Cruz, Washington DC). It constructs a night-level panel dataset to analyze seasonality and trains machine learning models (XGBoost and Neural Networks) to predict nightly prices and booking probabilities.

## Project Structure
- `Airbnb_Analysis.ipynb`: The main notebook containing data processing, analysis, modeling, and results.
- `requirements.txt`: List of Python dependencies.
- `logs/`: Directory containing TensorBoard training logs.
- `Dataset/`: (Created at runtime) Stores raw CSV files.

## Installation
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the notebook:
   ```bash
   jupyter notebook Airbnb_Analysis.ipynb
   ```
2. Run all cells. The notebook will automatically download the required datasets from InsideAirbnb.

## key Features
- **Temporal Analysis:** Seasonality plots for price and occupancy.
- **Advanced Modeling:** Comparative analysis of XGBoost vs. Neural Networks.
- **Strict Evaluation:** Time-series split (Train: Mar-Sep, Valid: Oct-Nov, Test: Dec-Feb) to prevent data leakage.
