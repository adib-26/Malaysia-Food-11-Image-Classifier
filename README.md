# 🍴 Malaysia Food-11 Image Classifier

A deep learning project that classifies **11 types of Malaysian food** using both a **Custom CNN** and **ResNet-50 (Transfer Learning)**. Includes training pipeline, evaluation, and a **Streamlit web app** for real-time predictions.

---



##  Dataset

https://www.kaggle.com/datasets/karkengchan/malaysia-food-11

- 11 Malaysian food categories:
  - Nasi Lemak
  - Satay
  - Roti Canai
  - Laksa
  - Fried Rice
  - Fried Noodles
  - Kaya Toast
  - Popiah
  - Hamburger
  - Fish and Chips
  - Mixed Rice

---


##  Features

- Custom Convolutional Neural Network (CNN)
- Transfer Learning with ResNet-50
- Data cleaning & validation pipeline
- Data augmentation for robustness
- Model comparison (accuracy & loss)
- Confusion matrix & misclassification analysis
- Interactive Streamlit web app

---

## 📂 Project Structure

```

malaysia-food-classification/
│
├── notebooks/
│   └── Malaysia-11.ipynb
│
├── app/
│   └── app.py
│
├── models/
│   ├── resnet_food_model.keras
│   ├── custom_cnn_best.keras
│   └── resnet_best_weights.keras
│
├── requirements.txt
├── README.md

````

---

##  Models

### 1. Custom CNN
- 4 Convolutional blocks
- MaxPooling layers
- Dropout for regularization
- Fully connected classifier

### 2. ResNet-50 (Transfer Learning)
- Pretrained on ImageNet
- Frozen base layers
- Custom classification head
- Fine-tuning ready

---



## ⚙️ Installation

```bash
git clone https://github.com/YOUR_USERNAME/malaysia-food-classifier.git
cd malaysia-food-classifier

pip install -r requirements.txt
````

---

##  Training

Run the notebook:

```bash
jupyter notebook Malaysia-11.ipynb
```

Key steps:

* Data cleaning & validation
* Dataset splitting (80/20)
* Model training
* Performance comparison

---

##  Evaluation

Includes:

* Accuracy & loss curves
* Confusion matrix
* Misclassification visualization

---

## 🌐 Streamlit Web App

Run locally:

```bash
streamlit run app.py
```

### Features:

* Upload food image
* Real-time prediction
* Confidence score display

---
## Application Preview with real world image
<img width="1273" height="776" alt="Screenshot 2026-04-23 at 10 17 09 PM" src="https://github.com/user-attachments/assets/a7493f6d-b816-42fa-973c-736744ceff12" />

---
## 🏪 Real-World Applications

* Self-service kiosks (automated billing)
* Food trend analytics
* Calorie tracking apps
* SME digital transformation in F&B


---

## ⭐ Contributing

Pull requests are welcome. For major changes, open an issue first.

---
