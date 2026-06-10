# SEMTEC: Emotion-Based Rumor Detection in Social Media

## Overview

This repository contains an implementation of **SEMTEC (Sentiment and EMotion driven TransformEr Classifier)**, a deep learning framework for detecting rumors in social media posts.

The model leverages:

* Textual content from tweets
* Sentiment information
* Emotion annotations
* Transformer-based contextual representations

By incorporating emotional and sentiment cues alongside textual features, SEMTEC improves the identification of misleading and unverified information circulating on social media platforms.

---

## Motivation

The rapid spread of information through social media platforms has made rumor detection a critical challenge. Unverified information can significantly impact public opinion, decision-making, and societal behavior.

Traditional rumor detection methods primarily focus on textual content or propagation patterns. SEMTEC enhances detection performance by incorporating users' emotional and sentimental expressions, enabling a richer understanding of the context surrounding social media posts.

---

## Methodology

### SEMTEC Architecture

The proposed framework consists of the following stages:

1. **Tweet Preprocessing**

   * Text cleaning
   * Tokenization
   * Normalization

2. **Sentiment Extraction**

   * Identification of sentiment polarity
   * Positive, negative, and neutral sentiment labels

3. **Emotion Detection**

   * Extraction of emotional characteristics from tweets
   * Emotion-aware feature generation

4. **Transformer Encoding**

   * Contextual representation learning
   * Semantic feature extraction

5. **Feature Fusion**

   * Integration of textual, sentiment, and emotion features

6. **Classification Layer**

   * Binary classification:

     * Rumor
     * Non-Rumor

---

## Dataset

### PHEME Dataset

The primary evaluation dataset consists of rumor and non-rumor events collected from Twitter.

### Twitter24 Dataset

A novel dataset introduced for validating the robustness and generalization capability of the proposed framework.

---
## Results

The proposed SEMTEC framework demonstrates strong performance for rumor detection by incorporating sentiment and emotion information alongside textual representations.

| Dataset   | Accuracy                       |
| --------- | ------------------------------ |
| PHEME     | ~92%                           |
| Twitter24 | Improved over baseline methods |

---

## Key Features

* Transformer-based text understanding
* Emotion-aware rumor detection
* Sentiment-enhanced classification
* End-to-end deep learning pipeline
* Improved generalization across datasets

---

## Citation

If you use this work, please cite:

```bibtex
@article{sharma2024semtec,
  title={Detecting Rumors in Social Media Using Emotion Based Deep Learning Approach},
  author={Sharma, Drishti and Srivastava, Abhishek},
  journal={PeerJ Computer Science},
  volume={10},
  pages={e2202},
  year={2024},
  doi={10.7717/peerj-cs.2202}
}
```

---

## Reference

Sharma, D., & Srivastava, A. (2024). *Detecting Rumors in Social Media Using Emotion Based Deep Learning Approach*. PeerJ Computer Science, 10:e2202.

DOI: https://doi.org/10.7717/peerj-cs.2202

---

## License

This project is intended for research and educational purposes.
