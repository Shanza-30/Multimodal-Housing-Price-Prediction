# 🏠 Multimodal Housing Price Prediction (Images + Tabular Data)

## 📌 Project Overview

This project task 4 Developershub Corporation implements a **Multimodal Machine Learning model** to predict housing prices by combining **structured tabular data** and **house images**.

Traditional models rely only on numerical features, but this project integrates visual information using Convolutional Neural Networks (CNNs) to improve prediction accuracy.

---

## 🎯 Objective

Predict housing prices using:

* 📊 Tabular housing data (structured features)
* 🖼️ House images (visual features)

---

## 📂 Dataset

* Housing Sales Dataset (tabular data)
* Custom/Public House Image Dataset

Each image corresponds to a specific property in the dataset.

---

## 🧠 Methodology

### 1️⃣ Image Feature Extraction

* Used pretrained CNN models (ResNet50/VGG16)
* Extracted deep visual features from house images

### 2️⃣ Tabular Data Processing

* Missing value handling
* Feature encoding
* Data normalization

### 3️⃣ Feature Fusion

* Combined CNN image features with tabular features
* Used concatenation layer for multimodal learning

### 4️⃣ Model Training

* Built regression model using TensorFlow/Keras
* Trained on both modalities simultaneously

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

---

## 📊 Evaluation Metrics

Model performance evaluated using:

* **MAE (Mean Absolute Error)**
* **RMSE (Root Mean Squared Error)**

These metrics measure prediction accuracy and error magnitude.

---

## 🚀 Skills Gained

* Multimodal Machine Learning
* Convolutional Neural Networks (CNNs)
* Feature Fusion (Image + Tabular Data)
* Regression Modeling
* Model Evaluation Techniques

---

## 📈 Project Workflow

Image Input → CNN Feature Extraction
Tabular Input → Dense Layers
Feature Fusion → Regression Model → Price Prediction


## 📌 Future Improvements

* Add more image augmentation
* Hyperparameter tuning
* Deploy model using Flask/Streamlit
* Real-time house price prediction system

