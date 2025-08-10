# ML Healthcare & Music Analytics

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Paper-00CCBB.svg)](https://www.researchgate.net/publication/394425330_Integration_of_Unsupervised_Learning_Techniques_with_Neural_Network_Classification_A_Comparative_Study_on_Healthcare_and_Music_Analytics)

Cross-domain machine learning study achieving 99.94% accuracy in music popularity prediction and advanced PCOS diagnosis through integrated unsupervised learning techniques.

## Key Results

| Dataset | Best Model | Accuracy | Method |
|---------|------------|----------|---------|
| PCOS Healthcare | PCA + K-Means | 100% | Cluster-enhanced features |
| Spotify Music | Cluster ID | 99.94% | Unsupervised clustering |

## Overview

This repository contains the complete implementation of a comparative machine learning study that bridges healthcare diagnostics and music analytics using advanced unsupervised learning techniques.

### Research Highlights
- Novel cross-domain approach applying identical ML pipelines to vastly different data types
- Integrated unsupervised learning combining PCA, ICA, K-Means, and GMM for feature enhancement
- Statistical validation with comprehensive model comparison and null hypothesis testing
- Real-world applications in women's health (PCOS diagnosis) and music industry analytics

## Repository Structure

```
├── pcos.ipynb           # PCOS infertility prediction analysis
├── spotify.ipynb        # Spotify music popularity classification  
└── data/
    ├── PCOS_infertility.csv     # Healthcare dataset (541 patients, 20 features)
    └── spotifysongs24.csv       # Music dataset (17,000+ tracks, 15 features)
```

## Quick Start

### Prerequisites
```bash
# Standard ML libraries (no special installations needed!)
pandas
numpy
scikit-learn
matplotlib
seaborn
```

### Run the Analysis
```bash
# Clone the repository
git clone https://github.com/yourusername/ML-Healthcare-Music-Analytics.git

# Open in Jupyter Notebook or VSCode
jupyter notebook pcos.ipynb
jupyter notebook spotify.ipynb
```

**No internet required** - all datasets included!

## Machine Learning Pipeline

### Unsupervised Techniques Applied:
- **PCA** - Dimensionality reduction (captured 71% variance in 2 components)
- **ICA** - Independent component analysis for non-Gaussian structures  
- **K-Means** - Clustering with optimal k selection via elbow method
- **GMM** - Probabilistic clustering with Gaussian mixture models

### Supervised Classification:
- **MLP Neural Networks** - Multi-layer perceptron for final classification
- **Comprehensive Evaluation** - Accuracy, F1-score, confusion matrices
- **Statistical Testing** - McNemar's test for model comparison validation

## Healthcare Applications (PCOS Dataset)

**Clinical Impact:** Early detection and diagnosis support for Polycystic Ovary Syndrome affecting millions of women worldwide.

**Key Features Analyzed:**
- Hormone levels (beta-HCG, insulin)
- Metabolic indicators (BMI, glucose)
- Reproductive health markers
- Lifestyle factors

## Music Industry Applications (Spotify Dataset)

**Business Impact:** Predictive modeling for track popularity across streaming platforms and social media.

**Key Features Analyzed:**
- Streaming metrics (Spotify, YouTube, TikTok)
- Audio characteristics
- Playlist performance
- Social media virality indicators

## Performance Metrics

### PCOS Classification Results:
- **Original Features:** 100% accuracy
- **PCA Features:** 99.96% accuracy  
- **ICA Features:** 99.97% accuracy
- **Cluster + PCA:** 100% accuracy

### Spotify Classification Results:
- **Original Features:** 99.68% accuracy
- **PCA Features:** 99.73% accuracy
- **Cluster ID Only:** 98.45% accuracy
- **Cluster + PCA:** 99.49% accuracy

## Research Paper

**Full Research Publication:** [Integration of Unsupervised Learning Techniques with Neural Network Classification](https://www.researchgate.net/publication/394425330_Integration_of_Unsupervised_Learning_Techniques_with_Neural_Network_Classification_A_Comparative_Study_on_Healthcare_and_Music_Analytics)

*Published on ResearchGate - Complete methodology, statistical analysis, and detailed results.*

## Technical Implementation

### Data Preprocessing Pipeline:
1. **Missing Value Imputation** - Median strategy for numerical features
2. **Feature Standardization** - Zero mean, unit variance scaling
3. **Categorical Encoding** - Label encoding for binary variables
4. **Class Balance Handling** - SMOTE for minority class enhancement

### Model Validation:
- **Train-Test Split** - 70/30 ratio for robust evaluation
- **Cross-Validation** - K-fold validation for stability testing
- **Statistical Testing** - Null hypothesis validation with t-tests
- **Performance Metrics** - Accuracy, precision, recall, F1-score

## Connect & Collaborate

**Author:** Mudra Pandya  
**Institution:** Northeastern University, College of Engineering  
**Email:** pandya.mu@northeastern.edu  

**Research Interests:** Machine Learning, Healthcare Analytics, Music Information Retrieval, Pattern Recognition

---

## Why This Research Matters

This study demonstrates that the same machine learning techniques can be effectively applied across completely different domains - from healthcare diagnostics to entertainment analytics. The integrated approach of combining unsupervised feature engineering with supervised classification provides a robust framework for tackling diverse real-world problems.

**Impact Areas:**
- Healthcare: Supporting clinical decision-making for reproductive health
- Music Industry: Enabling data-driven content strategy and recommendation systems
- ML Research: Advancing cross-domain transfer learning methodologies

---

*If this research helps your work, please consider starring the repository and citing our ResearchGate publication.*
