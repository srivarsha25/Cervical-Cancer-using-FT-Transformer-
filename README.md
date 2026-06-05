# 🩺 AI-Based Cervical Cancer Risk Prediction & Analytics System

## 📌 Overview

The **AI-Based Cervical Cancer Risk Prediction & Analytics System** is a comprehensive healthcare analytics platform designed to assist in the early detection and risk assessment of cervical cancer using both clinical patient data and cervical cell images.

The system combines multiple machine learning and deep learning approaches, including **CNN**, **FT-Transformer**, and **XGBoost**, to provide risk predictions, visual analytics, downloadable medical reports, AI-assisted guidance, and appointment scheduling capabilities.

---

## 🎯 Problem Statement

Cervical cancer remains one of the leading causes of cancer-related deaths among women worldwide. Early diagnosis significantly improves treatment outcomes; however, traditional screening methods can be time-consuming and require expert analysis.

This project aims to provide an intelligent decision-support system that:

* Predicts cervical cancer risk using clinical attributes
* Classifies cervical cell images automatically
* Visualizes patient risk trends
* Generates structured medical reports
* Assists patients through an AI-powered health assistant
* Facilitates doctor appointment scheduling

---

## 🚀 Key Features

### 🧠 Clinical Risk Prediction

* Predicts cervical cancer risk using patient clinical data
* Utilizes:

  * FT-Transformer
  * XGBoost
* Analyzes multiple clinical risk factors

### 🔬 Image-Based Cervical Cell Classification

* Uses Convolutional Neural Networks (CNNs)
* Classifies cervical cell images into multiple cell categories
* Provides confidence scores for predictions

### 📊 Risk Analytics Dashboard

* Interactive graphical representation of risk levels
* Visualizes prediction outcomes
* Displays patient-specific risk insights

### 📄 PDF Report Generation

Automatically generates downloadable patient reports containing:

* Prediction results
* Confidence scores
* Risk analytics
* Patient summary

### 🤖 AI Health Assistant

* AI-powered chatbot for cervical cancer awareness
* Provides educational information and guidance
* Helps users understand risk factors and screening methods

### 📅 Appointment Booking System

* Allows users to schedule doctor consultations
* Stores and manages appointment history
* Provides a streamlined healthcare workflow

---

## 🏗️ System Architecture

```text
User Input
     │
     ▼
Clinical Data ─────────────► FT-Transformer
     │                       │
     │                       ▼
     │                   Risk Score
     │
     ▼
XGBoost Model ───────────► Clinical Prediction

Image Upload
     │
     ▼
CNN Image Classifier ───► Cell Classification

     ▼
Combined Analytics Engine
     │
     ▼
Dashboard + Graphs + Reports
     │
     ├── AI Chat Assistant
     └── Appointment Booking
```

---

## 📂 Datasets Used

### 1. SIPaKMeD Dataset

Used for image-based cervical cell classification.

**Dataset Details**

* Total Images: 4049
* Image Type: Pap Smear Images

**Classes**

* Superficial-Intermediate
* Parabasal
* Koilocytotic
* Metaplastic
* Dyskeratotic

### 2. UCI Cervical Cancer Risk Factors Dataset

Used for clinical risk prediction.

**Dataset Details**

* Records: 858
* Clinical Attributes: 36

**Examples**

* Age
* Number of Sexual Partners
* First Sexual Intercourse
* Number of Pregnancies
* Smoking History
* Hormonal Contraceptive Usage
* STD History

---

## 🧠 Machine Learning Models

### CNN (Convolutional Neural Network)

Used for:

* Cervical cell image classification
* Feature extraction from Pap smear images

### FT-Transformer

Used for:

* Clinical risk prediction
* Tabular healthcare data analysis

**Advantages**

* Handles structured medical datasets effectively
* Learns feature interactions automatically

### XGBoost

Used for:

* Clinical risk assessment
* Feature-based prediction

**Advantages**

* High predictive performance
* Robust handling of structured healthcare data

---

## 📊 Data Analysis & Visualization

The platform provides:

* Dynamic risk visualization charts
* Prediction confidence analysis
* Comparative risk interpretation
* Patient-specific analytics dashboard

**Libraries Used**

* Matplotlib
* NumPy
* Pandas

---

## 📄 Report Generation

Generated PDF reports include:

* Patient Information
* Clinical Risk Score
* Image Classification Result
* Prediction Confidence
* Risk Analytics Summary
* Timestamp of Analysis

---

## 💻 Technology Stack

### Frontend

* React.js
* JavaScript
* Tailwind CSS
* Framer Motion

### Backend

* FastAPI
* Python

### Machine Learning & AI

* TensorFlow
* Keras
* PyTorch
* FT-Transformer
* XGBoost
* NumPy
* Pandas

### Data Visualization

* Matplotlib

### Reporting

* ReportLab

### AI Assistant

* Ollama
* Llama 3

---

## 📁 Project Structure

```text
cervical_cancer_ai/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── services/
│
├── backend/
│   ├── models/
│   │   ├── sipakmed_cnn_model.h5
│   │   ├── ft_transformer_model.pt
│   │   └── xgboost_risk_model.json
│   │
│   ├── main.py
│   ├── image_service.py
│   ├── clinical_service.py
│   └── models_loader.py
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/srivarsha25/cervical-cancer-ai.git
cd cervical-cancer-ai
```

### Backend Setup

```bash
cd backend

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --host 127.0.0.1 --port 8000
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

---

## 📈 Future Enhancements

* Cloud Deployment
* Multi-Hospital Integration
* Electronic Health Record (EHR) Integration
* Explainable AI (XAI)
* Real-Time Telemedicine Support
* Multi-Language AI Assistant
* Advanced Risk Forecasting

---

## 🎓 Academic Significance

This project demonstrates the integration of:

* Healthcare Analytics
* Machine Learning
* Deep Learning
* Medical Image Processing
* Full-Stack Web Development
* Data Visualization
* AI-Assisted Healthcare Systems

---

## 👨‍💻 Author

**Gudupudi Srivarsha**

---

## 📜 License

This project is developed for educational, academic, and research purposes. It is not intended to replace professional medical diagnosis or healthcare consultation.
