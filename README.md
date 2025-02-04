# Traffic Sign Recognition using CNN

## Introduction
This project implements a Traffic Sign Recognition system using Convolutional Neural Networks (CNN). It processes and classifies traffic signs from the German Traffic Sign Recognition Benchmark (GTSRB) dataset into 43 different categories, achieving an accuracy of 96% in just 5 epochs.

## Dataset
The dataset used is the **German Traffic Sign Recognition Benchmark (GTSRB)**, which contains **40,000 images** of traffic signs categorized into **43 different labels**. It is widely used for training and evaluating traffic sign classification models.

## Model & Approach
- Implemented a **CNN-based deep learning model** for image classification.
- Preprocessed the images for better model performance.
- Trained the model for **5 epochs**, achieving **96% accuracy**.
- Used **softmax activation** for multi-class classification.
- Optimized using **Adam optimizer** and **categorical cross-entropy loss function**.

## Features
- **High Accuracy**: Achieves **96% accuracy** on test data.
- **Efficient Training**: Requires only **5 epochs** for high performance.
- **Multi-class Classification**: Identifies **43 different traffic signs**.
- **Robust Preprocessing**: Ensures clean and effective training data.
- **Fast and Scalable**: Can be extended to real-world applications.

## Installation
To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaMVerma/Traffic-Sign-Recognition.git
   cd Traffic-Sign-Recognition
   ```

2. Install required dependencies using Anaconda:
   ```bash
   conda create -n myenv python=3.12
   conda activate myenv
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   Open `Traffic_Sign_Recognition_Using_CNN.ipynb` and execute the cells.

## Usage
- Load the dataset and preprocess images.
- Train the CNN model using the provided notebook.
- Evaluate the model on test data.
- Use the trained model to classify new traffic sign images.

## Results
- **Achieved Accuracy**: **96%**
- **Training Time**: Only **5 epochs** needed for high performance.
- **Confusion Matrix & Evaluation Metrics**: Show strong classification performance across all 43 labels.


