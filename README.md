# Skin Cancer Detection Using CNN
> Build a Convolutional Neural Network (CNN) to accurately detect melanoma, a deadly form of skin cancer.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project aims to detect melanoma using CNNs. Melanoma accounts for 75% of skin cancer deaths but can be treated effectively if detected early.
- The dataset consists of 2357 images divided into nine classes of skin cancer, with separate train and test directories.
- Data augmentation and preprocessing techniques were used to address class imbalance and improve model performance.

## Conclusions
- The model achieved reasonable accuracy after tuning, including adding dropout layers, batch normalization, and class balancing techniques.
- Overfitting was reduced by applying data augmentation and increasing dropout rates.
- Augmentor was used to rectify class imbalance by generating additional images for underrepresented classes.
- The model demonstrates the feasibility of using CNNs for early melanoma detection but requires further improvements for clinical applications.

## Technologies Used
- Python 3.8
- TensorFlow 2.x
- NumPy 1.21
- Pandas 1.3
- Matplotlib 3.4
- Augmentor 0.2

## Acknowledgements
- This project was inspired by medical challenges in melanoma detection.
- Dataset: Provided as part of the assignment.
- Based on techniques outlined in [TensorFlow's Image Classification Guide](https://www.tensorflow.org/tutorials/images/classification).

## Contact
Created by [@suddhasish] - feel free to contact me!

