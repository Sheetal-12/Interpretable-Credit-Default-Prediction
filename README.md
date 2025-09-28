# Interpretable-Credit-Default-Prediction

## Step 8: Permutation Importance
Computed using sklearn.inspection.permutation_importance.
Measures the drop in model performance when a feature’s values are randomly shuffled.
Results:
num__funded_amnt was the single most important predictor.
Other features like num__revol_bal, num__bc_util, and num__annual_inc added moderate predictive value.
A long tail of smaller features contributed incremental improvements.
Cumulative analysis showed it takes ~30 features to cover 80% of total predictive power → importance is spread across many features.
