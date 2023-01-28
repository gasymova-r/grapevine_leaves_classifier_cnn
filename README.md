# Grapevine Leaves Classifier using CNN

## About the project

This computer vision project attempts to recreate some of the research findings from the following article:
Koklu, M., Unlersen, M. F., Ozkan, I. A., Aslan, M. F., & Sabanci, K. (2022). A CNN-SVM study based on selected deep features for grapevine leaves classification. Measurement, 188, 110425. Doi:https://doi.org/10.1016/j.measurement.2021.110425

Images for classification were taken using Kaggle API (https://www.kaggle.com/datasets/muratkokludataset/grapevine-leaves-image-dataset), dataset includes 100 images per 5 species of grapevine leaves (Ak, Ala Adris, Buzgulu, Dimnit and Nazli).

## Used methods
Project:
1. utilizes image augmentation to create more training data
2. attempts to use transfer learning to improve results
3. applies Keras Tuner for Hyperparameter Tuning
4. allows to test predictions on five random images from the dataset

## Image examples


## Results
A model created is able to classify five kinds of grapevine leaves with over 80% validation accuracy. The best performing model was achieved using Hyperparameter Tuning.

## Future work
In order to further improve the results we need to continue experimentation and attempt:
1. Hyperparameter Tuning with more parameters
2. Application of CNN-SVM Cubic model proposed by the aforementioned article.
