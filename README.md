# The multi label skin diseases classification (Dermnet)

The 19500 images of 23 types of skin diseases from Kaggle 
https://www.kaggle.com/shubhamgoel27/dermnet

1. skin_diseases_classification_ResNet50 - surpevised learning.
2. skin_diseases_classification_DINO - unsurpervised leaning based on transformer + codistillation.
  The code is based on https://github.com/facebookresearch/dino
  
The dataset is devided as Train/Val/Test: 15557/2001/2001.

The ResNet50 gives the accuracy 0.64, it may be increased by additional augmentation and using the CNN ensemble (for examlple, the ensemble of ResNet-152,
DenseNet-161, SE-ResNeXt-101 and NASNet).

The DINO + kNN-classification gives the accurasy about 0.60 and may be increase by more apropriate augmentation and using larger unlabeled datasets.
