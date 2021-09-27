# Skin Cancer Image Classification

## Problem statement¶
Aim of this project is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Methodology
Model development is divided into multiple steps as mentioned below,

- Train-val split: This step involves spliting the dataset into train and validation parts.
- Data Visualization: This step involves visualizing our dataset. We can also check number of images availalbe for each class.
- Model Development: This steps involves training the model and validate it. It involves evaluating the model using relevant matrics.
- Data Augmentation: This part involves data augmentation and balancing the dataset amongst various classses. Here we generally rotate or flip or change color intensity/brightness or change color weights etc for the images. It increases the size of the dataset and improves the model against overfitting problem.
- Model Development (on augmented dataset): This steps involves training the model and validate it. It involves evaluating the model using relevant matrics.
- Conclusion/Recommendation: It involves drawing conclusions and recommendations to business.
