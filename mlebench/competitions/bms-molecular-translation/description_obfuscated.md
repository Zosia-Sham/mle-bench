# Data card

The dataset contains millions of images depicting chemical structures using skeletal formula notation. Images may vary in orientation, resolution, and noise levels.

Training data includes images paired with their corresponding ground-truth InChI strings, while test data contains images without labels. Images are stored in a hierarchical folder structure indexed by image_id.

Submissions require predicting a single InChI string for each test image, matching the molecular structure shown.

# Metric

Levenshtein distance

# Description

Translate images of hand-drawn or scanned chemical structures into machine-readable InChI text strings to enable automated search and analysis of chemical literature.
