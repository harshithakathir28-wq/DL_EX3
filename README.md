# Experiment 3: CNN Image Classification

## Aim

To design, implement, and evaluate a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 benchmark dataset.

## Tools and Technologies

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## Dataset

The CIFAR-10 dataset contains 60,000 color images of size 32 × 32 pixels belonging to 10 different classes.

### Classes

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Tasks Performed

### Task A – Dataset Preparation

* Loaded the CIFAR-10 dataset.
* Normalized pixel values between 0 and 1.
* Split the training data into training and validation sets.
* Visualized sample images from the dataset.

### Task B – CNN Model

The CNN architecture consists of:

* Convolutional Layer with 32 filters
* ReLU Activation
* Max Pooling
* Convolutional Layer with 64 filters
* ReLU Activation
* Max Pooling
* Flatten Layer
* Fully Connected Dense Layer
* Softmax Output Layer

The model was compiled using the Adam optimizer and sparse categorical cross-entropy loss.

### Task C – Model Training

* Trained the CNN for 10 epochs.
* Used a batch size of 64.
* Recorded training and validation accuracy.
* Recorded training and validation loss.
* Evaluated the model using the test dataset.
* Plotted accuracy and loss curves.

### Task D – Model Evaluation

* Generated a confusion matrix.
* Displayed sample predictions.
* Identified misclassified images.
* Analyzed the performance of the CNN.

## Results

The CNN successfully classified images from the CIFAR-10 dataset. Training and validation accuracy, loss curves, testing accuracy, confusion matrix, and misclassified images were analyzed to evaluate model performance.

## Conclusion

A Convolutional Neural Network was successfully implemented for image classification using the CIFAR-10 dataset. The experiment demonstrated how convolution, pooling, and fully connected layers work together to extract image features and classify images into different categories.
