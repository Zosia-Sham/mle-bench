# Data card

The dataset consists of 16-bit grayscale MRI scan slices collected from cancer patients undergoing radiation therapy. Each patient case includes multiple scans acquired on different treatment days.

Ground truth annotations are provided as run-length encoded segmentation masks for three anatomical structures: stomach, small bowel, and large bowel.

Training data includes scan images and corresponding segmentation labels, while the test data contains only scan images and requires predicted segmentation masks in the same encoded format.

# Metric

Mean Dice coefficient and 3D Hausdorff distance

# Description

The task is to automatically segment the stomach and intestinal organs from MRI scans of cancer patients to support faster and more precise radiation therapy planning.
