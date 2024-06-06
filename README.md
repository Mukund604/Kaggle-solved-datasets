# Kaggle Datasets Projects

This repository contains various projects where I have solved Kaggle datasets using different machine learning and deep learning techniques. Below is a brief description of each project:

## 1. Bone Fracture Classification
**Notebook:** [98-accuracy-binary-classification-bone-fracture.ipynb](98-accuracy-binary-classification-bone-fracture.ipynb)

This project focuses on developing a binary classification model to detect bone fractures from X-ray images. The following steps are involved:

- **Data Preprocessing:** The dataset is cleaned and preprocessed, including resizing images and normalizing pixel values.
- **Model Architecture:** A Convolutional Neural Network (CNN) is designed with multiple layers to effectively extract features from the images.
- **Training and Validation:** The model is trained on a dataset of labeled X-ray images and validated to ensure its accuracy.
- **Performance:** Achieves an impressive 98% accuracy in classifying images as fractured or not fractured.

## 2. Alzheimer MRI Scans Classifier using CNN
**Notebook:** [alzheimer-mri-scans-classifier-using-cnn.ipynb](alzheimer-mri-scans-classifier-using-cnn.ipynb)

This project aims to classify MRI scans to detect the presence and severity of Alzheimer's disease. The steps involved are:

- **Data Importing:** Loading the dataset of MRI scans, which are labeled as Mild Demented, Moderate Demented, Non Demented, or Very Mild Demented.
- **Data Visualization:** Displaying sample images from the dataset.
- **Preprocessing:** Reshaping images and performing one-hot encoding of labels for categorical classification.
- **Model Architecture:** Constructing a CNN with layers optimized for image classification tasks.
- **Training:** Training the model on the MRI scans and monitoring performance.
- **Evaluation:** Achieving an accuracy of 95.23% in classifying the MRI scans into the correct categories.

## 3. Chest X-ray Images Pneumonia Detection
**Notebook:** [chest-x-ray-images-pneumonia.ipynb](chest-x-ray-images-pneumonia.ipynb)

This project uses chest X-ray images to detect pneumonia. A deep learning model is trained to classify images into pneumonia or normal categories. Key steps include:

- **Data Preprocessing:** Cleaning and preparing the X-ray images for training.
- **Model Design:** Developing a CNN to extract features and classify the images accurately.
- **Training and Validation:** The model is trained on a labeled dataset and validated to measure performance.
- **Results:** The model effectively distinguishes between pneumonia and normal cases with high accuracy.

## 4. Digit Recognition using CNN
**Notebook:** [digit-recognition-cnn.ipynb](digit-recognition-cnn.ipynb)

The goal of this project is to recognize handwritten digits using a Convolutional Neural Network (CNN). The steps include:

- **Dataset Loading:** Using the MNIST dataset of handwritten digits.
- **Preprocessing:** Normalizing and reshaping the images for input into the CNN.
- **Model Construction:** Building a CNN with layers designed for digit recognition.
- **Training and Evaluation:** Training the model on the dataset and evaluating its accuracy.
- **Performance:** The model achieves high accuracy in predicting digits from 0 to 9.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests. Your contributions are welcome!

## License

This repository is licensed under the MIT License.
