# Plant Disease Classifier

Plant Disease Classifier is a deep learning project designed to identify and classify diseases in apple leaves using image-based inputs. It leverages convolutional neural networks (CNNs) to differentiate between various plant conditions and support early disease diagnosis through computer vision.

# Project Overview

The model is trained on a structured dataset of apple leaf images labeled into four categories: three disease types and one healthy class. This project demonstrates practical applications of image classification in agriculture and showcases the full workflow — from preprocessing and training to inference — in a Jupyter Notebook environment.

# Features

Image-based classification of apple leaf conditions
Four-label prediction: Apple Scab, Black Rot, Cedar Apple Rust, and Healthy
Train/test dataset organization using real-world images
End-to-end implementation in Jupyter Notebook
Easily adaptable to other crops with minimal changes

# Technologies Used

Category	Tools and Libraries
Language	Python
Deep Learning	TensorFlow / Keras or PyTorch
Visualization	Matplotlib, Seaborn
Data Handling	NumPy, Pandas
Notebook	Jupyter Notebook (.ipynb)
Image Loading	OpenCV or TensorFlow/Keras utils

# Project Structure

Plant_disease/
├── Plant-disease.ipynb         # Main notebook with training, evaluation, and predictions
├── Train/                      # Training dataset
│   ├── Apple___Apple_scab/
│   ├── Apple___Black_rot/
│   ├── Apple___Cedar_apple_rust/
│   └── Apple___Healthy/
├── Test/                       # Testing dataset
│   ├── Apple___Apple_scab/
│   ├── Apple___Black_rot/
│   ├── Apple___Cedar_apple_rust/
│   └── Apple___Healthy/
└── README.md

# How to Run

Clone the repository:
git clone https://github.com/RashmithaBolloju01/Plant_disease.git
cd Plant_disease
Open the notebook in Jupyter:
jupyter notebook Plant-disease.ipynb
Execute the notebook cells to train, validate, and test the model.
Ensure all dependencies such as TensorFlow, matplotlib, and OpenCV are installed in your Python environment.

#Sample Use Case

A farmer or researcher uploads an image of an apple leaf suspected to be infected. The model processes the image and predicts whether it is healthy or shows symptoms of Apple Scab, Black Rot, or Cedar Apple Rust — enabling timely treatment decisions.

# Future Enhancements

Expand to multiple plant species (e.g., tomato, potato)
Improve model generalization with data augmentation
Integrate a real-time prediction interface using Streamlit or Flask
Deploy the model via a web or mobile application

# License

This project is licensed under the MIT License.
