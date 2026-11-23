# Deep Learning-Based Fake Social Media Profile Detection
### Image Normalization and Metaheuristic Optimization Using ResNet-50

## Overview

This research project investigates image-based fake social media profile detection using deep learning, image normalization techniques, and metaheuristic optimization.

The proposed experimental framework employs a pretrained **ResNet-50** convolutional neural network to classify social media profile images into four categories:

- **Bot**
- **Cyborg**
- **Real**
- **Verified**

The study focuses on examining how different image normalization techniques affect classification performance and how metaheuristic optimization algorithms can be independently applied to optimize the model's hyperparameters.

Rather than combining all optimization algorithms into a single implementation, each metaheuristic algorithm is investigated through a separate experiment. Their individual results are documented and compared in the accompanying Master's thesis.

## Research Objectives

The main objectives of this project are:

1. Investigate the effectiveness of different image normalization techniques in deep learning-based image classification.
2. Evaluate the performance of ResNet-50 for distinguishing between four categories of social media profiles.
3. Explore metaheuristic optimization as an approach to hyperparameter tuning.
4. Implement and evaluate five metaheuristic algorithms independently.
5. Compare experimental outcomes to examine the impact of normalization and optimization strategies on classification performance.

## Dataset

The experiments use the **X Fake Profile Detection** image dataset.

- **Source:** [Hugging Face – X Fake Profile Detection](https://huggingface.co/datasets/drveronika/x_fake_profile_detection)
- **Total images:** 15,000
- **Training set:** 10,000 images
- **Validation set:** 1,000 images
- **Test set:** 4,000 images
- **Number of classes:** 4
- **Image dimensions:** 224 × 224 pixels
- **Image format:** RGB

The dataset contains profile images categorized as Bots, Cyborgs, Real, and Verified.

## Methodology

The research methodology consists of two main experimental stages.

### 1. Image Normalization

Ten image normalization techniques are investigated to study their influence on image representation and classification performance:

1. Min-Max Normalization
2. Z-Score Normalization
3. Mean Normalization
4. Decimal Scaling
5. Histogram Equalization
6. Principal Component Analysis (PCA)
7. Whitening
8. Batch Normalization
9. Local Contrast Normalization (LCN)
10. Color Normalization

The normalization experiments are conducted to evaluate how different preprocessing strategies influence the performance of the ResNet-50 model.

### 2. Metaheuristic Hyperparameter Optimization

Five metaheuristic optimization algorithms are implemented and evaluated independently:

| Algorithm | Abbreviation |
|---|---|
| Tug of War Optimization | TWO |
| Hunger Games Search | HGS |
| Kho-Kho Optimization | KKO |
| Golf Optimization Algorithm | GOA |
| Shell Game Optimization | SGO |

Each algorithm is treated as a separate experimental approach for hyperparameter optimization.

The resulting experiments are documented individually, allowing their performance to be examined and compared without confusing the implementation or results of one algorithm with another.

## Deep Learning Architecture

**ResNet-50** is used as the primary classification architecture.

The experimental implementation is based on:

- Transfer learning with pretrained ResNet-50 weights.
- Fine-tuning and a customized classification layer.
- Cross-entropy loss.
- AdamW optimizer.
- Learning-rate scheduling.
- Data augmentation.
- Early stopping.
- Classification performance evaluation.

The implementation uses Python and PyTorch.

## Experimental Results

The thesis reports high classification performance across several normalization and optimization configurations.

Some of the reported results include:

| Normalization | Optimization Algorithm | Reported Test Accuracy |
|---|---|---:|
| Histogram Equalization | Hunger Games Search (HGS) | 99.83% |
| Histogram Equalization | Kho-Kho Optimization (KKO) | 99.78% |
| Histogram Equalization | Tug of War Optimization (TWO) | 99.75% |
| Local Contrast Normalization (LCN) | Shell Game Optimization (SGO) | 99.67% |

These values are reported experimental results from the Master's thesis. They represent individual configurations and should not be interpreted as a single combined experiment.

The thesis also presents additional experimental comparisons, classification reports, and evaluation results.

## Technologies and Tools

- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Model Architecture:** ResNet-50
- **Image Processing:** OpenCV, NumPy
- **Data Analysis:** Pandas
- **Visualization and Evaluation:** Matplotlib, Scikit-learn
- **Development Environment:** Jupyter Notebook

## Repository Contents

This repository contains the experimental notebooks and supporting materials associated with the research.

The notebooks document the data preparation, image normalization, model training, and optimization experiments.

Each optimization algorithm is associated with its own experimental implementation and corresponding results, as documented in the thesis.

## Research Thesis

**Title:**  
*Solution pour la détection des faux profils sur les réseaux sociaux : normalisation des images.*

**Degree:** Master's Degree in Computer Science – Pattern Recognition and Artificial Intelligence.

**Institution:** Hassiba Ben Bouali University of Chlef, Algeria.

**Year:** 2025.

## Research Scope and Limitations

This research focuses on image-based classification of social media profile categories.

The experimental framework evaluates profile images rather than performing comprehensive account-level verification. It does not claim to detect fake accounts through behavioral analysis, textual content, social-network relationships, or real-time platform monitoring.

The reported performance should therefore be understood within the scope of the dataset, experimental settings, and image-based classification task.

## Author

**AHMED J M ABUAMER**

Master's Graduate in Computer Science – Pattern Recognition and Artificial Intelligence.

- **GitHub:** [9ahmed163788-cyber](https://github.com/9ahmed163788-cyber)
- **Research Repository:** [FakeProfileDetection](https://github.com/9ahmed163788-cyber/FakeProfileDetection)

---

*This repository accompanies a Master's research project on deep learning-based fake social media profile image detection, focusing on image normalization and independent metaheuristic optimization experiments.*
