# Explainable AI for Adolescent Depression Screening

An **Explainable AI (XAI)** framework for detecting and screening depression-related patterns in adolescent social media text using **MentalBERT, LIWC features, Attention-based Fusion, and BiLSTM**.

## 🚨 Problem

Adolescent depression is often **under-detected and diagnosed late** due to stigma, limited access to mental-health professionals, and difficulty identifying early symptoms. Social media can contain valuable linguistic indicators of emotional distress, but many existing AI approaches lack **interpretability, severity assessment, and cross-platform robustness**.

## 💡 Solution

We propose an explainable deep-learning framework that:

* Uses **MentalBERT** to capture mental-health-specific language patterns.
* Extracts **LIWC psycholinguistic features** to capture interpretable linguistic signals.
* Uses an **Attention Gate** to combine both representations.
* Applies **BiLSTM** for contextual classification.
* Provides **PHQ-9-inspired severity levels**: Not Depressed, Mild, Moderate, and Severe.
* Uses **LIME and SHAP** to explain model predictions.
* Evaluates **cross-platform generalization** across Reddit and Twitter.

## ✨ Key Novelty

The main contribution is the **combination of multiple complementary components in one framework**:

1. **MentalBERT + LIWC fusion** for contextual and psycholinguistic information.
2. **Learned Attention-based fusion** instead of simple feature concatenation.
3. **Dual explainability using LIME + SHAP** for transparent predictions.
4. **PHQ-9-inspired four-level severity screening**.
5. **Cross-platform evaluation** to study generalization between Reddit and Twitter.
6. **Adolescent-focused social-media depression screening** combining these components in a single framework.

## 📊 Results

| Metric                               |           Result |
| ------------------------------------ | ---------------: |
| Accuracy                             |       **82.18%** |
| F1-Score                             |       **0.8218** |
| AUC-ROC                              |       **0.9137** |
| Dataset                              | **24,574 posts** |
| Twitter F1 (mixed-platform training) |       **0.7686** |

## 🛠️ Tech Stack

**Python · PyTorch · Transformers · MentalBERT · LIWC · scikit-learn · LIME · SHAP · Pandas · NumPy · Matplotlib**

## ⚙️ Pipeline

**Social Media Data → Preprocessing → MentalBERT + LIWC → Attention Fusion → BiLSTM → Depression/Severity Prediction → LIME & SHAP Explanation**

## ⚠️ Disclaimer

This project is a **research and screening-support system**, not a clinical diagnostic tool. Predictions should not replace assessment by qualified mental-health professionals.
