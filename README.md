The DataSet for this project : https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

This project focuses on building a Convolutional Neural Network (CNN) using TensorFlow to classify chest X-ray images into two categories: Normal and Pneumonia. The model utilizes the Kaggle Chest X-Ray Images Dataset, which contains labeled X-ray images of healthy lungs and lungs affected by pneumonia, to train and evaluate the model.
Key Features:
Problem Type: Multi-Class Classification (Normal vs. Pneumonia).
Model Architecture: A deep CNN with multiple convolutional and pooling layers, followed by fully connected Dense layers to extract and classify features.
Output Layer:
Softmax Activation with one-hot encoded labels for scalability to multi-class problems. It is kept softmax so that it can be extended to more classes
Loss Function:
categorical_crossentropy for one-hot encoded multi-class classification.
Evaluation Metrics: Model accuracy on validation data to assess its performance.
