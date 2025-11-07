---
title: Scene-Aware Prediction of Diverse Human Movement Goals
description: Anticipation of human behaviours facilitates autonomous systems in proactive planning. Human behaviour could be stochastic due to varying goals. Human goals typically guide their own movement and could therefore help to predict the human trajectory and human motion in the long-term. To infer the human movement intentions, the environmental context plays a significant role, in addition to the social cues expressed by the individual. Previous works on human goals prediction either require semantic knowledge of the scene, or only tackle interactions with objects. In this paper, we propose a novel multi-goal prediction method using the generative model to address the stochasticity of human movement. It leverages the current RGB scene and the human pose to predict diverse potential future goals of human movement based on the Conditional Variational Autoencoder (CVAE). Our results demonstrate that our approach is capable of generating multiple movement goals in the scene via samplings in latent space of the CVAE and exhibits generalization capability across scenarios in GTA-IM dataset and PROX dataset. Code is publicly available at https://github.com/Q-Y-Yang/DiverseGoalsPrediction.git.
background: /assets/theme/images/home.png
image: /assets/theme/images/Scene-Aware Prediction.png
author: "Qiaoyue Yang, Amadeus Weber, Magnus Jung, Ayoub Al-Hamadi and Sven Wachsmuth"
categories: [Publication, Conference, MotionPrediction]
conference: "ROBOVIS 2025"
tags: [MotionPrediction, CVAE, HumanGoals]
---
## Scene-Aware Prediction of Diverse Human Movement Goals
Anticipation of human behaviours facilitates autonomous systems in proactive planning. Human behaviour could be stochastic due to varying goals. Human goals typically guide their own movement and could therefore help to predict the human trajectory and human motion in the long-term. To infer the human movement intentions, the environmental context plays a significant role, in addition to the social cues expressed by the individual. Previous works on human goals prediction either require semantic knowledge of the scene, or only tackle interactions with objects. In this paper, we propose a novel multi-goal prediction method using the generative model to address the stochasticity of human movement. It leverages the current RGB scene and the human pose to predict diverse potential future goals of human movement based on the Conditional Variational Autoencoder (CVAE). Our results demonstrate that our approach is capable of generating multiple movement goals in the scene via samplings in latent space of the CVAE and exhibits generalization capability across scenarios in GTA-IM dataset and PROX dataset. Code is publicly available at https://github.com/Q-Y-Yang/DiverseGoalsPrediction.git.

## Citing
```bibtex
@inproceedings{yang2025scene,
  title={Scene-Aware Prediction of Diverse Human Movement Goals},
  author={Yang, Qiaoyue and Weber, Amadeus and Jung, Magnus and Al-Hamadi, Ayoub and Wachsmuth, Sven},
  booktitle={International Conference on Robotics, Computer Vision and Intelligent Systems},
  pages={312--327},
  year={2025},
  organization={Springer}
}
```