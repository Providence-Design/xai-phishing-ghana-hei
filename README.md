# GhanaPhish-XAI: GH-XGBoost for Ghana-Contextualised Phishing Detection

**Ghana-Contextualised Phishing Threat Indicators Integrated into 
Explainable Gradient Boosting for Field-Validated Detection in 
Higher Education**

MSc Thesis Project | Cybersecurity and Digital Forensics | 
Kwame Nkrumah University of Science and Technology (KNUST), Ghana

**Author:** Providence Annor Asemah (Student ID: 22544709)  
**Supervisor:** Dr. Eric Opoku Osei, Department of Computer Science, KNUST  
**Year:** 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21634130.svg)](https://doi.org/10.5281/zenodo.21634130)

---

## Overview

This study engineers GH-XGBoost — a Ghana-contextualised phishing 
detection model — by fabricating 15 Context-Aware Ghanaian Phishing 
Indicators (CGPI) and integrating them into a baseline XGBoost 
classifier. The model is trained on the Hannousse and Yahiouche (2021) 
Web Phishing Detection Dataset and validated on 200 real phishing URLs 
submitted by Ghanaian university students via primary field survey.

---

## Three Contributions

1. **CGPI Taxonomy** — 15 Ghana-specific URL features across three 
   categories: university ecosystem, digital payment context, and 
   student-targeted phishing language. Deposited on Zenodo: 
   https://doi.org/10.5281/zenodo.21634130

2. **GH-XGBoost** — XGBoost augmented with CGPI features, achieving 
   statistically significant improvement over baseline 
   (AUC-ROC: 0.9656 vs 0.9641, Wilcoxon p=0.0371, Cohen's d=0.83)

3. **SHAP Explainability** — Feature-level explanations identifying 
   Ghana-specific phishing indicators, translated into cybersecurity 
   awareness recommendations for Ghanaian university students

---

## Key Results

| Model | Features | AUC-ROC | FNR | Wilcoxon p |
|---|---|---|---|---|
| Baseline XGBoost | 50 | 0.9641 ± 0.0062 | 9.06% | — |
| GH-XGBoost | 65 | 0.9656 ± 0.0052 | 8.67% | 0.0371 |

**Field Validation:** 193/200 Ghana student-submitted phishing URLs 
correctly detected (96.5% detection rate)

---

## Dataset

| Dataset | Role | Size | Source |
|---|---|---|---|
| Web Phishing Detection Dataset | Training | 9,468 URLs | Hannousse & Yahiouche (2021) |
| Ghana Student Survey | Field Validation | 200 URLs | Primary field data |

---

## Repository Structure
