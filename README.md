# Heart_Disease_prediction_using_deep_learning

---
## 📌 Overview

This project presents a hybrid deep learning system for binary heart disease classification. It combines:

- A neural network trained on **clinical tabular data** from the UCI Cleveland dataset.
- A CNN trained on **ECG image data**.
- A **fusion mechanism** to combine both model predictions into a final decision.

The goal is to mirror real-world diagnostic reasoning by integrating both structured data and physiological signals.

---

## 📊 Datasets Used

- **Tabular Data:** UCI Cleveland Heart Disease Dataset  
  🔗 https://archive.ics.uci.edu/ml/datasets/heart+Disease  
- **Image Data:** ECG images categorized as:
  - Normal
  - Abnormal heartbeat
  - Myocardial infarction
  - History of MI

---

## 🔧 Key Features

- ✅ Tabular preprocessing with **SMOTE** and **StandardScaler**
- ✅ Hyperparameter tuning with **Keras Tuner**
- ✅ CNN training with **ImageDataGenerator**
- ✅ Ensemble prediction via **simple averaging**
- ✅ Performance visualizations:
  - Confusion matrix
  - ROC and PR curves
  - Training history plots

---

## 🚀 How to Run

### 1. Full code base
```bash
heart_disease_prediction.ipynb
