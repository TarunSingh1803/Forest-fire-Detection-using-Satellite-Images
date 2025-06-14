# 🌲 Forest Fire Detection Using Satellite Images 🔥

This project aims to detect the presence of wildfires in satellite images using a deep learning model. Built with TensorFlow and deployed using Streamlit, it provides a user-friendly interface to upload satellite images and determine the likelihood of fire in them.

---

## 🚀 Demo

Upload a satellite image and the model will classify it as either:

- **Fire 🔥**
- **No Fire**

---

## 📂 Dataset

We used the **[Wildfire Prediction Dataset](https://www.kaggle.com/datasets/abdelghaniaaba/wildfire-prediction-dataset)** from Kaggle. It contains satellite imagery data labeled for fire and no-fire classes, which is ideal for training binary image classification models.

---

## 🧠 Model

The model is a Keras-based Convolutional Neural Network (CNN) trained on resized satellite images (64x64). It was saved as `wildfire_detection_model.h5` and is used in the app for real-time prediction.

---

## 📱 App Interface (Streamlit)

The app allows users to:
1. Upload `.jpg` satellite images.
2. View the uploaded image.
3. Click a button to run the fire detection model.
4. See the prediction result and model confidence.

---

## 🔧 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/TarunSingh1803/Forest-fire-Detection-using-Satellite-Images.git
cd Forest-fire-Detection-using-Satellite-Images
