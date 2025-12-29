# Data card

The dataset contains labeled training images and unlabeled test images of dogs, covering 120 distinct breeds. Each image filename serves as a unique `id`. 

Provided files include `train.zip` (training images), `test.zip` (test images), `labels.csv` (mapping from training `id` to breed label), and `sample_submission.csv` (required submission schema with one probability column per breed).

# Metric

LogLoss

# Description

Classify each dog photo into one of 120 dog breeds by predicting a probability distribution over all breeds for every test image.
