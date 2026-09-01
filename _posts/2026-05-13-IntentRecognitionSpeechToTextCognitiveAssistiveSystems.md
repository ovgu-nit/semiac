---
title: "Intent Recognition in Speech-to-Text Processing in the Context of Natural Interaction with Cognitive Assistive Systems"
description: A study of speech-to-intent recognition for human-robot interaction in elderly-care environments in German, deployed on resource-constrained platforms, comparing a modular ASR+LLM pipeline against an end-to-end large audio-language model architecture.
background: /assets/theme/images/home.png
image: /assets/theme/images/IntentRecognition.png
author: "Behnam Ensan, Magnus Jung, Matthias Busch, Andreas Wendemuth"
categories: [Publication, Conference, Speech Processing]
conference: "**LREC 2026** [[paper]](https://doi.org/10.63317/2ekx6bohnzso)"
tags: [LREC 2026, Conference]
---

## Intent Recognition in Speech-to-Text Processing in the Context of Natural Interaction with Cognitive Assistive Systems

This work examines speech-to-intent recognition for human-robot interaction in elderly-care environments in German, deployed on resource-constrained platforms. We created domain-specific datasets (PaSID and PaSynTex) simulating nursing home scenarios and compare two approaches: a two-stage system combining automatic speech recognition with large language models, and an end-to-end large audio-language model architecture. Our findings show that optimized ASR+LLM configurations, particularly Whisper Turbo coupled with Phi-3.5-mini or Qwen 2.5-7B, outperform unified LALM approaches in efficiency. While unified models showed better accuracy, they required substantially more computational resources. Modular pipelines therefore provide a more practical solution for real-time, on-device intent recognition in assistive robotics in German, balancing performance with practical deployment constraints on edge devices.

![](/semiac/assets/theme/images/IntentRecognition.png)

---

## Fulltext Access
[https://doi.org/10.63317/2ekx6bohnzso](https://doi.org/10.63317/2ekx6bohnzso)

---

## Citing

```bibtex
@inproceedings{ensan2026intent,
  title={Intent Recognition in Speech-to-Text Processing in the Context of Natural Interaction with Cognitive Assistive Systems},
  author={Ensan, Behnam and Jung, Magnus and Busch, Matthias and Wendemuth, Andreas},
  booktitle={Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  volume={11},
  number={16},
  pages={10102--10113},
  year={2026},
  organization={ELRA}
}
```
