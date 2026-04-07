# 🌿 PhytoShield
### Intelligent Plant Disease Detection & Treatment System

PhytoShield is a hybrid soft computing system that 
detects plant diseases from leaf images and provides 
intelligent severity assessment with treatment 
recommendations.

## 🧠 Tech Stack
- **CNN** — Detects plant disease from leaf image
- **Fuzzy Logic** — Assesses disease severity using 
  Mamdani inference system
- **Fuzzy-Neural Hybrid** — Recommends treatment category
- **LLM (Gemini API)** — Generates farmer-friendly reports
- **React + Flask** — Modern web interface

## 🌱 Features
- Detects 38 plant diseases across 14 crops
- Fuzzy severity scoring (Very Low → Critical)
- Intelligent treatment recommendation
- Plain English diagnosis report
- Beautiful React dashboard

## 📚 Soft Computing Concepts
- Fuzzy Sets & Membership Functions
- Mamdani Fuzzy Inference System
- Centroid Defuzzification
- Fuzzy-Neural Hybrid Architecture
- Artificial Neural Networks

## 🚀 Run Locally
# Backend
cd backend
pip install -r requirements_backend.txt
python app.py

# Frontend  
cd frontend
npm install
npm run dev

## 📊 Dataset
PlantVillage Dataset — 87,000 images, 38 classes
