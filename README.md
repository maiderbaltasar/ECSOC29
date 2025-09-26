# LIFE.PTML Model Development Targeting Calmodulin Pathway Proteins

**Authors**:  
Maider Baltasar Marchueta¹, Naia López¹, Sonia Arrasate¹, Matthew M. Montemore², Humberto González-Díaz¹˒³˒⁴*  

1. Department of Organic and Inorganic Chemistry, University of the Basque Country UPV/EHU, 48940, Leioa, Spain  
2. Department of Chemical and Biomolecular Engineering, Tulane University, 6823 St Charles Avenue, New Orleans, Louisiana 70118, United States  
3. Biofisika Institute, CSIC-UPV/EHU, 48940, Leioa, Spain  
4. IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Spain  

---

## 📖 Project Overview

This repository contains the implementation of **LIFE.PTML**, a methodology integrating:

- **Lifecycle (L)**  
- **Information Fusion (IF)**  
- **Encoding (E)**  
- **Perturbation Theory (PT)**  
- **Machine Learning (ML)**  

The goal is to develop predictive models of compound activity targeting **calmodulin (CaM) and related proteins**.

The dataset comprises **3,748 molecule–assay combinations**, combining chemical and protein descriptors. Several classifiers were tested (XGBoost, Gradient Boosting, Random Forest, etc.), with **XGBoost** achieving the best performance:

- **Test Accuracy**: 88.9%  
- **ROC AUC**: 0.959  

Feature importance analysis revealed contributions from both **drug- and protein-level descriptors**, confirming the robustness of the methodology.

---

## ⚙️ Environment & Requirements

This project was developed on **Kaggle Notebooks** with the following environment:

- **Python**: 3.11.13  
- **NumPy**: 1.26.4  
- **Pandas**: 2.2.3  
- **Matplotlib**: 3.7.2  
- **Seaborn**: 0.12.2  
- **Scikit-learn**: 1.2.2  
- **XGBoost**: 2.0.3  

All dependencies are listed in `requirements.txt`.  
To install them locally, run:

```bash
pip install -r requirements.txt
