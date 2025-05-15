---
title: Fine-grained gaze estimation based on the combination of regression and classification losses
description: We present our recent work on gaze estimation. Our approach is a novel two-branch CNN architecture with a multi-loss approach to estimate gaze angles (pitch and yaw) from face images, enabling explicit learning of discriminative features for each angle. Through experiments on three datasets, the proposed model outperforms state-of-the-art methods, demonstrating superior performance in gaze estimation under unconstrained conditions.
background: /assets/theme/images/header-img.jpg
image: /assets/theme/images/applint-2024.png
author: "Ahmed A. Abdelrahman, Thorsten Hempel, Aly Khalifa, Ayoub Al-Hamadi"
categories: [Publication, Journal, Gaze estimation]
tag: [Journal, Publication]
conference: "**Springer Applied Intelligence 2024** [[paper]](https://link.springer.com/article/10.1007/s10489-024-05778-3)"
---

## Fine-grained gaze estimation based on the combination of regression and classification losses

Human gaze is a crucial cue used in various applications such as human-robot interaction, autonomous driving, and virtual reality. Recently, convolution neural network (CNN) approaches have made notable progress in predicting gaze angels. However, estimating accurate gaze direction in-the-wild is still a challenging problem due to the difficulty of obtaining the most crucial gaze information that exists in the eye area which constitutes a small part of the face images. In this paper, we introduce a novel two-branch CNN architecture with a multi-loss approach to estimate gaze angles (pitch and yaw) from face images. Our approach utilizes separate fully connected layers for each gaze angle prediction, allowing explicit learning of discriminative features and emphasizing the distinct information associated with each gaze angle. Moreover, we adopt a multi-loss approach, incorporating both classification and regression losses. This allows for joint optimization of the combined loss for each gaze angle, resulting in improved overall gaze performance. To evaluate our model, we conduct experiments on three popular datasets collected under unconstrained settings: MPIIFaceGaze, Gaze360, and RT-GENE. Our proposed model surpasses current state-of-the-art methods and achieves state-of-the-art performance on all three datasets, showcasing its superior capability in gaze estimation.
ChatGPT said:

![](/enabling/assets/theme/images/applint-2024.png)

---

## Fulltext Access
[https://link.springer.com/article/10.1007/s10489-024-05778-3](https://link.springer.com/article/10.1007/s10489-024-05778-3)

---

## Citing

```bibtex
@article{abdelrahman2024fine,
  title={Fine-grained gaze estimation based on the combination of regression and classification losses},
  author={Abdelrahman, Ahmed A and Hempel, Thorsten and Khalifa, Aly and Al-Hamadi, Ayoub},
  journal={Applied Intelligence},
  pages={1--13},
  year={2024},
  publisher={Springer}
}
```

