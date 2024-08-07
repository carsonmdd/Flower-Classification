# Flower-Classification
## Basic Overview
This flower classification project utilizes a convolutional neural network (CNN) to classify images of flowers among 16 different species.
## Methods
Once the data was retrieved, I organized the data into a dataframe for manageability and visualization. After viewing some of the data points, I split the data and incorporated data augmentation to help prevent overfitting. Following data preprocessing, I constructed my model with four convolutional layers and fit it over 30 epochs. I then graphed the resulting losses and accuracies and evaluated the model. Upon saving, I used the model to predict 16 new flower images (one for each species) and visualized the results.
## Accuracy of the CNN model
Validation accuracy: 83.10% \
Testing accuracy: 82.97%
## Dataset
Total images: 15,740 \
Total classes: 16 \
Dataset: https://www.kaggle.com/datasets/l3llff/flowers/data
