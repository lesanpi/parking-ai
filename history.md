# Baseline.
Test: 0.9604 (96.04%)
Error: 0.0396 (3.96%)

# Data Augmentation.
Test: 0.9563 (95.63%)
Error: 0.0437 (4.37%)

###  Transforms:
- HorizontalFlip(),
- ToSepia(),
- GridDistortion(),
- ChannelShuffle()
