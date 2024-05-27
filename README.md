# multiclass_guava_classifier-three-
## Introduction
This project aims to classify three species of guava trees—Indonesian guava, green guava, and white guava—using a neural network model. Accurate classification of tree species is essential for agricultural management, biodiversity research, and botanical studies. The model is built using TensorFlow Keras and Scikit-learn.

## Dataset Description
The dataset consists of 120 samples, with 40 samples from each of the three guava species. Each sample includes the following features:
1. Area (cm²)
2. Ratio between length and width (length/width)
3. Petiole length (mm)
4. Number of vein pairs
5. Ratio between angle of veins

The data was split into training and testing sets using an 80-20 ratio, ensuring a robust evaluation of the model.

## Model Architecture
The neural network model has the following architecture:
1. **Input Layer:** 5 input features.
2. **First Hidden Layer:** Dense layer with 64 neurons and ReLU activation.
3. **Second Hidden Layer:** Dense layer with 32 neurons and ReLU activation.
4. **Output Layer:** Dense layer with 3 neurons and softmax activation, corresponding to the three guava species.
## Results
The model achieved the following performance on the test set:
- **Test Accuracy:** 1.0
- **Test Loss:** 0.0842
- ## Repository Contents
- `data.csv`: The dataset used for training and testing.
- `multiclass_classifier_three_guava.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
