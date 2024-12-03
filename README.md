# Edible-Mushroom-Classification-CNN

This project focuses on building machine learning and deep learning models to classify mushroom images as either edible or poisonous. The primary challenge stems from the vast number of mushroom species and their diverse visual features, which make accurate visual identification difficult. Additionally, the project aims to evaluate the performance of various models given the constraint of a limited dataset.

## Dataset
The dataset for this study, sourced from Kaggle, contains over 3000 mushroom images. Among these, 1181 images are labeled as edible, and 2220 are identified as poisonous. The images vary in size, with most being approximately 250x250 pixels.

## Methods
Three classification methods were explored for this task: Random Forest, Kernel Support Vector Machines (Kernel SVM), and Convolutional Neural Networks (CNN). For the CNN approach, transfer learning was implemented using the pre-trained ResNet50 model.

## Results
- The **Random Forest algorithm** achieved perfect accuracy on the training set. After hyperparameter tuning, it attained a testing accuracy of 0.648.

- The **Kernel SVM algorithm** achieved a testing accuracy of 0.656, showing high training accuracy (0.940). However, its performance in predicting the 'edible' class could be further improved.

- The **CNN without transfer learning** showed moderate accuracy on the testing set. However, a significant gap between training and validation accuracies indicated overfitting.

- The **Transfer Learning** approach using the ResNet50 model underperformed. The model faced challenges in identifying meaningful patterns and delivering accurate predictions.

## Conclusion
Among the methods tested, the Random Forest algorithm delivered the most reliable results in terms of accuracy, precision, recall, F1-scores, and overall discriminatory power. However, further investigation and optimization are needed to improve the performance of the Transfer Learning approach and its ability to classify mushroom images effectively.

## References
The dataset is provided by Kaggle (https://www.kaggle.com/datasets/marcosvolpato/edible-and-poisonous-fungi/data).

