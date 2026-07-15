# Liver Tumor Detection System

An AI-powered liver tumor detection system that uses deep learning techniques to analyze CT scan images and assist in identifying potential liver tumors.

The system combines a **PyTorch-based deep learning model**, a **FastAPI backend**, and a **Next.js frontend** to provide an end-to-end medical AI application.

---

# Developed By

## Zynox Tech

**Website:** https://zynoxtech.site
**Email:** [hello@zynoxtech.site](mailto:hello@zynoxtech.site)
**Location:** Abbottabad, Pakistan

Zynox Tech is a software development company specializing in:

* Artificial Intelligence Solutions
* Machine Learning Applications
* Web Applications
* Mobile Applications
* Enterprise Software
* Custom Digital Products

We build innovative, scalable, and reliable technology solutions that help businesses and organizations solve real-world challenges.

For AI solutions, software development, and technology partnerships:

**Website:** https://zynoxtech.site
**Email:** [hello@zynoxtech.site](mailto:hello@zynoxtech.site)

---

# Project Overview

The **Liver Tumor Detection System** is an AI-based medical imaging application designed to assist in detecting potential liver tumors from CT scan images.

The system uses deep learning with a **ResNet18 architecture** trained using the **LiTS (Liver Tumor Segmentation) dataset**.

The platform combines artificial intelligence, cloud-based backend services, and a modern web interface to provide an accessible medical image analysis workflow.

The system provides:

* CT scan image analysis
* AI-based liver tumor detection
* Deep learning-powered predictions
* API-based model inference
* Modern web-based user interface
* Secure user authentication
* Cloud-based data management

---

# Application Preview

## Main Interface

<p align="center">
  <img src="https://github.com/user-attachments/assets/b5f6b3b0-b6b7-4c63-9d25-30ebecf4b74f" width="850" alt="Liver Tumor Detection Main Interface"/>
</p>

---

## CT Scan Analysis

<p align="center">
  <img src="https://github.com/user-attachments/assets/5e1c3a6b-b1a0-4857-88e7-bada4b503e51" width="850" alt="Liver CT Scan Analysis"/>
</p>

---

## AI Detection Interface

<p align="center">
  <img src="https://github.com/user-attachments/assets/f091f1e5-821d-4722-a777-cb3685f21478" width="850" alt="AI Liver Tumor Detection Interface"/>
</p>

---

## Prediction Results

<p align="center">
  <img src="https://github.com/user-attachments/assets/914ccd33-520b-4e6d-b750-90bdc6310992" width="850" alt="Liver Tumor Prediction Results"/>
</p>

---

# Features

## AI-Powered CT Scan Analysis

* Deep learning-based medical image analysis
* CT scan processing
* Automated tumor pattern detection
* Fast AI inference workflow

---

## Liver Tumor Detection

* ResNet18 deep learning architecture
* Slice-based CT scan analysis
* Confidence-based detection workflow
* Automated image evaluation

---

## Modern Web Interface

* Responsive web application
* Clean medical AI interface
* Simple image upload workflow
* User-friendly prediction results

---

## Secure Authentication

* Firebase Authentication
* Secure user access
* User account management
* Cloud-based authentication services

---

## Cloud Data Management

* Firebase Firestore integration
* Cloud-based application data
* Scalable data architecture
* Secure data management

---

## API-Based AI Inference

* FastAPI backend
* REST-based model communication
* Fast prediction processing
* Scalable backend architecture

---

# Technology Stack

## Artificial Intelligence

* Python
* PyTorch
* ResNet18
* Deep Learning
* Medical Image Processing
* LiTS Dataset

## Backend

* FastAPI
* Python
* Docker
* REST API
* Hugging Face Spaces

## Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS v4

## Authentication & Database

* Firebase Authentication
* Firebase Firestore

---

# System Architecture

The application follows a modern AI-powered web architecture:

```text
User
  │
  ▼
Next.js Frontend
  │
  ├── Firebase Authentication
  │
  ├── Firebase Firestore
  │
  ▼
FastAPI Backend
  │
  ▼
Image Preprocessing
  │
  ▼
ResNet18 Deep Learning Model
  │
  ▼
Tumor Detection Analysis
  │
  ▼
Prediction Result
  │
  ▼
Web Interface
```

This architecture separates the frontend, backend, artificial intelligence model, and cloud services into independent application components.

---

# Detection Methodology

The liver tumor detection model uses a **ResNet18 deep learning architecture** for medical image analysis.

The detection process includes:

1. CT scan image input
2. Image preprocessing
3. Slice-based analysis
4. Deep learning model inference
5. Affected slice calculation
6. Tumor probability evaluation
7. Prediction result generation

The detection logic uses:

```text
70% Slice Threshold
11% Affected Ratio Cutoff
```

These thresholds are used within the application's prediction workflow to evaluate analyzed CT scan slices.

---

# Project Structure

```text
LiverDetectionModel/

├── backend/
│   ├── main.py
│   ├── requirements.txt
│   ├── model/
│   ├── utils/
│   └── Dockerfile
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── lib/
│   ├── public/
│   ├── package.json
│   └── .env.local
│
└── README.md
```

The project separates the AI backend and frontend web application into dedicated modules.

---

# Quick Start

## Requirements

Before running the project, install:

* Python 3.10+
* Node.js 18+
* npm
* Git
* Firebase Account

Verify Python:

```bash
python --version
```

Verify Node.js:

```bash
node --version
```

---

# Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Create a Python virtual environment:

```bash
python -m venv venv
```

Activate the environment.

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

Install backend dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI server:

```bash
python main.py
```

The backend API will run locally according to the configured FastAPI server settings.

---

# Cloud Backend

The backend is deployed using **Hugging Face Spaces** and Docker.

Backend API:

```text
https://hashammubarak1-liver-tumor-detection-api.hf.space
```

The cloud API allows the frontend application to communicate with the deployed AI model.

---

# Frontend Setup

Navigate to the frontend directory:

```bash
cd frontend
```

Create the environment configuration file:

```bash
cp .env.local.example .env.local
```

Add Firebase configuration credentials inside:

```text
.env.local
```

Install frontend dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the application:

```text
http://localhost:3000
```

---

# Firebase Setup

## Create Firebase Project

1. Open the Firebase Console.
2. Create a new Firebase project.
3. Add a web application.
4. Copy the Firebase configuration credentials.

---

## Enable Authentication

Enable the required authentication providers inside Firebase Authentication.

---

## Configure Firestore

Create a Firebase Firestore database for cloud-based application data management.

Add the Firebase credentials to:

```text
.env.local
```

---

# Application Workflow

```text
User Login
    │
    ▼
Upload CT Scan
    │
    ▼
Frontend Sends Image to API
    │
    ▼
FastAPI Receives Image
    │
    ▼
Image Preprocessing
    │
    ▼
ResNet18 Model Analysis
    │
    ▼
Slice-Based Detection
    │
    ▼
Tumor Probability Evaluation
    │
    ▼
Prediction Result
    │
    ▼
Result Displayed to User
```

---

# AI Model

The system uses **ResNet18**, a convolutional neural network architecture designed for image classification tasks.

The model implementation includes:

* Transfer learning
* Frozen early network layers
* Medical CT scan analysis
* Slice-based image processing
* Tumor detection logic

Using frozen early layers allows the model to retain previously learned image features while adapting later layers for liver tumor detection.

---

# Dataset

The AI model is developed using the **LiTS — Liver Tumor Segmentation Dataset**.

The dataset contains medical CT scan data used for liver and liver tumor research.

The dataset supports research in:

* Liver segmentation
* Tumor segmentation
* Medical image processing
* Deep learning
* Computer vision

---

# Deployment

## Backend Deployment

The backend is deployed using:

* Hugging Face Spaces
* Docker

The Docker-based backend provides a consistent runtime environment for the FastAPI application and AI model.

---

## Frontend Deployment

The frontend can be deployed using:

* Vercel
* Netlify
* Firebase Hosting

For Next.js applications, Vercel provides a streamlined deployment workflow.

---

# Security and Data Handling

The application uses:

* Firebase Authentication
* Controlled user access
* Environment-based credentials
* API-based backend communication
* Structured cloud data management

Sensitive configuration information should never be committed directly to the repository.

Store Firebase credentials and application configuration inside environment files.

Example:

```text
.env.local
```

---

# Medical Disclaimer

This AI system is developed for **educational, research, and software demonstration purposes only**.

The predictions generated by this application must not be considered a final medical diagnosis.

The system is designed to demonstrate artificial intelligence and medical image analysis technologies.

All medical diagnoses, treatment decisions, and healthcare recommendations must be made by qualified healthcare professionals.

---

# Future Improvements

Possible future enhancements include:

* Improved liver tumor segmentation
* Larger medical imaging datasets
* Advanced model architectures
* Multi-class tumor classification
* Automated medical report generation
* Doctor dashboard integration
* Patient history management
* Cloud-based AI inference optimization
* DICOM image support
* Explainable AI visualization
* Tumor region highlighting
* Advanced confidence analysis

---

# License

This project was developed by **Zynox Tech**.

For AI solutions, machine learning systems, medical AI applications, and custom software development:

**Zynox Tech**
**Website:** https://zynoxtech.site
**Email:** [hello@zynoxtech.site](mailto:hello@zynoxtech.site)
**Location:** Abbottabad, Pakistan

---

# About Zynox Tech

Zynox Tech develops modern, scalable, and intelligent software solutions for businesses and organizations.

Our services include:

* Artificial Intelligence Solutions
* Machine Learning Applications
* Medical AI Systems
* Custom Software Development
* Enterprise Applications
* Mobile Applications
* Web Platforms
* Business Automation Systems

We combine modern software engineering practices with artificial intelligence technologies to develop reliable and user-focused digital products.

For software development services and technology partnerships:

**Website:** https://zynoxtech.site
**Email:** [hello@zynoxtech.site](mailto:hello@zynoxtech.site)

---

<div align="center">

### Developed by **Zynox Tech**

**Building Modern AI and Technology Solutions for Real-World Challenges**

</div>
