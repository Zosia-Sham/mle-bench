# Data card

The dataset contains sentence-level text excerpts derived from public-domain horror fiction works and split using a sentence tokenizer. 

It includes train.csv (with columns: id, text, author), test.csv (with columns: id, text), and sample_submission.csv (template with columns: id, EAP, HPL, MWS). 

The label space has three classes: EAP (Edgar Allan Poe), HPL (H. P. Lovecraft), and MWS (Mary Wollstonecraft Shelley). 

Each row represents one excerpt identified by a unique id.

# Metric

LogLoss

# Description

Predict the author (Edgar Allan Poe, H. P. Lovecraft, or Mary Shelley) of each given text excerpt from horror fiction.
