# Multimodal Gesture Recognition using CNN–GCN–LSTM  
**With RGB, Depth, and Skeleton Data**

## 📌 Overview
This project presents a **multimodal gesture recognition system** that integrates **RGB video**, **Depth data**, and **Skeleton-based joint information** to accurately recognize human gestures.  
By combining **Convolutional Neural Networks (CNNs)**, **Graph Convolutional Networks (GCNs)**, and **Long Short-Term Memory (LSTM)** networks, the model captures **spatial**, **structural**, and **temporal** features effectively.

The implementation is provided as a **Google Colab–ready Jupyter Notebook**, making it easy to reproduce and experiment with.

---

## 🎯 Objectives
- Leverage **multiple modalities** to improve gesture recognition accuracy  
- Capture:
  - Spatial features from RGB & Depth data (CNN)
  - Structural relationships in skeleton joints (GCN)
  - Temporal dynamics of gestures (LSTM)
- Build an end-to-end deep learning pipeline for multimodal learning

---

## 🧠 Methodology

### 🔹 RGB & Depth Stream
- Processed using **Convolutional Neural Networks (CNNs)**
- Extracts spatial visual features from video frames

### 🔹 Skeleton Stream
- Skeleton joints modeled as a **graph**
- Processed using **Graph Convolutional Networks (GCNs)**

### 🔹 Temporal Modeling
- Features from all modalities are fused
- **LSTM** captures temporal dependencies across frames

### 🔹 Fusion Strategy
- Multimodal feature fusion before classification
- Final softmax layer predicts gesture classes


