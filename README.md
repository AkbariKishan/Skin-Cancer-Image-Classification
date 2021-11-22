# Skin Cancer Image Classification

## Problem statement¶
CBAM: Convolution Block Attention Module

CBAM Paper: https://arxiv.org/pdf/1807.06521.pdf

Here we are implementing CBAM based model for image classification purpose. CBAM is CNN + Attention based block which utilizes the soft attention on the extracted features by Convolution. Attention is applied across the features/channels (weighting the channel improtance) as well as on each feature/channel (weighting the location on each feature).

CBAM block is used to modify the Resnet based architencture. Resnet gives very good results as depth of the network is increased with the help of skip connection residue modelling approach. For more: https://arxiv.org/abs/1512.03385

## Methodology
Model development is divided into multiple steps as mentioned below,

- Data Augmentation: This part involves data augmentation and balancing the dataset amongst various classses. Here we generally rotate or flip or change color intensity/brightness or change color weights etc for the images. It increases the size of the dataset and improves the model against overfitting problem.
- Model Development (on augmented dataset): This steps involves training the model and validate it. It involves evaluating the model using relevant matrics.
- Conclusion/Recommendation: It involves drawing conclusions and recommendations to business.
