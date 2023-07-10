### Face Mask Detection with OpenCV and Deep Learning
This project aims to detect whether individuals in real-time video streams are wearing face masks or not. It combines computer vision techniques, utilizing OpenCV, with deep learning methodologies, using a Convolutional Neural Network (CNN) model.

## Features

1) Real-time face mask detection in video streams.
2) Preprocessing and augmentation techniques to enhance model performance.
3) CNN model architecture implemented using TensorFlow and Keras.
4) Training and evaluation on a labeled dataset.
5) Real-time visualization with bounding boxes and class labels.

## Dependencies

1) Python 3.x
2) OpenCV
3) TensorFlow
4) Keras

## installation

Clone the project repository:

git clone https://github.com/Adarsh10337/face-mask-detection.git
Install the required dependencies:

pip install -r requirements.txt

## Dataset Preparation

1) Organize your face images into two folders: one for images with masks and another for images without masks.

2) Preprocess and augment the dataset as needed, including resizing, normalization, and data augmentation techniques.

3) Split the dataset into training and testing sets. You can use the train_test_split() function from scikit-learn to achieve this.

## for datasets visit the following link

https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

## Training the Model
Update the file paths and parameters in the code to match your dataset and requirements.

Run the training script to train the CNN model:

python train.py
Evaluate the trained model using the testing set and analyze the performance metrics.

## Real-time Face Mask Detection

1) Update the model path in the code file for real-time inference.

2) Run the detection script to start face mask detection on the live video feed:

python detect.py

3) The live video feed will be displayed, showing bounding boxes and class labels indicating whether individuals are wearing masks or not.

## Contributing
Contributions and improvements to the project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.
