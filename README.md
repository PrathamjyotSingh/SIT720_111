# Heart Attack Prediction: Stacking Ensemble

This project reproduces a stacking-based ensemble for heart attack prediction and evaluates an improved leakage-aware machine learning pipeline.

## Files

* `heart_attack_stacking.ipynb`: Part 1 reproduction of the original stacking approach.
* `leakage_aware_pipeline.ipynb`: Part 2 improved pipeline with leakage investigation, cross-validation, and hyperparameter tuning.
* `heart.csv`: Cleveland heart disease dataset used for the experiments.
* `requirements.txt`: Required Python packages and versions.

## Requirements

Python 3.10 or later is recommended.

Install dependencies with:

```bash
pip install -r requirements.txt
```

## Running the Notebooks

1. Install the required packages.
2. Place all files in the same folder.
3. Open `heart_attack_stacking.ipynb` and run all cells.
4. Open `leakage_aware_pipeline.ipynb` and run all cells.

The notebooks generate the reported model results, evaluation metrics, and figures.

## Reproducibility

The experiments use `random_state = 42`. The dataset and required dependencies are included to support reproduction of the results.
