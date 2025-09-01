# 💳 Data Balancing with GANs: Credit Card Fraud Detection

Fraudulent credit card transactions are **rare but costly**, making fraud detection a critical task. However, the **high class imbalance** between legitimate and fraudulent transactions creates challenges for traditional machine learning models.  

This project demonstrates how **Generative Adversarial Networks (GANs)** can generate **synthetic fraudulent transactions** to balance the dataset and improve fraud detection model performance.  

---

## 🚀 Workflow Overview
The notebook walks through the following steps:

### 1️⃣ Importing the Dataset  
- Load the credit card dataset.  
- Inspect data shape and class imbalance.  

### 2️⃣ Data Preprocessing & Exploration  
- Remove missing values.  
- Drop irrelevant columns (`Time`).  
- Scale features (e.g., `Amount`).  
- Split into features & labels.  
- Visualize class imbalance.  

### 3️⃣ Building the GAN  
- **Generator model**: creates synthetic fraudulent transactions.  
- **Discriminator model**: distinguishes real from synthetic samples.  
- Combine both into a **GAN framework**.  

### 4️⃣ Training the GAN  
- Define training variables & loop.  
- Train generator and discriminator in an adversarial setup.  
- Monitor GAN performance using **PCA visualization**.  

### 5️⃣ Generating Synthetic Data  
- Use the trained Generator to produce **1000+ fraudulent samples**.  
- Compare distribution of **real vs synthetic fraud data**.  

---

## ✨ Key Features
- End-to-end **GAN implementation** for data balancing.  
- Synthetic fraud sample generation for **rare event detection**.  
- Evaluation of data quality through visualizations.  
- Improved training data for fraud detection models.  

---

