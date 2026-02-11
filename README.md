# Liquidity Shock Prediction

This repository contains an exploratory Jupyter notebook for predicting liquidity shocks. The main artifact is:

- `Liquidity_shock_prediction.ipynb` — the primary notebook containing data loading, preprocessing, modelling experiments, and evaluation.

## Project overview

The notebook implements an end-to-end exploratory workflow to investigate and model liquidity shocks using historical financial data. It contains data preparation steps, feature engineering, model training and evaluation, and visualizations. It also predicts real time stock data. 


## Quick start (Windows PowerShell)

1. Create a Python environment (recommended):

```powershell
python -m venv .venv; .\.venv\Scripts\Activate.ps1
```

2. Install recommended packages (adjust as needed):

```powershell
pip install --upgrade pip
pip install jupyter pandas numpy scikit-learn matplotlib seaborn notebook
```

3. Run Jupyter Notebook and open the notebook file:

```powershell
jupyter notebook "Liquidity_shock_prediction.ipynb"
```

4. Follow the notebook cells. Update any file paths to point to your local dataset.

## Dependencies

The notebook was developed using common data science libraries. Typical packages include:

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter / notebook


## Results and experiments

- The notebook includes multiple modelling experiments and visualizations.
  

## Contributing

1. Fork the repo and create a branch for your feature.
2. Open a PR with a clear description of changes.
