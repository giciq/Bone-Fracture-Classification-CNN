# Bone-Fracture-Classification

The file with extension ".ipynb" contains a code which provides taken steps to create a model for classificating bone fracture images.
The dataset used for the model: https://www.kaggle.com/datasets/pkdarabi/bone-break-classification-image-dataset

Models created:
* Simple CNN's model
* Feature Extraction model using EfficientNetV2 with data augmentation
* Fine-tuned, above model with data augmentation

The models were evaluated using:
* confusion matrix
* loss and accuracy curve plots
* precision, accuracy, recall and F1-score metrics

The last model achieves accuracy around 40%. 
It is because of the size of dataset that is quite small. 
Better dataset would result in better accuracy, for sure.
