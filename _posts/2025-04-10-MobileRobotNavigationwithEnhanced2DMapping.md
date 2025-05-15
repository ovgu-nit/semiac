---
title: Mobile Robot Navigation with Enhanced 2D Mapping and Multi-Sensor Fusion
description: We propose an enhanced SLAM framework that combines RGB-D and 2D LiDAR data using late fusion and adaptive resampling for robust and efficient mobile robot navigation. Our approach improves mapping accuracy and localization performance both in simulation and real-world settings using the Tiago robot.
background: /assets/theme/images/header-img.jpg
image: /assets/theme/images/nav.png
author: "Basheer Al-Tawil, Adem Candemir, Magnus Jung, Ayoub Al-Hamadi"
categories: [Publication, Journal, SLAM, Robotics]
tag: [SLAM, Multi-Sensor Fusion, Robot Navigation, Gmapping, RGB-D, LiDAR]
journal: "**MDPI Sensors 2025** [[paper]](https://www.mdpi.com/1424-8220/25/8/2408)"
---

## Mobile Robot Navigation with Enhanced 2D Mapping and Multi-Sensor Fusion

This work presents a robust and accurate SLAM framework that leverages RGB-D cameras and 2D LiDAR sensors to enhance mobile robot navigation. We introduce a data fusion pipeline where RGB-D point clouds are projected into 2D and denoised together with LiDAR data. These are then merged through late fusion and utilized in our Enhanced Gmapping (EGM) algorithm, which incorporates adaptive resampling and degeneracy handling to mitigate particle depletion. The proposed system was validated in simulated environments of varying complexity and on a real Tiago robot in small-scale indoor setups. Compared to RTAB-Map and classical Gmapping, our method achieved an 8% reduction in path length, 13% lower processing time, and 15% higher goal completion in simulation. In real-world tests, EGM achieved a 3% reduction in distance traveled and a 9% decrease in execution time.
![](/enabling/assets/theme/images/nav.png)

---

## Fulltext Access
[https://doi.org/10.3390/s25092930](https://doi.org/10.3390/s25092930)

## Citing

```bibtex
@article{al2025mobile,
  title={Mobile Robot Navigation with Enhanced 2D Mapping and Multi-Sensor Fusion},
  author={Al-Tawil, Basheer and Candemir, Adem and Jung, Magnus and Al-Hamadi, Ayoub},
  journal={Sensors},
  volume={25},
  number={8},
  pages={2408},
  year={2025},
  publisher={MDPI}
}
```
