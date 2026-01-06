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


---

## 🚀 How to Run

### Option 1: Run on Google Colab (Recommended)
1. Open the notebook in **Google Colab**
2. Ensure runtime is set to **GPU**
3. Run all cells sequentially

### Option 2: Run Locally
1. Install dependencies (see below)
2. Launch Jupyter Notebook
3. Open and run the `.ipynb` file

---

## 📦 Requirements
The project uses common deep learning libraries:
- Python 3.x
- PyTorch / TensorFlow (depending on implementation)
- NumPy
- OpenCV
- Matplotlib
- NetworkX (for graph operations)
- Jupyter Notebook

> Exact dependencies are listed/imported inside the notebook.

---

## 📊 Results
- The multimodal approach improves robustness compared to single modality models
- Effectively captures both **motion dynamics** and **body structure**
- Demonstrates the advantage of **CNN + GCN + LSTM** fusion for gesture recognition

---

## 🧪 Notes
- Large datasets and trained model weights are **not included** in this repository
- The notebook focuses on **implementation and experimentation**
- Outputs can be cleared before final submission if required

---

## 📚 Applications
- Human–Computer Interaction (HCI)
- Sign Language Recognition
- Surveillance and Activity Recognition
- AR/VR gesture-based interfaces

---

## ✍️ Author
**Md. Asraful Islam Khan** **Syful Islam**

---

## 📜 License
This project is for **academic and research purposes**.  
Feel free to use, modify, and reference with proper attribution.

