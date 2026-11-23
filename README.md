
# Deep Learning-Based Fake Social Media Profile Detection
### Image Normalization, ResNet-50, and Metaheuristic Optimization

## Overview

This research project investigates image-based fake social media
profile detection using deep learning and image normalization
techniques.

The proposed approach uses a ResNet-50 convolutional neural
network to classify profile images into four categories:
Bots, Cyborgs, Real, and Verified.

The study explores how image preprocessing and normalization
strategies, together with metaheuristic hyperparameter
optimization, affect classification performance.

## Research Objectives

- Investigate image normalization techniques for profile-image
  classification.
- Develop a ResNet-50-based classification pipeline.
- Compare different preprocessing configurations.
- Explore metaheuristic optimization for model tuning.
- Evaluate classification performance across four classes.

## Methodology

### 1. Image Preprocessing
The study investigates techniques including:
- Min-Max Normalization
- Z-score Normalization
- Histogram Equalization
- Principal Component Analysis (PCA)
- Local Contrast Normalization

### 2. Deep Learning Model
- Architecture: ResNet-50
- Framework: PyTorch
- Approach: Transfer Learning
- Task: Four-class image classification

### 3. Hyperparameter Optimization
The research explores metaheuristic approaches including:
- Tug of War Optimization
- Hunger Games Search
- Shell Game Optimization

## Experimental Results

The thesis reports the following result for the
Shell Game Optimization + Local Contrast Normalization
configuration:

- Precision: 99.67%
- F1-score: 1.0000

These values are reported thesis results. Please consult
the thesis for the experimental setup and comparison
with other configurations.

## Repository Structure

The source code is available in the `code/` directory.

## Dataset and Model

- Dataset: [Dataset link]
- Model: [Model link]

## Reproducibility

Detailed installation instructions, dependency versions,
data preparation steps, and execution commands will be
provided after verification of the source code.

## Limitations

This work focuses on visual profile-image classification.
It does not establish account authenticity from images
alone, nor does it claim to analyse textual content,
social-network graphs, or live platform activity.

## Academic Reference

Master's thesis:
"Solution pour la détection des faux profils sur les
réseaux sociaux : normalisation des images"

Hassiba Ben Bouali University of Chlef, Algeria, 2025.

## Author

Ahmed J. M. Abuamer
GitHub: https://github.com/9ahmed163788-cyber

