## Predictive Maintenance — Aircraft Engine (scikit‑learn/XGBoost)

### Overview
Binary classification to predict if an engine will fail within the next N cycles using the Azure AI turbofan dataset. The notebook explores data, engineers features, trains baseline and tree‑based models, and evaluates accuracy/F1.

### Repository structure
- `PredictiveMaintenanceAircraft.ipynb`: EDA, feature engineering, modeling
- `PM_train.txt`, `PM_test.txt`, `PM_truth.txt`: dataset files

### How to run
1. Open `PredictiveMaintenanceAircraft.ipynb` in Jupyter.
2. Run cells to load data, explore cycles/sensors, train models, and evaluate.

### Requirements
- Python 3.9+
- pandas, numpy, matplotlib, seaborn, scikit‑learn, xgboost, plotly

### Results
- Example XGBoost run: Accuracy ~93%, F1 ~96% predicting 20‑cycle horizon

### Next steps
- Reduce overfitting via feature selection and regularization
- Try alternative models (SVM, neural networks)
- Experiment with different prediction horizons or regression (RUL)
- Package an inference endpoint for deployment
