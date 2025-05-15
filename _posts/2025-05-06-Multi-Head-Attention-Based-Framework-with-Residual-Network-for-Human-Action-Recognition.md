---
title: Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition
description: We propose a novel HAR framework integrating residual networks, Bi-LSTM, and multi-head attention with a motion-based frame selection strategy. It achieves 96.60% accuracy on UCF-101 and supports real-time performance, even on mobile robots.
background: /assets/theme/images/header-img.jpg
image: /assets/theme/images/har_model.png
author: "Basheer Al-Tawil, Magnus Jung, Thorsten Hempel, Ayoub Al-Hamadi"
categories: [Publication, Journal, Human Action Recognition]
github: https://github.com/basheeraltawil/HAR-ResNet-BiLSTM-Attention
tag: [Journal, HAR, Deep Learning]
conference: "**MDPI Sensors 2025** [[paper]](https://doi.org/10.3390/s25092930)"
---

## Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition
Human action recognition (HAR) is essential for understanding and classifying human movements. It is widely used in real-life applications such as human–computer interaction and assistive robotics. However, recognizing patterns across different temporal scales remains challenging. Traditional methods struggle with complex timing patterns, intra-class variability, and inter-class similarities, leading to misclassifications.
In this paper, we propose a deep learning framework for efficient and robust HAR. It integrates residual networks (ResNet-18) for spatial feature extraction and Bi-LSTM for temporal feature extraction. A multi-head attention mechanism enhances the prioritization of crucial motion details. Additionally, we introduce a motion-based frame selection strategy utilizing optical flow to reduce redundancy and enhance efficiency. This ensures accurate, real-time recognition of both simple and complex actions.
We evaluate the framework on the UCF-101 dataset, achieving a 96.60% accuracy, demonstrating competitive performance against state-of-the-art approaches. Moreover, the framework operates at 222 frames per second (FPS), achieving an optimal balance between recognition performance and computational efficiency. The proposed framework was also deployed and tested on a mobile service robot, TIAGo, validating its real-time applicability in real-world scenarios. It effectively models human actions while minimizing frame dependency, making it well-suited for real-time applications.
![](/enabling/assets/theme/images/har_model.png)

---

## Fulltext Access
[https://doi.org/10.3390/s25092930](https://doi.org/10.3390/s25092930)

---

## Citing

```bibtex
@Article{s25092930,
AUTHOR = {Al-Tawil, Basheer and Jung, Magnus and Hempel, Thorsten and Al-Hamadi, Ayoub},
TITLE = {Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition},
JOURNAL = {Sensors},
VOLUME = {25},
YEAR = {2025},
NUMBER = {9},
ARTICLE-NUMBER = {2930},
URL = {https://www.mdpi.com/1424-8220/25/9/2930},
ISSN = {1424-8220},
DOI = {10.3390/s25092930}
}
```
