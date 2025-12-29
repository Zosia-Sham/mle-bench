# Data card

The dataset consists of RNA sequences designed through the Eterna platform and experimentally characterized at Stanford University. Each sample includes an RNA sequence of length 107 composed of A, G, U, and C bases, along with its predicted secondary structure and loop-type annotations.

Ground-truth measurements are provided for the first 68 positions of each sequence (seq_scored). These measurements include reactivity and degradation rates under multiple experimental conditions: with or without magnesium, at high pH (pH 10), and at elevated temperature (50 °C). Corresponding experimental error estimates are also included.

The training set contains RNA sequences with full ground-truth measurements, while the test set contains sequences without target values.

For submission, predictions must be provided for every position of each test sequence, including positions that are not scored.

# Metric

MCRMSE

# Description

Predict base-level RNA degradation and reactivity profiles for mRNA vaccine candidates using sequence and secondary-structure information, to support the design of more stable COVID-19 mRNA vaccines.
