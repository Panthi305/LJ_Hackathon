# LJ_Hackathon
# 🐄 KrushiMitra: AI-Powered Cattle Health & Milk Yield Predictor

### Problem Statement #8: AI/ML-Based Cattle Milk Yield and Health Prediction

---

## ❓ Problem Statement
Dairy farmers face significant challenges due to unpredictable milk yield fluctuations, which are often an early sign of cattle health issues such as mastitis or nutritional deficiencies.  
Traditional manual observation leads to **delayed detection** and **economic losses**.

### 🚩 The Challenge
Build an AI/ML platform that:
- Predicts **individual cattle milk yield** based on multifaceted inputs.  
- Detects and diagnoses potential **diseases early** by analyzing health and activity data.  
- Integrates with a **farmer-friendly dashboard** for input, alerts, and actionable insights.  

---

## 📌 Overview
**KrushiMitra** is an intelligent decision-support system designed to empower dairy farmers.  
By leveraging **machine learning**, it transforms raw data on cattle health, nutrition, and environment into:
- **Predictive insights**  
- **Early health warnings**  

This enables **proactive farm management** and **maximizes productivity**.

---

## ✨ Key Features

### 🤖 ML-Powered Milk Yield Prediction
- A **regression model** forecasts daily milk output per animal using:
  - Breed  
  - Feed quality  
  - Activity levels  
  - Lactation stage  

### 🏥 Early Disease Detection & Alerts
- A **classification model** diagnoses potential diseases (e.g., mastitis, digestive disorders).  
- Immediate **health alerts** are sent before yield drops significantly.  

### 📊 Interactive Farmer Dashboard
- Intuitive **web interface** for:
  - Data input  
  - Viewing predictions  
  - Color-coded health alerts  
  - Recommended actions  

### 📈 Comprehensive Data-Driven Reporting
- Generate detailed reports on:
  - Yield trends  
  - Feed utilization  
  - Health analysis  
- Export in **PDF / Excel** formats.  

### 🌤 Environmental Integration
- Considers external conditions:
  - Temperature  
  - Humidity  
  - Seasonal patterns  
- Ensures **accurate predictions & smart recommendations**.  

---

## ⚙ Tech Stack

**Frontend:** React + Vite  
**Backend:** Flask (Python)  
**AI/ML:** Scikit-learn, TensorFlow, Pandas, NumPy  
**Database:** MongoDB Atlas   


---

## 🚀 Getting Started

### 🔹 Backend Setup
```bash
# Navigate to backend folder
cd backend

# Create a virtual environment
python -m venv venv

# Activate environment
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the Flask application
python app.py
