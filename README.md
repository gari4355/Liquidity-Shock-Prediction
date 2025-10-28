# Liquidity Shock Prediction

This repository contains an exploratory Jupyter notebook for predicting liquidity shocks. The main artifact is:

- `Liquidity_shock_prediction.ipynb` — the primary notebook containing data loading, preprocessing, modelling experiments, and evaluation.

## Project overview

The notebook implements an end-to-end exploratory workflow to investigate and model liquidity shocks using historical financial data. It contains data preparation steps, feature engineering, model training and evaluation, and visualizations.

## Files

- `Liquidity_shock_prediction.ipynb` — Jupyter notebook with analysis and model experiments.
- `README.md` — this file.

(If you add datasets, place them in a `data/` folder and update the notebook paths accordingly.)

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

If you need a `requirements.txt`, you can generate one from your active environment with:

```powershell
pip freeze > requirements.txt
```

## Data

- This repo currently does not include raw data. Place your CSVs or other data files in a `data/` directory and update the notebook's data-loading paths.
- Keep sensitive or proprietary data out of the repository and instead provide sample data or data schemas for reproducibility.

## Results and experiments

- The notebook includes multiple modelling experiments and visualizations. Use separate branches or notebooks for large experiments to keep the main notebook tidy.

## Next steps (suggestions)

- Add a `requirements.txt` or `environment.yml` for reproducible environments.
- Add a small example dataset (or synthetic data generator) so others can run the notebook without private data.
- Break out preprocessing and modelling into Python modules for reuse and unit testing.
- Add minimal automated tests (e.g., validate data-loading and preprocessing functions).

## Contributing

1. Fork the repo and create a branch for your feature.
2. Open a PR with a clear description of changes.

## License

Add a LICENSE file to indicate how the project may be used. If you don't have a preference, consider an OSI-approved license such as MIT.

---

If you'd like, I can also:
- generate a `requirements.txt` based on the notebook imports,
- add a small synthetic example dataset and update the notebook to load it,
- or create a short CONTRIBUTING.md and LICENSE file.

Tell me which of those you'd like next.