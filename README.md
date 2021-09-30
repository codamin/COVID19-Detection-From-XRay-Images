# Visual Intelligence : COVID-19 Detection Using Deep Learning on Lung X-Ray Images
***Tools: Keras, Tensorflow***

## Goal: 
The purpose of this project is to create a 5-layer neural network as a classifier to distinguish COVID-19 cases from Pneumonia and Normal cases.

## Dataset: 
The dataset consists of 5144 images belonging to 3 classes of 1-COVID-19, 2-Pneumonia, and 3-Normal.

## Steps
- ***Data Transformation***: Transform each of the images into 80*80 grayscale images.
- ***Build The Model***: I used:
    - 5 layers with Relu as link function of the layers
    - Learning rate = 0.01
    - Batch Size = 32
    - Epoches = 10
    - Categorical Cross Entropy as loss function
    - User Accuracy, Recall, and F1-Score as evaluation metrics

- ***Link function impact***: Test Tanh instead of Relu as link function of the layers and interpret the results
- ***Normalization*** of the images
- User ***Optimizers*** and interpret the results:
    - Momentum
    - Adam
- Test with different numbers of ***epoches*** and interpret the results
- Use other ***loss functinos*** and interpret the results
- Use ***Regularization*** and interpret the results

## Results
We reached an accuracy of ***94%*** in 47 minutes with the best configuration. For more details please refer to to the jupyter notebook.