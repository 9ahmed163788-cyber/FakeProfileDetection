# Research Methodology

## 1. Research Framework

This research investigates image-based fake social media profile detection using deep learning, image normalization techniques, and metaheuristic hyperparameter optimization.

The experimental framework is based on a ResNet-50 convolutional neural network and consists of two main research stages:

1. Evaluating different image normalization techniques.
2. Investigating five metaheuristic optimization algorithms independently for hyperparameter optimization.

Each optimization algorithm is treated as a separate experimental approach. Its implementation, evaluation, and results are considered individually before comparing the outcomes.

## 2. Dataset Description

The experiments use the **X Fake Profile Detection** dataset.

**Dataset source:**  
https://huggingface.co/datasets/drveronika/x_fake_profile_detection

The dataset contains profile images belonging to four categories:

- Bot
- Cyborg
- Real
- Verified

The dataset configuration documented in the Master's thesis is as follows:

| Dataset Split | Number of Images |
|---|---:|
| Training | 10,000 |
| Validation | 1,000 |
| Testing | 4,000 |
| **Total** | **15,000** |

Images are processed at a resolution of 224 × 224 pixels in RGB format.

## 3. Image Normalization

The first experimental stage investigates ten normalization techniques to examine their influence on image representation and classification performance.

The investigated techniques are:

| No. | Normalization Technique |
|---:|---|
| 1 | Min-Max Normalization |
| 2 | Z-Score Normalization |
| 3 | Mean Normalization |
| 4 | Decimal Scaling |
| 5 | Histogram Equalization |
| 6 | Principal Component Analysis (PCA) |
| 7 | Whitening |
| 8 | Batch Normalization |
| 9 | Local Contrast Normalization (LCN) |
| 10 | Color Normalization |

The purpose of this stage is to investigate the relationship between image preprocessing strategies and the classification performance of the selected deep learning architecture.

The normalization experiments are evaluated within the image-classification framework, and their reported outcomes are documented in the Master's thesis.

## 4. Deep Learning Architecture

### ResNet-50

ResNet-50 is adopted as the main image-classification architecture.

The implementation uses transfer learning with pretrained weights and a customized classification layer adapted to the four target categories.

The model is implemented using **PyTorch**.

The documented training framework includes:

- Pretrained ResNet-50 architecture.
- Fine-tuning of the classification model.
- Cross-Entropy Loss.
- AdamW optimizer.
- Learning-rate scheduling.
- Data augmentation.
- Early stopping.
- Validation and test evaluation.

The model is designed to classify profile images into Bot, Cyborg, Real, and Verified categories.

## 5. Metaheuristic Hyperparameter Optimization

The second research stage investigates the application of metaheuristic optimization algorithms for deep learning hyperparameter tuning.

Five algorithms are studied:

1. Tug of War Optimization (TWO).
2. Hunger Games Search (HGS).
3. Kho-Kho Optimization (KKO).
4. Golf Optimization Algorithm (GOA).
5. Shell Game Optimization (SGO).

### Independent Experimental Design

Each algorithm is implemented and evaluated independently.

The experiments are not treated as a single combined optimization procedure. Instead, each algorithm has its own implementation and corresponding experimental results.

This design allows the performance of the individual optimization approaches to be examined and compared.

The investigated optimization parameters include training-related hyperparameters such as:

- Learning rate.
- Weight decay.
- Batch size.
- Dropout rate.
- Other training configuration parameters, depending on the experiment.

The optimization experiments and their corresponding outcomes are documented separately in the Master's thesis.

## 6. Experimental Evaluation

The research evaluates classification performance using several metrics:

- Accuracy.
- Precision.
- Recall.
- F1-score.
- Loss.
- Confusion matrices.
- Classification reports.

The experiments use training, validation, and test data for model development and performance assessment.

The normalization techniques and independent metaheuristic optimization experiments are examined through their respective experimental configurations.

## 7. Comparative Analysis

The final research stage compares the reported experimental outcomes.

The analysis considers:

- The influence of image normalization techniques.
- The performance of the ResNet-50 classification architecture.
- The results obtained from each independently implemented metaheuristic algorithm.
- Differences between experimental configurations.
- Classification metrics and computational evaluation where documented.

The comparative findings are presented in the Master's thesis and summarized in the repository's `RESULTS.md` file.

## 8. Technologies and Tools

| Component | Technology |
|---|---|
| Programming Language | Python |
| Deep Learning Framework | PyTorch |
| Model Architecture | ResNet-50 |
| Image Processing | OpenCV, NumPy |
| Data Analysis | Pandas |
| Model Evaluation | Scikit-learn |
| Visualization | Matplotlib |
| Development Environment | Jupyter Notebook |

## 9. Research Scope

This research focuses specifically on image-based classification of social media profile categories.

It does not claim to provide complete social media account verification or to detect fraudulent accounts through behavioral analysis, textual content, social-network relationships, or real-time platform monitoring.

The findings should be interpreted within the scope of the selected dataset, model architecture, preprocessing methods, and experimental configurations.

## 10. Academic Reference

**Research Title:**  
*Solution pour la détection des faux profils sur les réseaux sociaux : normalisation des images.*

**Degree:** Master's Degree in Computer Science – Pattern Recognition and Artificial Intelligence.

**Institution:** Hassiba Ben Bouali University of Chlef, Algeria.

**Year:** 2025.

**Repository:**  
https://github.com/9ahmed163788-cyber/FakeProfileDetection

