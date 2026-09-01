---
title: "Long-Term Prediction of Local and Global Human Motion with Occlusion Recovery"
description: A non-autoregressive transformer based on spatio-temporal attention, trained for both local pose anticipation and global motion prediction in space, while recovering joints missing due to occlusions and handling varying lengths of history observations.
background: /assets/theme/images/home.png
image: /assets/theme/images/LongTermHumanMotion_skeleton.jpg
author: "Qiaoyue Yang, Sven Heutger, Christopher Niemann, Magnus Jung, Ayoub Al-Hamadi, Sven Wachsmuth"
categories: [Publication, Conference, Human Motion Prediction]
github: https://github.com/Q-Y-Yang/Prediction-of-Local-and-Global-Human-Motion
conference: "**ISVC 2025** [[code]](https://github.com/Q-Y-Yang/Prediction-of-Local-and-Global-Human-Motion)"
tags: [ISVC 2025, Conference]
---

## Long-Term Prediction of Local and Global Human Motion with Occlusion Recovery

Human motion prediction anticipates the three-dimensional full-body movement of a person and is relevant to applications including human-robot interaction, autonomous driving, animation, and healthcare. Existing approaches typically rely on autoregressive mechanisms, which can accumulate errors over extended prediction horizons and focus only on local pose prediction. To overcome these limitations, we propose a non-autoregressive transformer based on spatio-temporal attention that is trained not only for local pose anticipation but also for global motion prediction in space. To enhance its applicability in real-world scenarios, the model is trained to recover missing joints caused by occlusions and can process varying lengths of history observations.

![](/semiac/assets/theme/images/LongTermHumanMotion_skeleton.jpg)

---

## Citing

```bibtex
@inproceedings{yang2025longterm,
  title={Long-Term Prediction of Local and Global Human Motion with Occlusion Recovery},
  author={Yang, Qiaoyue and Heutger, Sven and Niemann, Christopher and Jung, Magnus and Al-Hamadi, Ayoub and Wachsmuth, Sven},
  booktitle={International Symposium on Visual Computing},
  pages={141--153},
  year={2025},
  organization={Springer}
}
```
