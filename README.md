# AI Image Classification using CNN (CIFAR-10) :
This project demonstrates a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras to classify images into **10 object categories** from the CIFAR-10 dataset.  
It also includes a simple script to **load a trained model** and **predict new images**.


## Features :
- Train a CNN from scratch on CIFAR-10 dataset  
- Achieve high accuracy on 10 classes (airplane, car, bird, cat, deer, dog, frog, horse, ship, truck)  
- Save and load trained models in `.h5` format  
- Test real-world images through prediction script  
- Visualize training and validation performance (accuracy and loss)


## Technologies Used :
- Python 3.9  
- TensorFlow / Keras  
- NumPy, Pillow  
- Matplotlib  


## 📂 Project Structure

ai_image_classification/
│
├── main.py # Script to load and predict new images
├── train_model.py # CNN training and evaluation on CIFAR-10
├── requirements.txt # All project dependencies
├── notebooks/
│ └── cnn_cifar10_model.h5 # Saved trained model
├── data/
│ └── truck.jpg # Example image for testing
└── README.md # Project documentation
