# 🧠 Cataract Detection Using Deep Learning

This project focuses on detecting cataract disease from eye images using Deep Learning and Transfer Learning (MobileNetV2).  
It classifies eye images into Cataract and Normal categories.

---

## 📌 Project Overview

Cataract is one of the leading causes of blindness worldwide. Early detection helps in timely treatment and prevention of vision loss.  
This project uses a deep learning model trained on eye images to automatically detect cataract disease.

---

## 🚀 Features

- Binary classification (Cataract / Normal)
- Transfer Learning using MobileNetV2
- Image augmentation to reduce overfitting
- Lightweight and deployable model
- Medical image analysis project

---

## 🧠 Model Information

- Architecture: MobileNetV2
- Pre-trained on: ImageNet
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy
- Input Image Size: 224 × 224 × 3

---

## 📂 Dataset Structure

processed_images/
├── train/
│   ├── cataract/
│   └── normal/
└── test/
    ├── cataract/
    └── normal/

Each folder contains eye images belonging to that class.

---

## ⚙️ Installation

1. Clone the repository:
git clone https://github.com/your-username/Cataract-Detection-Deep-Learning.git

2. Move into project directory:
cd Cataract-Detection-Deep-Learning

3. Install dependencies:
pip install -r requirements.txt

---

## ▶️ How to Run

1. Open the notebook:
notebooks/cataract_detection.ipynb

2. Run all cells to:
- Load dataset
- Train the model
- Evaluate performance
- Save trained model

---

## 🔍 Prediction

The trained model predicts whether an eye image is:
- Cataract Detected
- Normal Eye

Prediction is done using the saved .h5 model file.

---

## 📈 Results

The model achieves good accuracy on test data using:
- Transfer learning
- Data augmentation
- Frozen pre-trained layers

Training and validation accuracy/loss graphs are included in the notebook.

---

## 🏥 Applications

- Medical diagnosis support systems
- Ophthalmology clinics
- AI-assisted health screening
- Academic and research projects

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Matplotlib
- OpenCV
- Google Colab

---

## 👤 Author

Pawan  Rajput  
Computer Science Student  
Aspiring Machine Learning / AI Engineer  

LinkedIn: https://www.linkedin.com/in/pawan-rajput-1913b12b1

---

## 📜 Disclaimer

This project is for educational and research purposes only and should not be used as a replacement for professional medical diagnosis.

---

⭐ If you find this project useful, consider giving it a star!
