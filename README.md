# Liver Tumor Detection System

An AI-powered liver tumor detection system that uses deep learning techniques to analyze CT scan images and assist in identifying potential liver tumors.

The system combines a **PyTorch-based deep learning model**, a **FastAPI backend**, and a **Next.js frontend** to provide an end-to-end medical AI application.

---

# Developed By

## Zynox Tech

Website: https://zynoxtech.site  
Email: hello@zynoxtech.site  
Location: Abbottabad, Pakistan

Zynox Tech is a software development company specializing in:

- Artificial Intelligence Solutions
- Machine Learning Applications
- Web Applications
- Mobile Applications
- Enterprise Software
- Custom Digital Products

We build innovative, scalable, and reliable technology solutions that help businesses and organizations solve real-world challenges.

For AI solutions, software development, and technology partnerships:

Website: https://zynoxtech.site  
Email: hello@zynoxtech.site

---

# Project Overview

The **Liver Tumor Detection System** is an AI-based medical imaging application designed to assist in liver tumor detection from CT scan images.

The system uses deep learning with **ResNet18** architecture trained on the **LiTS (Liver Tumor Segmentation) dataset**.

It provides:

- CT scan image analysis
- AI-based tumor detection
- Prediction results through API
- Web-based user interface
- Secure authentication and data management

---

# Project Structure

```
LiverDetectionModel/

├── backend/
│   └── FastAPI server
│       └── Docker deployment on HuggingFace Spaces

├── frontend/
│   └── Next.js web application
       ├── Firebase Authentication
       └── Firestore database
```

---

# Quick Start

## Backend Setup

The backend is deployed on HuggingFace Spaces:

```
https://hashammubarak1-liver-tumor-detection-api.hf.space
```

Run locally:

```bash
cd backend
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start the API:

```bash
python main.py
```

---

# Frontend Setup

Navigate to frontend:

```bash
cd frontend
```

Create environment file:

```bash
cp .env.local.example .env.local
```

Add your Firebase credentials inside:

```
.env.local
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Open:

```
http://localhost:3000
```

---

# Technology Stack

## Artificial Intelligence

- PyTorch
- ResNet18
- Deep Learning
- LiTS Dataset

## Backend

- FastAPI
- Python
- Docker
- HuggingFace Spaces Deployment

## Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS v4

## Authentication & Database

- Firebase Authentication
- Firebase Firestore

---

# Detection Methodology

The model uses:

- ResNet18 deep learning architecture
- Frozen early layers for efficient training
- CT scan image analysis
- Slice-based detection approach

Detection logic:

- 70% slice threshold
- 11% affected ratio cutoff

---

# Features

- AI-powered CT scan analysis
- Deep learning-based tumor detection
- Fast API inference system
- Modern web interface
- User authentication
- Cloud database integration
- Docker-based deployment
- Scalable architecture

---

# Deployment

## Backend

Hosted using:

- HuggingFace Spaces
- Docker

## Frontend

Can be deployed using:

- Vercel
- Netlify
- Firebase Hosting

---

# Future Improvements

Possible improvements:

- Improved segmentation accuracy
- Additional medical imaging support
- Larger training datasets
- Real-time inference optimization
- Advanced reporting system

---

# License

This project was developed by **Zynox Tech**.

For AI solutions, machine learning systems, and custom software development:

Zynox Tech  
Website: https://zynoxtech.site  
Email: hello@zynoxtech.site  

---

Developed by **Zynox Tech**  
Abbottabad, Pakistan
