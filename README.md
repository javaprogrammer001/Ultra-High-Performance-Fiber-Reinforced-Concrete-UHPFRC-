# 🧠 EPTANN — Enhanced Phase Time Adaptive Neural Network  
A time-adaptive neural architecture designed for dynamic signal modeling, temporal prediction, and interpretable feature learning.

---

## 📌 Overview  
The **Enhanced Phase Time Adaptive Neural Network (EPTANN)** is built to process **time-varying, sequential, or dynamic signals**.  
It adapts its internal parameters based on temporal context, providing both **accuracy** and **interpretability**.

---

## 🏗️ Architecture Structure  

### ### 1️⃣ Input Layer  
- Accepts sequential or time-series feature vectors  
- Supports variable sequence lengths  

---

### 2️⃣ Time-Adaptive Encoding Block  
Components:  
- Temporal Convolution Layer  
- Phase-Shift Learning Module  
- Gated Activation Unit (GAU)

Key Features:  
- Learns fine-grained temporal transitions  
- Dynamically adapts to changing patterns  

---

### 3️⃣ Multi-Scale Feature Extraction Block  
Contains:  
- Dilated CNNs  
- Residual Skip Connections  
- Temporal Multi-Scale Kernels  

Purpose:  
- Captures short-term + long-term dependencies  

---

### 4️⃣ Time-Adaptive Normalization  
- Normalization parameters vary at each time-step  
- Improves convergence and stabilizes training  

---

### 5️⃣ Dense Reconstruction Block  
- Several fully connected layers  
- Final prediction or reconstruction output  

---

## ⚡ Activation Functions  
- **ReLU** → feature extraction  
- **Tanh** → gating mechanisms  
- **Sigmoid** → adaptive control modules  

---

## 🎯 Key Advantages  
- Learns **dynamic temporal patterns**  
- Produces **interpretability outputs** such as:  
  - Temporal attention heatmaps  
  - Phase-shift visualization  
  - Adaptive weight evolution plots  
- Robust for non-stationary signals  

---

## 📊 Block Diagram (ASCII Representation)

