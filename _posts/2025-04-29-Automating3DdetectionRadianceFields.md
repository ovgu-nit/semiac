---
title: "Automating 3D Dataset Generation with Neural Radiance Fields"
description: We present a fully automated pipeline that leverages Radiance Field–based universal 3D representations to rapidly generate high-quality models of arbitrary objects and synthesize large, diverse 3D datasets—enabling state-of-the-art detection and pose-estimation performance despite the scarcity of public 3D data. 
background: /assets/theme/images/header-img.jpg
image: /assets/theme/images/Teaser.png
author: "Paul Schulz, Thorsten Hempel, Ayoub Al-Hamadi"
categories: [Publication, Conference, Engagement]
github: https://github.com/PaulSK98/Nerf2Dataset
conference: "**ROBOVIS 2025** [[paper]](https://arxiv.org/abs/2503.15997) [[code]]( https://github.com/PaulSK98/Nerf2Dataset)"
tags: [ROBOVIS 2025, Conference]
---

## Automating 3D Dataset Generation with Neural Radiance Fields

3D detection is a critical task to understand spatial characteristics of the environment and is used in a variety of applications including robotics, augmented reality, and image retrieval. Training performant detection models require diverse, precisely annotated, and large scale datasets that involve complex and expensive creation processes. Hence, there are only few public 3D datasets that are additionally limited in their range of classes. In this work, we propose a pipeline for automatic generation of 3D datasets for arbitrary objects. By utilizing the universal 3D representation and rendering capabilities of Radiance Fields, our pipeline generates high quality 3D models for arbitrary objects. These 3D models serve as input for a synthetic dataset generator. Our pipeline is fast, easy to use and has a high degree of automation. Our experiments demonstrate, that 3D pose estimation networks, trained with our generated datasets, archive strong performance in typical application scenarios. 
![](/enabling{{page.image}})

---

## Citing

```bibtex
@article{Schulz2025radiancefields,
  title={Automating 3D Dataset Generation with Neural Radiance Fields},
  author={Schulz, Paul and Hempel, Thorsten and Al-Hamadi, Ayoub},
  booktitle={International Conference on Robotics, Computer Vision and Intelligent Systems},
  year={2025},
  organization={Springer}
}
```