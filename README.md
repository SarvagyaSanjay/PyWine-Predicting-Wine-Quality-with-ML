# 🍷 Wine Quality Prediction using Machine Learning  

Welcome to the **Wine Quality Prediction Project**!   
The project demonstrates how to **predict wine quality** using **Random Forest Classifier** based on chemical parameters.  

---
## This is the accuracy result along with a test done
<img width="740" height="686" alt="image" src="https://github.com/user-attachments/assets/cbeb2ab7-2175-4569-8c90-98ae92eae346" />


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
📥 **Source:** [Kaggle - Red Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009?resource=download)
- 🧾 **Size:** `1599 rows × 12 columns`  
- 🎯 **Target Column:** `quality`  

### ⚙️ Preprocessing  
- ✅ Features (X): All chemical parameters  
- 🎯 Labels (y): Wine Quality (binary)  
  - `Good (1)` → Quality ≥ 7  
  - `Bad (0)` → Quality ≤ 6  
- 📂 Train-Test Split: **80-20%**  

---

## Predictive System and Evaluation
The predictive system takes chemical parameters as input and outputs wine quality as 0 (bad) or 1 (good).
The random forest model achieves an accuracy score of 0.925, correctly predicting wine quality for 93 out of 100 samples.

## Model Comparison
This model comparision shows that Random Forest performs the best amongst all the three models.
<img width="1194" height="222" alt="image" src="https://github.com/user-attachments/assets/415a8933-27fb-4945-8e67-2f63161d2348" />


## 🔄 Workflow  

```mermaid
flowchart TD
    A[📥 Collect Dataset] --> B[🔍 Data Analysis & Visualization]
    B --> C[🧹 Data Preprocessing]
    C --> D[✂️ Train-Test Split]
    D --> E[🌳 Random Forest Classifier Training]
    E --> F[📈 Model Evaluation]
    F --> G[🤖 Predictive System Build]
