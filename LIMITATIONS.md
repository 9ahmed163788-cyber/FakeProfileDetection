# Research Limitations and Future Directions

## 1. Research Scope

This project investigates image-based fake social media profile classification using deep learning, image normalization techniques, and metaheuristic hyperparameter optimization.

The classification task considers four categories:

- Bot
- Cyborg
- Real
- Verified

The research focuses on evaluating the influence of image preprocessing and independently implemented optimization algorithms on the classification performance of a ResNet-50 model.

The findings are limited to the selected dataset, classification task, model architecture, and experimental configurations investigated in this research.

## 2. Limitations of Image-Based Classification

The proposed framework analyzes profile images rather than complete social media accounts.

Consequently, the approach does not directly evaluate:

- User activity and behavioral patterns.
- Posting frequency and interaction history.
- Textual content and linguistic characteristics.
- Social-network relationships and interaction graphs.
- Account creation history and other platform-specific signals.
- Real-time account activity.

Profile images provide only one source of information about an online account. Image-based classification alone cannot establish whether a complete social media account is authentic, automated, or fraudulent.

A more comprehensive assessment would require combining visual information with additional behavioral, linguistic, and social-contextual features.

## 3. Dataset Dependency and Generalization

The experimental findings depend on the selected X Fake Profile Detection dataset.

The model's performance may vary when applied to:

- Other social media datasets.
- Different platforms and profile-image distributions.
- Images with different resolutions or visual characteristics.
- Previously unseen image categories and account types.
- Real-world conditions that differ from the experimental dataset.

The reported results should therefore not be interpreted as evidence of equivalent performance across all social media platforms or deployment environments.

Further evaluation using independent datasets and external test environments would help assess generalization, robustness, and the practical applicability of the proposed approach.

## 4. Experimental Configuration and Evaluation Limitations

The reported results correspond to the specific model configurations, normalization techniques, and independent metaheuristic optimization experiments documented in the Master's thesis.

The five optimization algorithms were investigated separately rather than as a unified optimization procedure.

Consequently, comparisons between their reported outcomes should take into account differences in experimental configurations and evaluation settings.

The reported performance values describe the experiments conducted within this research and should not be interpreted as universal performance guarantees.

Additional controlled experiments, repeated evaluations, and comparisons under consistent experimental conditions could provide further evidence regarding the stability and reproducibility of the findings.

## 5. Future Research Directions

Several research directions could extend the scope of this project.

### 5.1 Multimodal Fake Profile Detection

Combining profile images with textual information and other available account signals could provide a more comprehensive representation of social media profiles.

### 5.2 Behavioral and Social-Network Analysis

Integrating user activity, interaction patterns, and social-network relationships could help investigate characteristics that cannot be identified through profile images alone.

### 5.3 Generalization and Robustness

Evaluating the proposed approach on additional independent datasets could provide further insight into its generalization capabilities.

Future experiments could also investigate robustness under different image conditions, visual transformations, and distribution shifts.

### 5.4 Explainable Artificial Intelligence

Integrating Explainable AI (XAI) techniques could help interpret model predictions and provide greater insight into the visual features influencing classification decisions.

### 5.5 Natural Language Processing and Language Models

Extending the research toward NLP and language-model-based approaches could support the investigation of textual misinformation, harmful content, and broader online safety challenges.

This direction could connect image-based profile analysis with human–AI interaction and more comprehensive approaches to detecting online threats.

## 6. Conclusion

This project provides an experimental investigation of image normalization and independently evaluated metaheuristic optimization approaches for ResNet-50-based social media profile-image classification.

While the findings demonstrate the performance observed under the investigated experimental conditions, the research also highlights the limitations of relying exclusively on visual information.

These limitations identify opportunities for extending image-based analysis toward more comprehensive, multimodal, explainable, and robust approaches to online safety.

---

*This document outlines the research scope, methodological limitations, and potential future directions of the Master's research project.*
