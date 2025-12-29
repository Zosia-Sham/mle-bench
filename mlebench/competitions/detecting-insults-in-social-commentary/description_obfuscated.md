# Data card

The dataset is provided as CSV files with one label column and two feature columns. 

The label is binary: 0 for neutral (not insulting) and 1 for insulting. Features include a comment timestamp in the format "YYYYMMDDhhmmss" (may be blank) and the comment text stored as a unicode-escaped string surrounded by double quotes. The text is mostly in English and may include formatting.

# Metric

AUC

# Description

Build a binary classifier that predicts the probability that an online conversation comment is an insult directed at another participant.
