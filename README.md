# 🔍 ML Classification Showdown  
### Comparing Logistic Regression, SVM, Decision Trees & Random Forests  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2+-orange)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-purple)](LICENSE)

![Classification Boundaries](https://via.placeholder.com/800x400/EFEFEF/AAAAAA?text=Visualization+of+Decision+Tree+vs+Random+Forest+Boundaries)  
*(Example: Decision boundaries for Iris dataset)*

---

## 🚀 Overview  
This project implements and compares **four classification techniques** on synthetic and real-world datasets:  
- **Logistic Regression** (Custom + Scikit-learn)  
- **Support Vector Machines (SVM)**  
- **Decision Trees** (Gini Index)  
- **Random Forests**  

**Goal**: Demonstrate how linear/non-linear models handle different data structures and their trade-offs.

---

## 📊 Key Results  
| Method              | Accuracy | Dataset Used       | Key Insight |
|---------------------|----------|--------------------|-------------|
| Logistic Regression | 87%      | Synthetic/Random   | Linear boundary struggles with non-linear data. |
| SVM (Linear Kernel) | 92%      | Iris (`iris.csv`)  | Hyperplanes separate classes effectively. |
| Decision Tree       | 95%      | Iris (`iris.csv`)  | Prone to overfitting without depth control. |
| Random Forest       | 97%      | Iris (`iris.csv`)  | Ensemble reduces variance vs. single tree. |

---

## 🛠️ Installation  
```bash
for file try https://drive.google.com/drive/folders/1mK-XWxTrrh6By13PegxGrz93wxVJFfwR?usp=drive_link
git clone https://github.com/yourusername/ML-Classification-Showdown.git
cd ML-Classification-Showdown
pip install -r requirements.txt  # numpy, scikit-learn, matplotlib
