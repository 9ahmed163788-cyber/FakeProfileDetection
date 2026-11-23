# Deep Learning-Based Fake Social Media Profile Detection

### Image Normalization, ResNet-50, and Metaheuristic Optimization

## Project Overview

This project presents a deep learning-based approach to image-based fake social media profile detection. It investigates the impact of image preprocessing, normalization techniques, and metaheuristic optimization on the classification performance of convolutional neural networks.

The proposed framework uses a ResNet-50 architecture, implemented in PyTorch, to classify profile images into four categories:

- **Bots**
- **Cyborgs**
- **Real**
- **Verified**

The main focus is to examine how different image normalization strategies influence feature representation and classification performance, and how metaheuristic optimization methods can contribute to model configuration and performance improvement.

## Research Objectives

The main objectives of this research are:

- Investigate the effect of image normalization and preprocessing techniques on profile-image classification.
- Develop a deep learning classification pipeline based on ResNet-50.
- Compare different preprocessing and normalization configurations.
- Explore metaheuristic optimization methods for model tuning.
- Evaluate classification performance across four profile categories.
- Analyse the relationship between image representation, preprocessing strategies, and classification results.

## Methodology

### 1. Image Preprocessing and Normalization

The research investigates several image-processing and normalization techniques:

- **Min-Max Normalization:** Rescaling image values to a predefined range.
- **Z-score Normalization:** Standardizing values based on their mean and standard deviation.
- **Histogram Equalization:** Improving image contrast through intensity distribution adjustment.
- **Principal Component Analysis (PCA):** Exploring dimensionality reduction and feature representation.
- **Local Contrast Normalization (LCN):** Enhancing local image contrast and normalization.

These techniques are investigated to assess their influence on the input representation and subsequent classification performance.

### 2. Deep Learning Architecture

The classification framework is based on the following configuration:

| Component | Description |
|---|---|
| Model architecture | ResNet-50 |
| Framework | PyTorch |
| Learning approach | Transfer Learning |
| Input data | Social media profile images |
| Classification task | Four-class image classification |
| Output categories | Bots, Cyborgs, Real, Verified |

ResNet-50 is used as the main convolutional neural network architecture to extract visual features and perform profile-image classification.

### 3. Metaheuristic Optimization

The research explores the use of metaheuristic optimization approaches in the model-tuning process.

The investigated algorithms include:

- **Tug of War Optimization (TWO)**
- **Hunger Games Search (HGS)**
- **Shell Game Optimization (SGO)**

Different optimization and preprocessing configurations are examined to investigate their impact on the classification results.

## Experimental Results

The Master's thesis reports the following results for the configuration combining **Shell Game Optimization (SGO)** with **Local Contrast Normalization (LCN)**:

| Evaluation Metric | Reported Result |
|---|---:|
| Precision | 99.67% |
| F1-score | 1.0000 |

These values are reported from the thesis experiments and should be interpreted in the context of the experimental configuration and evaluation procedure described in the original research.

The results are presented as experimental findings rather than a general guarantee of performance on other datasets or real-world social media platforms.

## Repository Structure

The project source code is available in the following directory:

```text
FakeProfileDetection/
│
├── code/
│   └── Source code and implementation
│
├── README.md
└── .gitignore
```

The repository structure may be extended as additional documentation, experimental results, and reproducibility materials are organised.

## Technologies and Tools

The project is based on the following technologies and research tools:

- **Python** – Main programming language.
- **PyTorch** – Deep learning model implementation and training.
- **ResNet-50** – Convolutional neural network architecture.
- **Image Processing** – Image preprocessing and normalization.
- **Metaheuristic Optimization** – Model optimization experiments.
- **Git and GitHub** – Source code management and project documentation.

## Dataset and Model Resources

The dataset and model resources associated with this research are referenced in the original project materials.

For further details about the dataset, experimental configurations, and model implementation, please consult the source code and the corresponding Master's thesis.

## Reproducibility

The repository contains the implementation associated with the research project.

Installation instructions, dependency versions, dataset preparation procedures, and execution commands should be verified against the source code before being documented as reproducible steps.

The experimental results should be considered alongside the implementation details and evaluation methodology described in the thesis.

## Research Limitations

This project focuses specifically on the visual analysis of social media profile images.

It does not claim to establish the authenticity of an entire social media account based on its profile image alone. In particular, the current research scope does not include:

- Natural Language Processing (NLP) of profile descriptions or posts.
- Social-network graph analysis.
- Behavioural analysis of account activity.
- Real-time monitoring of social media platforms.
- Multimodal verification combining images, text, and account behaviour.

These aspects represent possible directions for further research beyond the scope of this work.

## Academic Reference

**Master's Thesis**

*Solution pour la détection des faux profils sur les réseaux sociaux : normalisation des images*

Master's Degree in Computer Science – Pattern Recognition and Artificial Intelligence  
Hassiba Ben Bouali University of Chlef  
Algeria, 2025

## Author

**Ahmed J. M. Abuamer**

GitHub: https://github.com/9ahmed163788-cyber

---

*This repository accompanies an academic Master's research project in deep learning, computer vision, image normalization, and metaheuristic optimization.*
