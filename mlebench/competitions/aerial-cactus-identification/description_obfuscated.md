# Data card

Modality: RGB aerial imagery thumbnails  

Task type: Supervised binary image classification

Image size: 32 x 32 pixels (uniformly resized)  

Labels: `has_cactus` where 1 indicates the image contains a cactus and 0 indicates it does not  

Training data: `train/` image directory and `train.csv` with filenames (`id`) and labels  

Test data: `test/` image directory with filenames (`id`) and no labels provided  

Submission format: CSV with columns `id,has_cactus`, where `has_cactus` is a predicted probability for each test image.

# Metric

AUC

# Description

Build a binary classifier that predicts whether a 32 x 32 aerial thumbnail image contains a columnar cactus (Neobuxbaumia tetetzo).
