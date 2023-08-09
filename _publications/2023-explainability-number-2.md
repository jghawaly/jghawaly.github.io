---
title: "Explaining machine-learning models for gamma-ray detection and identification"
collection: publications
#permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This work evaluates a variety of neural network explainability approaches for explaining deep learning models trained to perform gamma-ray spectroscopy.'
date: 2023-06-20
venue: 'PLoS ONE'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'James M. Ghawaly Jr., Aaron Young, Andrew Nicholson, Brett Witherspoon, Nick Prins, Matthew Swinney, Cihangir Celik, Catherine D. Schuman, and Karan Pankaj Kumar Patel. 2023. Performance Optimization Study of the Neuromorphic Radiation Anomaly Detector. In International Conference on Neuromorphic Systems (ICONS ’23), August 1–3, 2023, Santa Fe, NM, USA. ACM, New York, NY, USA, 7 pages. https://doi.org/10.1145/3589737.3605980'
---

Abstract:

As more complex predictive models are used for gamma-ray spectral analysis, methods are needed to probe and understand their predictions and behavior. Recent work has begun to bring the latest techniques from the field of Explainable Artificial Intelligence (XAI) into the applications of gamma-ray spectroscopy, including the introduction of gradient-based methods like saliency mapping and Gradient-weighted Class Activation Mapping (Grad-CAM), and black box methods like Local Interpretable Model-agnostic Explanations (LIME) and SHapley Additive exPlanations (SHAP). In addition, new sources of synthetic radiological data are becoming available, and these new data sets present opportunities to train models using more data than ever before. In this work, we use a neural network model trained on synthetic NaI(Tl) urban search data to compare some of these explanation methods and identify modifications that need to be applied to adapt the methods to gamma-ray spectral data. We find that the black box methods LIME and SHAP are especially accurate in their results, and recommend SHAP since it requires little hyperparameter tuning. We also propose and demonstrate a technique for generating counterfactual explanations using orthogonal projections of LIME and SHAP explanations.

Recommended citation:
Bandstra MS, Curtis JC, Ghawaly JM Jr, Jones AC, Joshi THY (2023) Explaining machine-learning models for gamma-ray detection and identification. PLoS ONE 18(6): e0286829. https://doi.org/10.1371/journal.pone.0286829