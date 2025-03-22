# 🧠 Image-Based Recognition with CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to perform image-based recognition on the MNIST dataset, which consists of handwritten digits (0-9). ✍️

## 🌟 Project Overview
- **Dataset:** 📊 MNIST (70,000 grayscale images of size 28x28 pixels, 10 classes)
- **Model:** 🏗️ Convolutional Neural Network (CNN)
- **Objective:** 🎯 Classify handwritten digits with high accuracy

## ⚙️ Prerequisites
Ensure you have the following installed:
- 🐍 Python (>= 3.7)
- 🔧 TensorFlow (>= 2.x)
- 📦 NumPy
- 📊 Matplotlib

Install dependencies with:
```bash
pip install tensorflow numpy matplotlib
```

## 📁 Project Structure
```
📦 image-based-recognition
├── 📝 image_recognition.py  # Main script for training and evaluation
└── 📘 README.md             # Project documentation
```

## 🚦 Steps in the Project
1. **📥 Load Dataset:** Import MNIST directly from Keras.
2. **🛠️ Preprocessing:** Reshape the data and normalize pixel values to the range [0, 1].
3. **🏗️ Build CNN Model:**
   - 🌀 2 Conv2D layers with ReLU activation and MaxPooling
   - 🧱 Flatten layer to convert 2D features into 1D
   - ⚙️ Dense layer with 64 neurons and ReLU activation
   - 🎉 Output layer with 10 neurons and softmax activation (one for each digit)
4. **📌 Compile the Model:** Use Adam optimizer and sparse categorical cross-entropy loss.
5. **🚀 Train the Model:** Train the CNN for 5 epochs with 20% validation split.
6. **📊 Evaluate the Model:** Test accuracy is printed after evaluation.
7. **🔍 Make Predictions:** Display predictions for 5 sample images.

## 🚀 How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/RELLABHAVANISOWMYA/image-based-recognition.git
```
2. Navigate to the project directory:
```bash
cd image-based-recognition
```
3. Run the script:
```bash
python image_recognition.py
```

## 📌 Expected Output
- 📈 Training and validation accuracy per epoch
- 🎯 Final test accuracy
- 🖼️ Visualizations of sample predictions

## 📊 Results
- The model achieves around 98% accuracy on the MNIST test set. ✅

## 🙌 Acknowledgements
- 🤖 TensorFlow/Keras for the deep learning framework
- 📚 MNIST dataset by Yann LeCun

## 📜 License
This project is licensed under the MIT License. 📄

