# 🍷 Wine Quality Prediction using Machine Learning  

Welcome to the **Wine Quality Prediction Project**!   
The project demonstrates how to **predict wine quality** using **Random Forest Classifier** based on chemical parameters.  

---

## 📌 Project Objective  
The goal is to build a **predictive system** that can classify wine as **Good (1) or Bad (0)** based on its **chemical properties**.  
This is a practical example of applying **Machine Learning in the food & beverage industry** for **quality control** ✅.  

---

## 🏭 Problem Statement  
A wine manufacturing company wants to launch a **new brand of wine**.  
The challenge for the data scientist is to **predict wine quality** from parameters like:  

- 🍋 Fixed Acidity  
- 🧪 Citric Acid  
- 🍬 Residual Sugar  
- 🍷 Alcohol  
- ⚗️ Volatile Acidity  

**Key insights:**  
- Higher **citric acid** and **alcohol** = better wine.  
- Higher **volatile acidity** and **sugar** = lower quality wine.  

---

## 📊 Dataset Information  
- 📥 **Source:** [Kaggle Wine Quality Dataset](https://www.kaggle.com/)  
- 🧾 **Size:** `1599 rows × 12 columns`  
- 🎯 **Target Column:** `quality`  

### ⚙️ Preprocessing  
- ✅ Features (X): All chemical parameters  
- 🎯 Labels (y): Wine Quality (binary)  
  - `Good (1)` → Quality ≥ 7  
  - `Bad (0)` → Quality ≤ 6  
- 📂 Train-Test Split: **80-20%**  

---

## 🔄 Workflow  

```mermaid
flowchart TD
    A[📥 Collect Dataset] --> B[🔍 Data Analysis & Visualization]
    B --> C[🧹 Data Preprocessing]
    C --> D[✂️ Train-Test Split]
    D --> E[🌳 Random Forest Classifier Training]
    E --> F[📈 Model Evaluation]
    F --> G[🤖 Predictive System Build]
