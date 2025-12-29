# Data card

The dataset contains simulated manufacturing control data split into three CSV files: `train.csv`, `test.csv`, and `sample_submission.csv`. 

`train.csv` includes an `id` column, a set of normalized continuous and categorical features, and a binary label column named `target`. 

`test.csv` includes the same `id` column and feature columns as training data but does not include `target`. 

`sample_submission.csv` provides the required submission schema with columns `id` and `target`, where `target` is a predicted probability for each `id`.

# Metric

AUC

# Description

Predict a binary machine state 0 vs 1 from tabular, simulated manufacturing control features, producing a probability for the positive class for each test record.
