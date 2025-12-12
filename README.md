---
title: ECG-Analysis (Flask)
emoji: 🐱🐇
colorFrom: blue
colorTo: purple
sdk: docker
pinned: false
---

# 🐱🐇 ECG-Analysis (Flask App)

This Space hosts a **Flask-based image classifier** that predicts whether an uploaded image contains a **cat** or a **rabbit**.

The model is a custom PyTorch CNN and uses a simple HTML frontend (`templates/index.html`).

## 🚀 How it Works
- You upload an image.
- The image is preprocessed and passed through the CNN.
- The model outputs:
  - predicted class 
  - probability score
  

## 📁 Project Structure

main.py
requirements.txt
Dockerfile
ECG-patient.pth
templates/
└── index.html


## 🔧 Tech Stack
- Python + Flask
- PyTorch
- Docker
- Hugging Face Spaces

## ▶️ Running Locally
pip install -r requirements.txt
python main.py


## 🐳 Docker Build (Hugging Face)
The Space uses a custom Dockerfile to run Flask on port **7860**.

---



