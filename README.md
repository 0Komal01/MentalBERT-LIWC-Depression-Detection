# Explainable AI for Adolescent Depression Screening

An **Explainable AI (XAI)** framework for detecting depression from social media text using **MentalBERT, LIWC features, Attention-based Fusion, and BiLSTM**.

## 🔍 Overview

The proposed approach combines contextual language representations from MentalBERT with psycholinguistic LIWC features to identify depression-related patterns in Reddit and Twitter posts.

It also provides:

* 🧠 Depression classification
* 📊 PHQ-9-inspired severity levels
* 🔎 LIME & SHAP explanations
* 🔄 Cross-platform evaluation
* 📈 Ablation and attention analysis

## 🛠️ Tech Stack

**Python · PyTorch · Transformers · MentalBERT · LIWC · scikit-learn · LIME · SHAP · Pandas · NumPy · Matplotlib**

## 📂 Project Structure

```text
IMPLEMENTATIONS/
├── V1/
│   ├── final-notebook-1.ipynb   # Data Preparation & EDA
│   ├── final-notebook-2.ipynb   # Model Training
│   └── final-notebook-3.ipynb   # Ablation & Explainability
├── V2/
└── V3/
```

## 📊 Results

* **Accuracy:** 82.18%
* **F1-Score:** 0.8218
* **AUC-ROC:** 0.9137
* **Dataset:** 24,574 Reddit & Twitter posts
* **Cross-platform Twitter F1:** 0.7686

## ⚙️ Pipeline

**Social Media Data → Preprocessing → LIWC + MentalBERT → Attention Fusion → BiLSTM → Depression & Severity Prediction → LIME/SHAP Explanation**

## ⚠️ Disclaimer

This project is intended as a **research and screening-support tool**, not a clinical diagnostic system. Predictions should not replace assessment by qualified mental-health professionals.


