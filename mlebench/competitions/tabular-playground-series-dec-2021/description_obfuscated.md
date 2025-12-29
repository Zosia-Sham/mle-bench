# Data card

The dataset is a synthetic tabular dataset generated with CTGAN based on the original “Forest Cover Type Prediction” dataset. 

It includes a training split (train.csv) containing feature columns and the target column Cover_Type, a test split (test.csv) containing the same feature columns without the target, and a sample_submission.csv that shows the required submission format. 

Each test row is identified by an Id, and predictions must output one integer Cover_Type class per Id.

# Metric

CategorizationAccuracy

# Description

Predict the forest cover type (multi-class label) for each record in a tabular dataset using the provided feature columns.
