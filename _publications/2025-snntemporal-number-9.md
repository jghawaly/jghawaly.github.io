---
title: "Exploring Spiking Neural Networks for Binary Classification in Multivariate Time Series at the Edge"
collection: publications
permalink: /publication/2025-snntemporal-number-9
excerpt: "We present a general framework for training spiking neural networks (SNNs) to perform binary classification on multivariate time series, with a focus on step-wise prediction and high precision at low false alarm rates."
date: 2025-07-02
venue: 'IJCNN'
# paperurl: ''
citation: 'Ghawaly, J., Nicholson, A., Schuman, C., Diez, D., Young, A., & Witherspoon, B. (2025). Exploring Spiking Neural Networks for Binary Classification in Multivariate Time Series at the Edge. 2025 International Joint Conference on Neural Networks (IJCNN). In press.'
---

Abstract:

We present a general framework for training spiking neural networks (SNNs) to perform binary classification on multivariate time series, with a focus on step-wise prediction and high precision at low false alarm rates. The approach uses the Evolutionary Optimization of Neuromorphic Systems (EONS) algorithm to evolve sparse, stateful SNNs by jointly optimizing their architectures and parameters. Inputs are encoded into spike trains, and predictions are made by thresholding a single output neuron’s spike counts. We also incorporate simple voting ensemble methods to improve performance and robustness. To evaluate the framework, we apply it with application-specific optimizations to the task of detecting low signal-to-noise ratio radioactive sources in gamma-ray spectral data. The resulting SNNs, with as few as 49 neurons and 66 synapses, achieve a 51.8% true positive rate (TPR) at a false alarm rate of 1/hr, outperforming PCA (42.7%) and deep learning (49.8%) baselines. A three-model any-vote ensemble increases TPR to 67.1% at the same false alarm rate. Hardware deployment on the μCaspian neuromorphic platform demonstrates 2 mW power consumption and 20.2 ms inference latency. We also demonstrate generalizability by applying the same framework, without domain-specific modification, to seizure detection\ in EEG recordings. An ensemble achieves 95% TPR with a 16% false positive rate, comparable to recent deep learning approaches with significant reduction in parameter count. Index Terms—neuromorphic computing, spiking neural

Recommended citation:
Ghawaly, J., Nicholson, A., Schuman, C., Diez, D., Young, A., & Witherspoon, B. (2025). Exploring Spiking Neural Networks for Binary Classification in Multivariate Time Series at the Edge. 2025 International Joint Conference on Neural Networks (IJCNN). In press.
