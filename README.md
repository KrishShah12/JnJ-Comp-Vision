# Histopathological Image Classification

This repository contains code for the MHIST image classification project, where the primary model utilized is ResNet-18. The project involves training a classifier to predict whether an image belongs to one of two classes: Hyperplastic Polyp (HP) or Sessile Serrated Adenoma (SSA). Implemented two strategies to address the imbalanced dataset: under-sampling and weighted random sampling.

Code Files:
1. Weighted_Random_Sampling.ipynb: In this notebook, you'll find code for implementing weighted random sampling during the training process. Weighted random sampling assigns higher probabilities to samples from underrepresented classes, effectively addressing class imbalance issues.
2. Under_Sampling.ipynb: This notebook contains code for under-sampling the dataset, a technique used to balance class distribution by randomly removing samples from the majority class until class proportions are equalized.

GradCam was used to generate heatmaps on 5 sample images on the test set to highlight the important regions that the model used to make predictions.
