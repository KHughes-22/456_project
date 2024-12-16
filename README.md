Project overview:
- This project implements a convolutional Neural Network to classify X-ray images into two categories: Normal and Pneumonia:
- The model processes images of size 128X128 and achieves binary classification using TensorFlow / Keras libary.
- The dataset is structred into train, val, and test directories

Dataset:
- https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?select=chest_xray
- Make sure to update the path to where you saved the dataset: data_dir = "path_to_your_dataset"  # Replace with your dataset's path

Dependencies:
- pip install tensorflow numpy matplotlib

Expected Results:
- Training Accuracy: Approximatley 95% after 5 epochs
- Test Accuracy: Approximatley 72%
