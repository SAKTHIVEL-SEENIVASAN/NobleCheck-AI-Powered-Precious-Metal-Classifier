# 🌟 NobleCheck: AI-Powered Precious Metal Classifier

**NobleCheck** is an AI-based image classification tool designed to detect whether a jewelry item is made of:
- 🟡 Pure Gold
- 🟠 Gold-Plated / Covering Gold
- ⚪ Silver  

This solution helps buyers, sellers, and online platforms verify jewelry types visually, reducing fraud and building trust.

---

## 📌 Project Overview
NobleCheck uses image classification powered by deep learning to identify precious metals from photos. The goal is to assist jewelers, pawn brokers, and customers with a quick, non-invasive, AI-driven method to distinguish between pure gold, gold-plated, and silver items.

---

## 🚀 Features
✅ Classifies jewelry into pure gold, gold-plated, or silver  
✅ Uses transfer learning for lightweight, accurate performance  
✅ Works in real-time through a web app  
✅ Displays confidence score for each prediction  
✅ Designed to work with varied lighting conditions  

---

## 🛠️ Tech Stack
- Python 3.x  
- TensorFlow / PyTorch (model training)  
- OpenCV (optional for image preprocessing)  
- Flask / FastAPI / Streamlit (web app backend)  
- HTML / CSS / Bootstrap (frontend)  
- GitHub Pages (for hosting static parts)

---

## 📂 Project Structure
NobleCheck/
├── dataset/ # Store sample dataset images / links / augmentations
├── model/ # Model training notebooks/scripts
├── app/ # Web app code (Flask/FastAPI/Streamlit)
├── static/ # CSS, JS, images for frontend
├── templates/ # HTML templates (for Flask/Streamlit)
├── requirements.txt # Dependencies list
├── README.md # Project description (this file)
└── LICENSE # MIT 
## 📊 Dataset
Our dataset includes images of:
- Pure gold jewelry (22K, 24K)
- Gold-plated jewelry
- Silver jewelry  

We plan to collect data via:
- Original photography from jewelry shops (with permission)  
- Publicly available datasets (where possible)  
- Data augmentation: rotations, brightness adjustments, zoom, background variations  

---

## 🧠 Model Design
We apply transfer learning on pre-trained models:
- MobileNetV2 (lightweight, mobile-ready)
- ResNet50 (high accuracy)

Training split:
- 80% training  
- 10% validation  
- 10% testing  

The model will output the predicted class and confidence score.

---

## 🌐 Application Flow
1️⃣ User uploads or captures jewelry image  
2️⃣ Model predicts type (pure gold / gold-plated / silver)  
3️⃣ App displays result with confidence score  

Future scope:
- Price estimation tool (based on weight input)
- Mobile app version (TensorFlow Lite + Flutter)

---


