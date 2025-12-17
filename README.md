# Face Emotion Recognition

Real-time facial emotion detection system using Deep Learning. Analyzes live webcam feed to classify 7 emotions with high accuracy.

## 🎯 Features
- **Live Webcam Detection**: Processes video frames in real-time
- **7 Emotion Classes**: angry, disgust, fear, happy, neutral, sad, surprise
- **Face Detection**: Haar Cascade for robust face localization
- **CNN Model**: Pre-trained on FER-2013 dataset (48x48 grayscale)
- **Real-time Overlay**: Emotion labels displayed on detected faces

## 🛠 Tech Stack

## 🚀 How It Works
1. **Face Detection**: Haar Cascade identifies faces in webcam feed
2. **Preprocessing**: Converts to 48x48 grayscale, normalizes pixel values
3. **Prediction**: CNN model outputs emotion probabilities
4. **Visualization**: Draws bounding boxes + emotion labels

## 📁 Key Files
- `facialemotionmodel.json` & `.h5` - Pre-trained CNN weights
- `haarcascade_frontalface_default.xml` - Face detection cascade

## 🔗 Live Demo
[![Live Demo](https://chand6756.github.io/Face-Emotion-Recognition/)](https://chand6756.github.io/Face-Emotion-Recognition/)

## 📊 Sample Output

## Installation

## Usage
Press ESC to exit.

---
**Built with ❤️ for computer vision enthusiasts!**
