# Research Notebooks

This directory contains the Jupyter Notebooks associated with the Master's research project **Deep Learning-Based Fake Social Media Profile Detection**.

The notebooks document the image preprocessing, deep learning training, and metaheuristic optimization experiments conducted for classifying social media profile images into four categories: **Bot, Cyborg, Real, and Verified**.

## 1. Notebook Overview

| Notebook | Description |
|---|---|
| [`notebook 1 (normalization).ipynb`](./notebook%201%20%28normalization%29.ipynb) | Image preprocessing using Min-Max normalization, followed by ResNet-50 training and evaluation. |
| [`notebook 2 (metaheuristics).ipynb`](./notebook%202%20%28metaheuristics%29.ipynb) | Metaheuristic optimization experiments associated with the research project. |
| [`code3.ipynb`](./code3.ipynb) | An implementation of Shell Game Optimization (SGO) for hyperparameter optimization, followed by model training and evaluation. |

## 2. Experimental Workflow

The notebooks cover the following main stages:

1. **Dataset preparation:** Loading and organizing profile images into training, validation, and test sets.
2. **Image preprocessing:** Applying image normalization before model training.
3. **Deep learning model:** Using ResNet-50 for four-class image classification.
4. **Hyperparameter optimization:** Exploring metaheuristic optimization for selecting model training parameters.
5. **Model evaluation:** Assessing performance using accuracy, loss, classification reports, and confusion matrices.

## 3. Dataset

The experiments use the `x_fake_profile_detection` dataset.

The dataset split documented in the notebooks contains:

| Split | Number of Images |
|---|---:|
| Training | 10,000 |
| Validation | 1,000 |
| Testing | 4,000 |
| **Total** | **15,000** |

The four classification categories are:

- Bot
- Cyborg
- Real
- Verified

The dataset must be obtained separately and placed in the appropriate directory before running the notebooks.

## 4. Implementation Environment

The notebooks were developed using Python and PyTorch, with a Kaggle-based execution environment.

They use machine-learning and image-processing libraries for data loading, preprocessing, model training, optimization, and evaluation.

**Environment note:** Some notebook cells contain Kaggle-specific input and output paths, such as `/kaggle/input/` and `/kaggle/working/`. These paths may need to be adjusted when running the notebooks in another environment.

## 5. Reported Execution Output

The recorded output in `code3.ipynb` includes:

- Best optimization score: **99.40%**.
- Final test accuracy: **98.05%**.
- Final test loss: **0.0785**.

The optimization score and final test accuracy represent different evaluation stages and should not be interpreted as the same metric.

These values refer specifically to the recorded execution of this notebook and are not presented as aggregate results for all experiments.

## 6. Research Documentation

For a more detailed explanation of the research, methodology, and experimental findings, see:

- [Project Overview](../README.md)
- [Research Methodology](../METHODOLOGY.md)
- [Experimental Results](../RESULTS.md)
- [Research Limitations](../LIMITATIONS.md)

## 7. Academic Context

These notebooks form part of a Master's research project on image-based fake social media profile detection using deep learning, image normalization, and metaheuristic optimization.

They are provided to document the computational experiments and support the academic review of the research.

