---
title: "Characterization of the Autoencoder Radiation Anomaly Detection (ARAD) model"
collection: publications
#permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'In this work we demonstrate an in-depth analysis and characterization of the Autoencoder Radiation Anomaly Detection (ARAD) algorithm. ARAD is a deep convolutional autoencoder designed to detect anomalous radioactive signatures in gamma-ray spectra collected by NaI(Tl) detectors. '
date: 2022-05-01
venue: 'Engineering Applications of Artificial Intelligence'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'James M. Ghawaly Jr., Aaron Young, Andrew Nicholson, Brett Witherspoon, Nick Prins, Matthew Swinney, Cihangir Celik, Catherine D. Schuman, and Karan Pankaj Kumar Patel. 2023. Performance Optimization Study of the Neuromorphic Radiation Anomaly Detector. In International Conference on Neuromorphic Systems (ICONS ’23), August 1–3, 2023, Santa Fe, NM, USA. ACM, New York, NY, USA, 7 pages. https://doi.org/10.1145/3589737.3605980'
---

Abstract:

In this work we demonstrate an in-depth analysis and characterization of the Autoencoder Radiation Anomaly Detection (ARAD) algorithm. ARAD is a deep convolutional autoencoder designed to detect anomalous radioactive signatures in gamma-ray spectra collected by NaI(Tl) detectors. This model works by learning a dimensionally constrained representation of background gamma-ray spectra called the latent space. The latent space cannot fully describe anomalous components in new spectra, resulting in a decrease in spectral reconstruction accuracy that triggers an alarm. This paper demonstrates the model’s performance on a set of data collected outside of the High Flux Isotope Reactor and Radiochemical Engineering Development Center facilities at Oak Ridge National Laboratory. We also perform an evaluation of the model’s detection performance using a set of publicly available synthetic data representing a radiation detector moving throughout an urban city street. We demonstrate the algorithm’s ability to detect sources in locations with highly dynamic background count rates resulting from variations in naturally occurring radioactive materials and precipitation-induced radon washout, a challenge for many traditional radiation detection algorithms. We compare these results against those from another unsupervised radiation anomaly detection algorithm based on principal component analysis. ARAD achieved excellent performance on both datasets and proves the viability and efficacy of autoencoders for radiation anomaly detection.

Recommended citation:
Ghawaly Jr, J. M., Nicholson, A. D., Archer, D. E., Willis, M. J., Garishvili, I., Longmire, B., ... & Cook, M. T. (2022). Characterization of the Autoencoder Radiation Anomaly Detection (ARAD) model. Engineering Applications of Artificial Intelligence, 111, 104761.