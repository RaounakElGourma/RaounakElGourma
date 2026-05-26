<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f62fe,100:6929c4&height=180&section=header&text=Raounak%20El%20Gourma&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%7C%20Computer%20Vision%20Specialist&descAlignY=58&descColor=c6e0ff" />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/raounak-el-gourma)
[![Email](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elgraounak@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://your-portfolio-link)

</div>

---

## 👁️ About Me

I'm a **Computer Vision & AI Engineer** currently completing my **Master of Excellence in AI & IoT** at the Center of Excellence in Automotive & Aeronautics, Morocco.

My work lives at the intersection of **deep learning, computer vision, and real-world deployment** — from medical imaging to logistics, fashion tech to smart surveillance. I care about building systems that don't just work in notebooks, but run reliably in production.

- 🔭 Currently working on **clothing attribute recognition** using YOLO-based pipelines (Nextronic / ABA Technology)
- 🧠 Interests: Object Detection · OCR · Medical Imaging · NLP · Edge AI
- 🌍 Based in **Morocco**

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### AI & Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

### Computer Vision & Image Processing
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![Tesseract](https://img.shields.io/badge/Tesseract_OCR-1B72BE?style=for-the-badge&logo=google&logoColor=white)

### Data & Visualization
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)

### Deployment & Tools
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Embedded Systems
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

---

## 🚀 Featured Projects

### 👗 Clothing Understanding Pipeline for Surveillance Environments
> *Computer Vision Engineer Intern — Nextronic / ABA Technology (2026–Present)*

A **modular, production-grade CV pipeline** for clothing understanding in CCTV/surveillance contexts. The system detects people in video streams, tracks them across frames, and routes each person through specialized classification models. robust to real-world conditions like motion blur, occlusions, crowded scenes, and varied camera angles.

**Key Features:**
- **ByteTrack** multi-object tracking — maintains identity across frames, prevents re-processing, enables temporal analysis
- **Temporal voting mechanism** — classifies the same person across multiple non-consecutive frames, then applies majority/weighted voting for stability
- **Dual routing** — EfficientNet-B3 classifier separates standard (top + bottom) vs. full-body garments before downstream classification
- Supports recorded video, CCTV footage, RTSP streams, and live webcam input
- Outputs annotated video with bounding boxes, tracking IDs, and predicted labels

**Stack:** `Python` `PyTorch` `YOLOv8` `ByteTrack` `EfficientNet-B3` `OpenCV`

---

### 🚗 Moroccan License Plate & SIM Card Phone Number Detection
> *ML & CV Intern — EMS Maroc (Jul–Sep 2025)*

Real-time detection and **automatic text extraction** from Moroccan license plates and SIM card phone numbers using a YOLO + OCR pipeline.

- End-to-end data pipeline: collection → cleaning → annotation → augmentation → training
- Live stream and image upload inference via a Flask web demo
- Robust to real-world lighting and perspective variation

**Stack:** `Python` `YOLOv8` `EasyOCR` `OpenCV` `Flask` `Albumentations`

---

### 📄 Intelligent CV Matching & Scoring
> *Data Science Intern — Omni Consulting (Jul–Aug 2025)*

AI-powered system that **automatically compares CVs against job/internship descriptions** and ranks candidates by relevance — supporting HR pre-screening at scale.

- NLP-based feature extraction from unstructured CV text
- Similarity scoring and ranked candidate output
- Designed to reduce manual screening time significantly

**Stack:** `Python` `NLP` `Transformers` `Scikit-learn` `Pandas`

---

### 🩺 Diabetic Retinopathy Detection
> *Computer Vision Intern — CHU Oujda (Jul 2024)*

CNN-based classification model for early detection of **diabetic retinopathy** from retinal fundus images.

- Medical image preprocessing and dataset balancing
- Performance evaluation on clinical imaging datasets
- Contributes to accessible AI-assisted ophthalmology

**Stack:** `Python` `TensorFlow/Keras` `OpenCV` `NumPy` `Matplotlib`

---

### 📦 Parcel Volume Estimation
Automatic **3D volume estimation** of parcels from 2D images — a computer vision solution for logistics automation.

**Stack:** `Python` `OpenCV` `Deep Learning`

---

### 🌱 Agrobot – Crop Recommendation System
Machine Learning system providing **crop recommendations** based on soil and climate data, using Random Forest classification.

**Stack:** `Python` `Scikit-learn` `Random Forest` `Pandas`

---

## 📊 GitHub Stats

<div align="center">

![Raounak's GitHub Stats](https://github-readme-stats.vercel.app/api?username=RaounakElGourma&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=RaounakElGourma&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🎓 Education

| Degree | Institution | Year |
|--------|-------------|------|
| 🎓 Master of Excellence — AI & IoT | Center of Excellence in Automotive & Aeronautics | 2024–2026 |
| 🎓 Bachelor of Excellence — AI & Data Engineering | Center of Excellence in Automotive & Aeronautics | 2023–2024 |
| 🎓 DUT — Embedded Computer Engineering | Higher School of Technology (EST), Oujda | 2021–2023 |
| 🏫 Baccalauréat — Physical Sciences & Chemistry | Lycée Omar Ibn Abdel-Aziz, Oujda | 2021 |

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6929c4,100:0f62fe&height=100&section=footer" />

</div>
