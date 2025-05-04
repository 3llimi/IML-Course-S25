# 🌱 IML Assignment 2: Seasonal Energy Classification

This project explores machine learning techniques to classify seasonal energy usage based on Denmark's hourly energy data. It evaluates multiple deep learning models for their effectiveness in capturing temporal and seasonal patterns.

---

## 📊 Dataset

The dataset includes:
- **Features**: Hourly data (24 per day) on:
  - Power Load
  - Wind Generation
  - Solar Generation
- **Target**: Seasonal classification (Winter, Spring, Summer, Fall)

---

## 🛠️ Preprocessing

- Missing values handled via **forward-fill**
- Standardization using **StandardScaler**
- Labels mapped to corresponding **seasons**

---

## 🧠 Models

| Model           | Description                                 | Accuracy |
|-----------------|---------------------------------------------|----------|
| **MLP**         | Baseline Multi-Layer Perceptron             | 81.27%   |
| **1D-CNN**      | Temporal pattern extraction via 1D convolutions | 83.49%   |
| **2D-CNN + GAF**| Time-series transformed with Gramian Angular Fields + CNN | 84.76%   |

📈 **Accuracy Improvements**:
- 1D-CNN: +2.22% over MLP
- 2D-CNN + GAF: +3.49% over MLP

---



