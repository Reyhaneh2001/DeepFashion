# 👗 DeepFashion: Visualizing and Classifying Fashion MNIST with Keras Functional API

This project demonstrates a complete end-to-end pipeline for image classification using the **Fashion MNIST** dataset. It includes **exploratory data analysis (EDA)**, **data preprocessing**, **visualizations**, and a **Convolutional Neural Network (CNN)** built using the **Keras Functional API**.




## 📌 Project Highlights  
- **Data preprocessing**: scaling, one-hot encoding, reshaping  
- CNN with **Batch Normalization**, **Dropout**, and **Early Stopping**  
- Built with **Keras Functional API** 
- Model evaluation with **accuracy, confusion matrix, and classification report**  




## Dataset

- **Fashion MNIST**: A dataset of 70,000 grayscale images (28x28) of 10 fashion categories  
- Comes preloaded with Keras: `tf.keras.datasets.fashion_mnist`

| Class Label | Description      |
|-------------|------------------|
| 0           | T-shirt/top      |
| 1           | Trouser          |
| 2           | Pullover         |
| 3           | Dress            |
| 4           | Coat             |
| 5           | Sandal           |
| 6           | Shirt            |
| 7           | Sneaker          |
| 8           | Bag              |
| 9           | Ankle boot       |




## Model Architecture

Built with **Keras Functional API** for more control and flexibility.

- Input Layer (28x28x1)
- Conv2D → BatchNorm → ReLU → Dropout  
- Conv2D → BatchNorm → ReLU → Dropout  
- Flatten  
- Dense → BatchNorm → ReLU → Dropout  
- Output: Dense(10, softmax)


## Visualizations

- Class distribution bar chart   
- Training/Validation accuracy and loss curves  
- Confusion Matrix  
- Classification Report



