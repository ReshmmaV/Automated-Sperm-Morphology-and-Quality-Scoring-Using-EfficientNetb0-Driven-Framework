# Automated Sperm Morphology and Quality Scoring Using Explainable EfficientNet-B0 Driven Framework

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Publication](https://img.shields.io/badge/Publication-Springer-green)

## Overview

This repository presents an AI-powered framework for automated sperm morphology classification and sperm quality scoring using EfficientNet-B0 and Explainable AI techniques.

The framework classifies:
- Normal sperm
- Abnormal sperm
- Non-sperm cells

using the Sperm Morphology Image Dataset (SMIDS).

The project also integrates:
- Integrated Gradients for explainability
- Sperm Quality Score (SQS) generation
- Transfer learning-based morphology analysis

---

## Abstract

Sperm morphology provides vital insights into functional competence, a key factor in male fertility assessment. Standard manual evaluation is often slow, time-consuming and observer-dependent, making it prone to human error.

This study develops an AI-powered framework for automated sperm morphology evaluation using a fine-tuned EfficientNet-B0 model trained on the Sperm Morphology Image Dataset (SMIDS). The framework classifies normal sperm, abnormal sperm and non-sperm images while incorporating Explainable AI using Integrated Gradients to highlight important predictive regions.

The proposed model achieved an accuracy of **84.75%**, outperforming the DenseNet+CBAM architecture. Additionally, a novel Sperm Quality Score (SQS) was introduced to convert model predictions into an interpretable fertility assessment metric.

This framework paves the way for affordable, scalable and accessible AI-assisted male fertility assessment systems.

---

## Publication

Published in Springer Nature.

### Citation

Vijayakumar, R., Venkatesan, N. (2026).  
**Automated Sperm Morphology and Quality Scoring Using Explainable EfficientNet-B0 Driven Framework.**

In:
Karsh, R.K., Murugan, R., Laskar, R.H., Schuller, B.W. (eds)

*Advances on Signal Processing and Computer Vision.*  
SIPCOV 2025. Communications in Computer and Information Science, vol 2848. Springer, Cham.

DOI:
https://doi.org/10.1007/978-3-032-15809-3_11

Published:
02 February 2026

---

## Features

- EfficientNet-B0 based sperm morphology classification
- Explainable AI using Integrated Gradients
- Sperm Quality Score (SQS)
- Transfer learning framework
- Comparative evaluation with DenseNet+CBAM
- Automated fertility assessment pipeline

---

## Model Performance

| Model | Accuracy |
|------|------|
| EfficientNet-B0 | 84.75% |
| DenseNet + CBAM | Lower than proposed model |

---

## Repository Contents

| File | Description |
|------|------|
| efficientnetb0+xai+sqs.ipynb | Main proposed framework |
| DenseNet+CBAM.ipynb | Comparative baseline architecture |

---

## Technologies Used

- Python
- TensorFlow / Keras
- EfficientNet-B0
- DenseNet
- CBAM
- Integrated Gradients
- Google Colab

---

## Dataset

Dataset used:
- Sperm Morphology Image Dataset (SMIDS)

Note:
Dataset may be subject to licensing/privacy restrictions and is therefore not uploaded directly in this repository.

---

## Usage

Clone the repository:

```bash
git clone https://github.com/ReshmmaV/Automated-Sperm-Morphology-and-Quality-Scoring-Using-EfficientNetb0-Driven-Framework.git
```

Open notebooks using:
- Google Colab
- Jupyter Notebook

---

## Future Scope

- Real-time sperm analysis systems
- Clinical fertility assessment tools
- Mobile-assisted diagnostics
- Multi-class morphology grading
- Edge AI deployment for laboratory automation

---

## Authors

- Reshmma Vijayakumar
- Nandakumar Venkatesan

---

## License

This project is intended for academic and research purposes.
