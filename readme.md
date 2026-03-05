# Investigating Dementia Patterns by Machine Learning and Graph-Based Marker Analysis for Multiclass Dementia Diagnosis

## Overview
This repository contains the official implementation and experimental framework for our study on multiclass dementia diagnosis using machine learning and graph-based marker analysis. The proposed framework investigates dementia patterns by integrating **machine learning classification**, **feature importance analysis**, **interpretable decision rules**, and **graph-based marker relationship modeling**.


<p align="center">
  <!-- Replace with your framework image -->
  <img src="figs/overview.png" alt="Proposed Framework" width="1000"/>
</p>

---

## Major Contributions

> **Comprehensive Machine Learning Benchmarking**  
Multiple machine learning algorithms were evaluated to determine the most effective model for dementia prediction.

> **Feature Importance and Marker Ranking**  
Key dementia-related markers such as **MMSE, nWBV, Age, SES, and Education** were analyzed to determine their predictive importance.

> **Interpretable Decision Tree Rule Extraction**  
Decision tree models were used to extract interpretable rules that highlight clinically meaningful diagnostic patterns.

> **Graph-Based Marker Relationship Analysis**  
Graph-based analysis was used to explore structural relationships among clinical variables and reveal interaction patterns between dementia markers.

## Dataset

This study utilizes the **Open Access Series of Imaging Studies (OASIS-2)** dataset, which contains clinical and demographic information related Alzheimer’s disease. Dataset citation is as follows:

```bibtex
@article{marcus2010open,
  title={Open access series of imaging studies: longitudinal MRI data in nondemented and demented older adults},
  author={Marcus, Daniel S and Fotenos, Anthony F and Csernansky, John G and Morris, John C and Buckner, Randy L},
  journal={Journal of cognitive neuroscience},
  volume={22},
  number={12},
  pages={2677--2684},
  year={2010},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```
Download the data with:
```
wget https://sites.wustl.edu/oasisbrains/files/2024/03/oasis_longitudinal_demographics-8d83e569fa2e2d30.xlsx
```

---

## Evaluated Machine Learning Models

We evaluated the following machine learning algorithms:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naïve Bayes  
- Gradient Boosting  
- AdaBoost  
- Extra Trees  
- XGBoost

---

## Graph-Based Marker Analysis

To better understand the relationships between dementia-related features, we constructed **feature interaction graphs**.

Graph analysis includes:
- Betweenness Centrality  
- Eigenvector Centrality  
- Correlation-based feature networks  

---

## Required Package Versions
```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
xgboost>=1.5.0
imbalanced-learn>=0.8.0
matplotlib>=3.4.0
tqdm>=4.62.0
graphviz>=0.16
boruta>=0.3
```
complete installation setup will be updated soon.

## Citation
Will be updated soon.