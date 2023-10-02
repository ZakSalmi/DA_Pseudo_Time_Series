# Data Augmentation for Pseudo-Time Series Using Generative Adversarial Networks

**Authors:** Zakaria Salmi and José Luis Seixas Junior
**Affiliation:** ELTE – Eötvös Loránd University, Faculty of Informatics, Budapest, Hungary
**Date:** [Insert publication date]

## Abstract

This repository contains the code and materials for the research paper titled "Data Augmentation for Pseudo-Time Series Using Generative Adversarial Networks." In this paper, we propose a novel approach for generating synthetic pseudo-time series data using a Generative Adversarial Network (GAN) architecture based on Long Short-Term Memory (LSTM).

## Overview

- **Authors**: Zakaria Salmi and José Luis Seixas Junior
- **Affiliation**: ELTE – Eötvös Loránd University, Faculty of Informatics, Budapest, Hungary
- **Date**: 22/09/2023

## Abstract

Data augmentation techniques have been developed to address the challenge of acquiring large and diverse datasets for training machine learning models. In this paper, the focus is on time series data and proposing a Generative Adversarial Network (GAN) architecture based on Long Short-Term Memory (LSTM) for generating synthetic pseudo-time series data. The dataset is preprocessed by normalizing the series lengths and then designing the LSTM-GAN architecture, which consists of a generator network and a discriminator network. The generator network uses an LSTM layer to generate synthetic time series data, while the discriminator network distinguishes between real and synthetic data. LSTM-GAN is trained using an adversarial approach and updates the network parameters iteratively. To evaluate the quality of the generated data, the original and synthetic data are compared using metrics such as silhouette score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE). Our results show that the LSTM-GAN is capable of generating synthetic time series data that closely resembles the real data, as evidenced by similar silhouette score and low MSE and RMSE values. This work contributes to the field of data augmentation for time series data and demonstrates the effectiveness of GANs in generating realistic and complex time series data.

## Citation

If you find this research paper useful or reference it in your work, please cite it using the following BibTeX entry:
```BibTeX
@article{salmi_data_augmentation_year,
  title={Data Augmentation for Pseudo-Time Series Using Generative Adversarial Networks},
  author={Zakaria Salmi and José Luis Seixas Junior},
  journal={ITAT},
  year={2023}
}
```

Contact
For any inquiries or questions regarding this research paper or the code, please feel free to contact the authors:

**Zakaria Salmi**: Zakariaprofes@gmail.com

**José Luis Seixas Junior**: jlseixasjr@inf.elte.hu

We welcome any feedback, suggestions, or collaborations related to this work.

