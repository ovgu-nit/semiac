---
title: "Eye Contact Based Engagement Prediction for Efficient Human-Robot Interaction"
description: We introduce a new approach to predict human engagement in human-robot interactions (HRI), focusing on eye contact and distance information. Recognising engagement, particularly its decline, is essential for successful and natural interactions. This requires early, real-time user behavior detection.
background: /assets/theme/images/header-img.jpg
image: /assets/theme/images/EyeContactBasedEngagementForHRI2025.png
author: "Magnus Jung, Ahmed A. Abdelrahmanand, Thorsten Hempel, Basheer Al-Tawil, Qiaoyue Yang, Sven Wachsmuth, Ayoub Al-Hamadi"
categories: [Publication, Journal, Engagement]
conference: "**CIS 2025, *accepted***"
tags: [Journal, Springer, Publication]
---

## Fine-grained gaze estimation based on the combination of regression and classification losses

We introduces a new approach to predict human engagement in human-robot interactions (HRI), focusing on eye contact and distance information. Recognising engagement, particularly its decline, is essential for successful and natural interactions. This requires early, real-time user behavior detection. Previous HRI engagement classification approaches use various audiovisual features or adopt end-to-end methods. However, both approaches face challenges: the former risks error accumulation, while the latter suffer from small datasets. 
The proposed class-sensitive model for capturing engagement in HRI is based on eye contact detection.
By analyzing eye contact intensity over time, the model provides a more robust and reliable measure of engagement levels, effectively capturing both temporal dynamics and subtle behavioral changes.
Direct eye contact detection, a crucial social signal in human interactions that has not yet been explored as a standalone indicator in HRI, offers a significant advantage in robustness over gaze detection and incorporates additional facial features into the assessment. This approach reduces the number of features from up to over 100 to just two, enabling real-time processing and surpassing state-of-the-art results with 80.73% accuracy and 80.68% F1-Score on the UE-HRI dataset, the primary resource in current engagment detection research. Additionally, cross-dataset testing on a newly recorded dataset with the Tiago robot from Pal Robotics achieved an accuracy of 86.8% and an F1-score of 87.9%.
The model employs a sliding window approach and consists of just three fully connected layers for feature fusion and classification, offering a minimalistic yet effective architecture.
The study reveals that engagement, traditionally relying on extensive feature sets, can be inferred reliably from temporal eye contact dynamics. The results include a detailed analysis of established engagement levels on the UE-HRI dataset using the proposed model. Additionally, models for more nuanced engagement classification are introduced, showcasing the effectiveness of this minimalistic feature set. These models provide a robust foundation for future research, advancing robotic systems and deepening understanding of HRI, for example by improving real-time social cue detection and creating adaptive engagement strategies in HRI.

![](/enabling/assets/theme/images/EyeContactBasedEngagementForHRI2025.png)

---

## Fulltext Access
https://link.springer.com/article/10.1007/s40747-025-01902-z
---

## Citing

```bibtex
@article{jung2025eye,
  title={Eye contact based engagement prediction for efficient human--robot interaction},
  author={Jung, Magnus and Abdelrahman, Ahmed and Hempel, Thorsten and Al-Tawil, Basheer and Yang, Qiaoyue and Wachsmuth, Sven and Al-Hamadi, Ayoub},
  journal={Complex \& Intelligent Systems},
  volume={11},
  number={7},
  pages={1--20},
  year={2025},
  publisher={Springer}
}
```
