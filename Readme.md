# Multiclass Classification Model using a custom convolutional neural network in TensorFlow

- This project involves building a Convolutional Neural Network (CNN) to classify skin cancer images.


## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information

- Project is undertaken as one of the Assignments for UpGrad PG Program in Machine Learning and AI
- Goal of the project is to develop an Machine Learning Model that can evaluate images and alert the dermatologists about the presence of melanoma
- Melanoma is a type of cancer that can be deadly if not detected early.It accounts for 75% of skin cancer deaths
- This model uses a dataset of about 2357 images of skin cancer types. The dataset contains 9 sub-directories in each train and test subdirectories. The 9 sub-directories contains the images of 9 skin cancer types respectively.
- The data set contains the following diseases:

    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion

- Key Steps and Methodology

- Data Preparation:

    - The dataset was structured into training and testing directories, each containing subdirectories for each class.
    - Data augmentation was applied using the Augmentor library to enhance the training dataset and improve model robustness.

- Model Architecture:

    - A Sequential CNN model was built using TensorFlow and Keras.
    - The model consisted of multiple convolutional layers followed by max-pooling layers, and fully connected layers, ending with a softmax output layer.

- Model Training:

    - The model was compiled with the Adam optimizer and a sparse categorical cross-entropy loss function.
    - It was trained for several epochs, with accuracy and loss monitored on both training and validation data.

- Evaluation:

    - The model’s performance was evaluated using metrics such as accuracy on the test dataset.
    - Training and validation accuracy and loss were plotted to observe the learning curves and check for overfitting or underfitting.

## Technologies Used
The following libraries and their versions were used in this project:

- TensorFlow version: 2.15.0
- NumPy version: 1.25.2
- Pandas version: 2.0.3
- Matplotlib version: 3.7.1
- Pillow version: 9.4.0
- Augmentor version: 0.2.12

## Conclusions
- Following three different Models are built under the project : 
    - Basic CNN Model with Augementation & Dropout
    - CNN Model with Augementation & Dropout 
    - CNN Model After Rebalancing of Classes 

- The final model achieved a training accuracy of 91% and a validation accuracy of 80%.
- The learning curves indicated that the model was learning effectively, with training and validation accuracy improving over epochs.
- Augmentation techniques helped in preventing overfitting to some extent 
- Class Rebalancing enhanched the performance of the model to great extent  

## Acknowledgements

- International Skin Imaging Collaboration (ISIC) for compilation of the given dataset
- UpGrad Team for guidance and setting up the base code for learning


## Contact
Created by [@hims-pg] - feel free to contact me!

