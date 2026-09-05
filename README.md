# 📰 Evaluating Model Agreement in Explainable Fake News Detection Using Transformer-Based Models

> Measuring not just what AI predicts — but how consistently, fairly, and explainably it reaches those predictions.

---

## 📌 Overview

Fake news detection has become one of the most critical challenges in the age of digital information. While modern Transformer-based models achieve impressive classification performance, they often operate as black boxes, providing little insight into how decisions are made.

This project investigates a fundamental question:

**Can highly accurate AI models also be trusted, explained, and shown to agree with one another?**

To answer this, the project evaluates multiple Transformer architectures and Explainable AI (XAI) techniques while introducing agreement-based evaluation metrics to assess reliability beyond traditional performance measures.

---

## 🎯 Research Objectives

* Compare Transformer-based models for fake news detection.
* Benchmark against traditional Machine Learning approaches.
* Interpret model predictions using Explainable AI techniques.
* Measure inter-model agreement and reliability.
* Evaluate fairness and trustworthiness in AI decision-making.

---

## 🏗️ Project Architecture

```text
LIAR Dataset
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Feature Engineering / Tokenization
      │
      ├── Traditional ML Models
      │      ├── Logistic Regression
      │      ├── Random Forest
      │      ├── SVM
      │      └── XGBoost
      │
      └── Transformer Models
             ├── BERT
             ├── RoBERTa
             └── DistilBERT
      │
      ▼
Model Evaluation
      │
      ├── Accuracy
      ├── Precision
      ├── Recall
      ├── F1 Score
      ├── ROC-AUC
      ├── Cohen's Kappa
      ├── Fleiss' Kappa
      └── Fairness Metrics
      │
      ▼
Explainability Analysis
      ├── SHAP
      ├── LIME
      └── BertViz Attention Visualization
```

---

## 📂 Dataset

### LIAR Dataset

The project uses the widely recognized **LIAR Benchmark Dataset**, containing:

* 12,836 human-verified political statements
* Fact-checked by PolitiFact
* Balanced true/false representation
* Suitable for misinformation research and model comparison

---

## 🤖 Models Evaluated

### Traditional Machine Learning Models

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest
* XGBoost

### Transformer Models

* BERT
* RoBERTa
* DistilBERT

---

## 🔍 Explainable AI Techniques

Understanding model decisions is as important as achieving high accuracy.

### SHAP

Provides both local and global explanations by identifying influential features contributing to predictions.

### LIME

Generates interpretable, instance-level explanations for individual predictions.

### BertViz

Visualizes attention mechanisms within Transformer architectures to better understand contextual reasoning.

---

## 📊 Evaluation Framework

This research moves beyond conventional classification metrics.

### Performance Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

### Agreement Metrics

* Cohen's Kappa
* Fleiss' Kappa

### Fairness Metrics

* Demographic Parity
* Equalized Odds

### Statistical Validation

* One-Way ANOVA Testing

---

## 🏆 Key Results

| Model      | Accuracy |
| ---------- | -------- |
| DistilBERT | 65.43%   |
| BERT       | 65.35%   |
| RoBERTa    | 56.35%   |

### Major Findings

✅ DistilBERT achieved the highest overall accuracy.

✅ Model compression did not significantly reduce performance.

✅ Transformer models outperformed most traditional baselines.

✅ Agreement scores remained relatively low despite good accuracy.

✅ Explainability methods frequently agreed on correct classifications but diverged on misclassifications.

✅ Accuracy alone is insufficient to measure trustworthiness and reliability.

---

## 💡 Research Contributions

### 1. Unified Transformer Evaluation

Compared BERT, RoBERTa, and DistilBERT under a single experimental framework.

### 2. Multi-Method Explainability

Integrated SHAP, LIME, and Attention Visualization within one pipeline.

### 3. Agreement-Based Evaluation

Introduced Cohen's Kappa and Fleiss' Kappa alongside traditional performance metrics.

### 4. Responsible AI Assessment

Combined explainability, fairness, and reliability evaluation.

### 5. Extensible Research Framework

Provides a foundation for future trustworthy AI and misinformation detection research.

---

## 📈 Visual Outputs

The project generates:

* Confusion Matrices
* ROC Curves
* SHAP Summary Plots
* SHAP Force Plots
* LIME Explanations
* BertViz Attention Maps

---

## 🛠️ Tech Stack

### Programming

* Python

### Libraries

* PyTorch
* Hugging Face Transformers
* Scikit-Learn
* SHAP
* LIME
* BertViz
* NumPy
* Pandas
* Matplotlib

### Environment

* Google Colab
* GPU Acceleration

---

## 🔬 Future Work

Potential directions for extending this research:

* Large Language Models (LLMs)
* Multilingual Fake News Detection
* Cross-Domain Misinformation Analysis
* Ensemble Transformer Architectures
* Graph-Based Detection Models
* More Robust Explainability Frameworks
* Advanced Agreement Evaluation Methods

---

## 🌟 Key Takeaway

> **High Accuracy ≠ High Trust**

A model can achieve strong predictive performance while still producing inconsistent explanations and low agreement with other models.

Building trustworthy AI requires more than optimizing accuracy—it requires transparency, fairness, explainability, and reliability.

---

## 👩‍💻 Author

**Sheetal Gupta**

AI Research | Data Science | Machine Learning | NLP | Explainable AI

📧 [sheetalgupta72951@gmail.com](mailto:sheetalgupta72951@gmail.com)

🔗 LinkedIn: [www.linkedin.com/in/sheetal-gupta-a26715216](http://www.linkedin.com/in/sheetal-gupta-a26715216)

💻 GitHub: github.com/sheetalguptaa

---

### ⭐ If you found this project interesting, consider giving it a star and sharing your feedback!
