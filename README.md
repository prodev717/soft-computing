# Stress Prediction using Hybrid Soft Computing

This project presents a hybrid soft computing framework for predicting student stress levels by integrating Artificial Neural Networks (ANN), Genetic Algorithms (GA), and Fuzzy Logic Inference Systems (FIS). The work focuses on balancing predictive accuracy, feature efficiency, and model interpretability.

## Overview

Stress among university students is a critical issue affecting academic performance and well-being. Traditional assessment methods rely on static questionnaires and lack scalability. This project addresses the problem by developing a data-driven predictive system using machine learning and soft computing techniques.

The proposed framework follows a multi-stage pipeline:

* A baseline ANN model trained on the full feature set
* Feature selection using a Genetic Algorithm to reduce dimensionality
* A refined ANN trained on selected features
* A Fuzzy Logic system for interpretable decision-making

The dataset consists of survey responses from 571 students, including DASS-21 stress indicators, personality traits (TIPI), and academic/environmental factors .

## Key Contributions

* Development of a hybrid ANN + GA + Fuzzy Logic pipeline for stress prediction
* Reduction of feature space from 28 to 5 using Genetic Algorithm
* Preservation of high accuracy with significantly fewer features
* Design of an interpretable rule-based Fuzzy Inference System
* Comparative analysis of accuracy vs interpretability trade-offs

## Model Summary

| Model              | Accuracy | Features | Interpretability |
| ------------------ | -------- | -------- | ---------------- |
| Baseline ANN       | 96.43%   | 28       | Low              |
| GA-Optimized ANN   | 90.18%   | 5        | Medium           |
| Fuzzy Logic System | 83.04%   | 3        | High             |

The results demonstrate that high predictive performance can be achieved while improving model transparency and reducing complexity .

## Methodology

The system is designed as a four-stage pipeline:

1. Data preprocessing and feature engineering
2. Baseline ANN model training
3. Genetic Algorithm-based feature selection
4. Fuzzy Logic system for interpretable predictions

The pipeline integrates both data-driven learning and human-understandable reasoning, as illustrated in the methodology diagram (see report).

## Dataset

The dataset includes:

* DASS-21 stress-related questionnaire responses
* TIPI personality traits
* Demographic and academic factors

A binary stress label is derived using clustering-based thresholding on stress scores .

## Results

* High accuracy achieved with full feature ANN model
* Significant dimensionality reduction with minimal accuracy loss using GA
* Fully interpretable fuzzy system with rule-based reasoning

The study highlights the trade-off between accuracy and interpretability and demonstrates that both can coexist in a hybrid system.

## Future Work

* Cross-cultural dataset validation
* Integration of physiological or behavioral data
* Adaptive neuro-fuzzy systems (ANFIS)
* Comparison with explainable AI methods such as SHAP and LIME

## License

This project is intended for academic and research purposes.
