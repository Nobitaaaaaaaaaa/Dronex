# Dronex

# 🚁 Flying Object & Drone Classifier API

An end-to-end Deep Learning project that classifies images of flying objects into 6 distinct categories. The project includes a model trained using transfer learning (VGG16) and a Flask REST API to serve the predictions.

## 🌟 Overview

This project is designed to distinguish between various types of drones, birds, and RC planes. It takes an image as input and returns the predicted class along with its probability. 

### 🎯 Classification Categories
The model is trained to recognize the following 6 classes:
1. `3 long blade rotor`
2. `3 short blade rotor`
3. `bird`
4. `bird with mini helicopter`
5. `drone`
6. `rc plane`

---

## 🛠️ Technology Stack

* **Machine Learning:** TensorFlow, Keras (VGG16 Architecture)
* **Computer Vision:** OpenCV (`cv2`), NumPy
* **Backend API:** Python, Flask, Flask-CORS
* **Environment:** Jupyter Notebook (for model training)

---

## 📁 Project Structure

```text
├── app.py                 # Flask application serving the REST API
├── model.ipynb            # Jupyter notebook used for data prep & model training
├── final model.h5         # Pre-trained Keras model weights (Needs to be in the root directory)
└── README.md              # Project documentation
