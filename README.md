# Handling Class Imbalance Using River ML Library

This project demonstrates various techniques for handling imbalanced datasets in machine learning, specifically using the River library. Imbalanced data is a common problem in binary classification tasks, such as fraud detection and spam classification, where one class significantly outnumbers the other.

## Techniques Covered
### Baseline Model

I used logistic regression to create a baseline model and evaluated its performance on imbalanced data.

### Importance Weighting

I Adjusted the loss function to give more importance to the minority class using weight_pos.

### Focal Loss

I Applied the focal loss function to address class imbalance.

### Under-sampling and Over-sampling

I used under-sampling to reduce the majority class and over-sampling to increase the minority class.

### Sampling with Desired Sample Size

I Combined under-sampling and over-sampling to control both class distribution and training data size.

### Hybrid Approach

I combined multiple techniques, such as under-sampling with importance weighting, for enhanced performance.
