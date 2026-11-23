# Experimental Results and Comparative Analysis

## 1. Overview

This document summarizes the experimental findings of the Master's research project:

**Deep Learning-Based Fake Social Media Profile Detection Using ResNet-50, Image Normalization, and Metaheuristic Optimization.**

The experiments investigate the influence of image normalization techniques and metaheuristic hyperparameter optimization on the classification performance of a ResNet-50 model.

The five metaheuristic algorithms were implemented and evaluated independently. Each algorithm represents a separate experimental approach, and its results are documented individually in the Master's thesis.

The results presented here are reported experimental findings from the thesis and should be interpreted within the scope of the dataset and experimental configurations used.

## 2. Image Normalization Experiments

Ten image normalization techniques were investigated:

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

The purpose of these experiments was to examine how different normalization strategies affect the classification performance of ResNet-50.

The thesis includes a comparative evaluation of these techniques, reporting accuracy measurements and a global evaluation score.

The complete normalization comparison is presented in the Master's thesis, Chapter 5, Table 5.1.

## 3. Independent Metaheuristic Optimization Experiments

Five metaheuristic algorithms were investigated separately for hyperparameter optimization.

### 3.1 Tug of War Optimization (TWO)

The Tug of War Optimization algorithm was implemented as an independent optimization experiment.

The thesis reports the following configuration among the evaluated results:

| Configuration | Reported Test Accuracy |
|---|---:|
| Histogram Equalization + TWO | 99.75% |

### 3.2 Hunger Games Search (HGS)

Hunger Games Search was evaluated independently as a metaheuristic optimization approach.

The thesis reports the following experimental result:

| Configuration | Reported Test Accuracy |
|---|---:|
| Histogram Equalization + HGS | 99.83% |

### 3.3 Kho-Kho Optimization (KKO)

The Kho-Kho Optimization algorithm was investigated through a separate experimental implementation.

The thesis reports the following configuration:

| Configuration | Reported Test Accuracy |
|---|---:|
| Histogram Equalization + KKO | 99.78% |

### 3.4 Golf Optimization Algorithm (GOA)

The Golf Optimization Algorithm was investigated as an independent hyperparameter optimization experiment.

Its experimental evaluation and corresponding results are documented separately in the Master's thesis.

### 3.5 Shell Game Optimization (SGO)

Shell Game Optimization was implemented and evaluated independently.

The thesis reports the following configuration:

| Configuration | Reported Test Accuracy |
|---|---:|
| Local Contrast Normalization + SGO | 99.67% |

## 4. Selected Experimental Results

The following table summarizes selected configurations reported in the Master's thesis.

| Normalization Technique | Optimization Algorithm | Test Accuracy |
|---|---|---:|
| Histogram Equalization | HGS | 99.83% |
| Histogram Equalization | KKO | 99.78% |
| Histogram Equalization | TWO | 99.75% |
| Local Contrast Normalization | SGO | 99.67% |

These values represent individual experimental configurations. They do not represent a single combined experiment or a universal performance value for the model.

The complete experimental analysis, including additional evaluation metrics, is available in the Master's thesis.

## 5. Evaluation Metrics

The experimental evaluation includes classification performance measures such as:

- Accuracy
- Precision
- Recall
- F1-score
- Test loss
- Confusion matrices
- Classification reports

The thesis provides detailed evaluation results for the individual experiments.

## 6. Interpretation and Scope

The results demonstrate the performance observed under the specific experimental conditions of this research.

The experiments focus on image-based classification of four profile categories:

- Bot
- Cyborg
- Real
- Verified

The study does not claim comprehensive social media account verification. It focuses on profile-image classification rather than behavioral patterns, textual analysis, social-network relationships, or real-time platform monitoring.

Comparisons between experimental configurations should take into account their respective normalization methods, optimization algorithms, and evaluation settings.

## 7. Full Research Documentation

**Thesis title:**

*Solution pour la détection des faux profils sur les réseaux sociaux : normalisation des images.*

**Degree:** Master's Degree in Computer Science – Pattern Recognition and Artificial Intelligence.

**Institution:** Hassiba Ben Bouali University of Chlef, Algeria.

**Year:** 2025.

**Research code:**  
https://github.com/9ahmed163788-cyber/FakeProfileDetection

