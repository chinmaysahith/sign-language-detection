# 🤟 Sign Language Deduction

A team project aiming to detect and translate **American Sign Language (ASL)** into real-time text captions for communication and accessibility.

---
## 🚀 Overview

Sign Language Deduction is a hybrid AI-based system that:
- Detects **word-level signs** from live video using computer vision.
- Combines fast static recognition with temporal smoothing for continuous signing.
- Converts signs into **text captions in real-time** — useful for meetings, classrooms, and video calls.
---
## 🧠 Features
✅ Real-time ASL word recognition  
✅ Automatic sentence translation (hybrid system)  
✅ MediaPipe-based hand landmark detection  
✅ Lightweight model for fast processing  
✅ Extensible — can later support full sentences or regional sign languages  
---
## 📂 Project Structure
sign-language-deduction/
├─ notebooks/ # Colab notebooks for data exploration and training
├─ scripts/ # Preprocessing, model training, and demo scripts
├─ data/ # (Tracked with DVC) Dataset and preprocessed data
├─ models/ # (Tracked with DVC) Model checkpoints
├─ docs/ # Reports, images, and documentation
└─ README.md
---
## ⚙️ Getting Started
###  Step 1 Clone the Repository
git clone https://github.com/chinmaysahith/sign-language-deduction.git
cd sign-language-deduction

---
### Step 2 install Required Packages
pip install -r requirements.txt

---
### Step 3 Open Notebooks in Google Colab
notebooks/01_data_explore.ipynb → Download and explore Kaggle dataset
notebooks/02_preprocess.ipynb → Preprocess images/keypoints
notebooks/03_train_static.ipynb → Train basic word-recognition model

## 👥 Team Members
- V Chinmay Sahith  
- Y Govardhan  
- Yaswin  
- Teja  

---

## 🧾 License
This project is licensed under the **MIT License** — free to use and modify with attribution.


Cleaned extra text from README





