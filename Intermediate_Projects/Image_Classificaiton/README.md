🖼️ CIFAR-10 Image Classification — ANN vs CNN

📖 Project Overview
This project compares Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) for image classification on the popular CIFAR-10 dataset. It aims to demonstrate how CNNs outperform standard ANNs on structured image data.

🎯 Objective
To develop, train, and compare two deep learning models—ANN and CNN—for the task of classifying 32x32 color images across 10 categories, showcasing deep learning best practices.

🗃️ Dataset Details
Dataset: CIFAR-10 via TensorFlow/Keras datasets

Samples: 60,000 total - 50,000 train, 10,000 test

Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

Format: RGB images, 32x32 pixels each

🛠️ Key Steps
Data Preparation: Normalized pixel values to. One-dimensional label conversion.​

Model 1: ANN: Flatten input to a dense network. Used ReLU activations and output softmax layer.

Model 2: CNN: Built a deep convolutional network with maxpooling, making the model spatially sensitive.

Evaluation: Compared performance using test accuracy and per-class metrics.

⚙️ Technologies Used
Python 
TensorFlow / Keras
NumPy
Matplotlib
scikit-learn

📊 Results

Model	Test Accuracy	Key Takeaways
ANN	    ~48-55%	        Basic performance, weak on spatial info
CNN	    ~80%	        Much better, handles images effectively

🧠 CNN substantially outperforms ANN, confirming the effectiveness of convolutions for capturing patterns in image data.
⏱️ CNN also offers more efficient computation (thanks to max pooling and reduced parameter count).

📝 Sample Outputs
Classification reports and confusion matrices detail strengths/weaknesses by class.
Sample visualizations help in understanding learning efficacy.

🚀 How to Run
Clone this repo, open the notebook in Jupyter, and run all cells. Make sure you have TensorFlow, NumPy, Matplotlib, and scikit-learn installed.

💡 Learnings
ANN (MLP) architectures are limited for raw image data.
CNNs learn spatial structure, filters, and are the backbone of modern computer vision.
Data normalization and preprocessing are crucial for model performance.

📂 Reference
Dataset source: CIFAR-10 Dataset