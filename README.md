# 🌿Plant Disease Detection using CNN
This project uses Convolutional Neural Networks (CNNs) to automatically detect and classify plant diseases from leaf images. By leveraging deep learning and image processing, the model can assist farmers, researchers, and agricultural professionals in identifying diseases early and taking appropriate action.

## 🔍 Features
: Trained CNN model to classify multiple types of plant diseases

: Preprocessing pipeline for image cleaning and augmentation

: Evaluation metrics (accuracy, confusion matrix, etc.)

: Easy-to-use inference script for real-time predictions

: Support for custom datasets and retraining

## 📁 Dataset
Uses the PlantVillage dataset containing labeled leaf images of healthy and diseased plants.

##🛠️ Tech Stack
: Python
: TensorFlow
: OpenCV
: NumPy and Pandas
: Matplotlib (for visualization)

## 🚀 How to Use

## :- Clone the repo
git clone https://github.com/yourusername/plant-disease-cnn.git

## :- Install dependencies
pip install -r requirements.txt

## :- Train the model
python train.py

## :- Predict disease from a new image
python predict.py --image path_to_image.jpg

## 📊 Results
Achieved over 99.48% accuracy on the validation set, with good generalization to unseen leaf samples.

## 📌 Future Work
: Deploy model as a web/mobile app

: Improve accuracy using transfer learning (e.g., ResNet, EfficientNet)

: Real-time detection using a smartphone camera
