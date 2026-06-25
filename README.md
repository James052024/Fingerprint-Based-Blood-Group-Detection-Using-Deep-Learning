# 🩸 Fingerprint Based Blood Group Detection Using Deep Learning

A deep learning-based web application that predicts a person's blood group from fingerprint images using Convolutional Neural Networks (CNN) and Transfer Learning models. The system provides a fast, non-invasive, and AI-driven approach for blood group prediction through fingerprint analysis. 

---

## 📖 Overview

Traditional blood group detection requires blood samples and laboratory testing. This project proposes a non-invasive alternative by analyzing fingerprint images using deep learning models such as **ResNet50**, **MobileNet**, and **VGG16**.

The application preprocesses fingerprint images, extracts features using CNN-based transfer learning models, and predicts one of the eight blood groups.

---

## ✨ Features

* 🔐 Non-invasive blood group prediction
* 🖼️ Fingerprint image upload
* 🤖 Deep Learning-based prediction
* 📊 Comparison of multiple transfer learning models
* 🌐 Flask-based web application
* 📈 Model performance evaluation using Accuracy, Precision, Recall, F1-Score & Confusion Matrix

---

## 🛠️ Tech Stack

* Python
* Flask
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Scikit-learn
* HTML
* CSS

---

## 🏗️ System Architecture

> <img width="1281" height="643" alt="image" src="https://github.com/user-attachments/assets/5cab044f-4532-4693-a9a9-492179232db9" />


## 🧠 Deep Learning Models

The project compares three transfer learning models:

* ResNet50
* MobileNet
* VGG16

These models were trained on fingerprint datasets to classify blood groups accurately.

---

## 📂 Project Structure

```text
Fingerprint-BloodGroup-Detection/
│
├── dataset/
├── model/
├── static/
│   ├── css/
│   └── images/
├── templates/
│   ├── index.html
│   └── result.html
├── app.py
├── train.py
├── requirements.txt
└── README.md
```

---

## 📷 Screenshots

### 🏠 Home Page

<img width="668" height="343" alt="image" src="https://github.com/user-attachments/assets/75018fe3-6008-40a2-8d23-84690b87862d" />


### 📤 Upload Fingerprint

<img width="612" height="307" alt="image" src="https://github.com/user-attachments/assets/b5154aaf-6969-47fb-a10f-6800b732e1e9" />


### ✅ Prediction Result

<img width="550" height="197" alt="image" src="https://github.com/user-attachments/assets/883360b0-a450-48b8-83c9-96107705d438" />


## ⚙️ Installation

```bash
git clone https://github.com/yourusername/Fingerprint-BloodGroup-Detection.git

cd Fingerprint-BloodGroup-Detection

pip install -r requirements.txt

python app.py
```

---

## 🚀 How It Works

1. Upload a fingerprint image.
2. Image preprocessing is performed.
3. CNN extracts fingerprint features.
4. Transfer Learning model predicts the blood group.
5. Prediction is displayed on the web interface.

---

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🎯 Future Enhancements

* Improve prediction accuracy with larger datasets.
* Deploy on cloud platforms.
* Mobile application support.
* Real-time fingerprint scanner integration.
* Support for additional biometric features.

---

## 👨‍💻 Authors

**Gagan S**

Bachelor of Engineering – Computer Science & Engineering

ACS College of Engineering

---

## 📄 License

This project is developed for educational and academic purposes.


This README is professional, recruiter-friendly, and suitable for showcasing your final-year project on GitHub.
