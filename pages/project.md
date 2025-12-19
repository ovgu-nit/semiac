---
title: SEMIAC
description: "Implicit mobile human-robot communication for spatial action coordination with action-specific semantic environment modelling"
background: /assets/theme/images/home.png
permalink: /project/
---

{: .alert .alert-warning}
 
<!-- ![image](/enabling/assets/theme/images/home.png) -->

<!-- # SEMIAC -->


## Project
With the increasing use of robots in industrial and everyday contexts, the need for systems that can interact flexibly and cooperatively with humans is growing. Collaborative robots (cobots) in particular, which share a common workspace with humans and can react to complex, dynamic environments, are coming into focus. A central challenge here is the context-related perception of the environment and the appropriate interpretation of human behavior.

## Research questions
The project presented addresses this problem by systematically investigating difficult perception situations in human-robot collaborations. The focus here is on three central research questions: (1) How can a robot perceive action spaces in a context-sensitive manner and use them in the sense of addressee-oriented communication? (2) How can implicit human behavior patterns - such as facial expressions, gestures or changes in movement - be used to interpret mental states? (3) How can a more robust, interpretable movement planning be realized through active spatial coordination?

## Goals
The aim of the SEMIAC project is to develop and evaluate a responsive, mobile robot system that uses implicit forms of communication, in particular the communication of interaction-relevant states and spatial prompting, to achieve automatic and adaptive coordination with human partners in cooperative situations.

## Report

Das Projekt **SEMIAC** („Implizite mobile Mensch-Roboter-Kommunikation für die räumliche Handlungskoordination mit aktionsspezifischer semantischer Umgebungsmodellierung“) – Projektnr. **502483052 (AL 638/15, WA1622/2-1)** – etablierte fundierte wissenschaftliche und technische Grundlagen für sozial kompetente, räumlich präzise Eins-zu-Eins-Interaktionen (vgl. [https://ovgu-nit.github.io/semiac/](https://ovgu-nit.github.io/semiac/)). Kernfragen lauteten, wie ein mobiler Roboter menschliche Intentionen, Aufmerksamkeit, emotionale Zustände und soziale Signale robust erfasst und in transparentes, responsives Verhalten umwandelt. Dies gelang durch eine enge Verzahnung von experimenteller Datenakquisition (z.B. Wizard-of-Oz-Studien mit gezielt induzierten Fehlern zur Provokation realer Probandenreaktionen), fortschrittlichen Wahrnehmungsmodellen, semantischer Umgebungsinterpretation, sozialer Signalverarbeitung und lernfähiger Bewegungssteuerung.

#### Empirische Datengrundlagen

Im Projekt SEMIAC wurden die folgenden empirischen Datengrundlagen geschaffen:

- **SEMIAC-Datensatz**: Multimodal und mehrperspektivisch (Robotersicht + externe Kameras), speziell für die Analyse impliziter Kommunikationsdynamiken in herausfordernden 1-zu-1-Situationen (vgl. [https://ovgu-nit.github.io/semiac/datasets/SEMIAC/](https://ovgu-nit.github.io/semiac/datasets/SEMIAC/)) [semiac19].
- **NITEC-Datensatz**: Fokussiert auf Egoperspektive-Blickkontaktschätzung; Modelle erreichen bis zu 86,8 % Genauigkeit mit minimalen Features wie Blickintensität über die Zeit und übertreffen bestehende Methoden (vgl. [https://ovgu-nit.github.io/semiac/datasets/NITEC/](https://ovgu-nit.github.io/semiac/datasets/NITEC/)) [semiac1, semiac6].
- **ODE-3D-Datensatz**: Kombiniert Blickrichtung, Kopfpose und Zeigegesten für aufmerksamkeitssensitive Objektidentifikation (vgl. [https://ovgu-nit.github.io/semiac/datasets/ODE-3D/](https://ovgu-nit.github.io/semiac/datasets/ODE-3D/)) [semiac20].

#### Methodische Modelle und Frameworks

Für die methodische Umsetzung wurden die folgenden Modelle und Frameworks entwickelt (vgl. [https://ovgu-nit.github.io/semiac/](https://ovgu-nit.github.io/semiac/)):

- **IM HERE**: Theoretisches Modell mit vier interpretierbaren Engagement-Zuständen basierend auf menschlichem Aufwand; ermöglicht frühe Misskommunikationserkennung als Wegweiser für adaptive Strategien [semiac2].
- **VAE3D-Net**: Simultane Schätzung affektiver und attentiver Zustände aus Egoperspektive-Videos; erzeugt dichte 3D-Repräsentationen zur Erkennung früher Disengagement-Anzeichen und Vermeidung von Abbrüchen [semiac14].
- **Adaptives Proxemik-Modell**: Lernt situationsspezifische Distanzregeln aus Daten und integriert sie in Bewegungsplanung; Roboter werden als angenehmer, sicherer und kompetenter wahrgenommen [semiac4].
- **Zielantizipationsverfahren**: Conditional Variational Autoencoder generiert plausible Bewegungszielhypothesen unter Berücksichtigung von Szenegeometrie und Personenspose; ergänzt durch Modelle für langfristige Vorhersagen bei Verdeckungen [semiac5, semiac21].
- **Synthetische Datengenerierung**: Automatisierte Pipeline mit Radiance Fields für hochqualitative 3D-Objektdigitalisierung; starke Generalisierung in realen Szenarien, ergänzt reale Datensätze ideal [semiac7, semiac13].

#### Integrierte Verhaltensmodelle und Robotersysteme

Für die Entwicklung integrierter Verhaltensmodelle auf den Roboterplattformen wurden die folgenden integrativen Ansätze entwickelt:

- **LLM-Integration**: Taxonomie für Large Language Models in Roboterarchitekturen; demonstriert flexiblere, kontextsensitive Aufgabenlösung auf TIAGo-Plattform im Vergleich zu symbolischen Ansätzen [semiac3].
- **Semantische SLAM-Erweiterung**: Integriert bewegte Objekte und soziale Dynamiken für stabile Kartenbildung [semiac22].

#### Erweiterte Beiträge

Erweiterte Beiträge (weitere 9 Publikationen) decken Multi-Sensor-Fusion [semiac8], multimodale Assistenz [semiac9], Handlungserkennung [semiac10, semiac17], Blickschätzung [semiac11], Radiance-Fields [semiac12], Gestenerkennung [semiac15], Sprachintents [semiac16] und robuste Blickkontaktmodelle [semiac18] ab. Diese dokumentieren die wissenschaftliche Tiefe, Breite und enge Kooperation der Forschungsgruppen im Rahmen von SEMIAC.

### Literatur

- **[semiac1]** Hempel, Thorsten, et al. *NITEC: Versatile hand-annotated eye contact dataset for ego-vision interaction.* Proceedings of the IEEE/CVF WACV, 2024. doi: 10.1109/WACV57701.2024.00438
- **[semiac2]** Strazdas, Dominykas, et al. *IM Here: interaction model for human effort based robot engagement.* IEEE CogSIMA, 2025. doi: 10.1109/CogSIMA64436.2025.11079517
- **[semiac3]** Jung, Magnus, et al. *Toward truly intelligent autonomous systems: a taxonomy of LLM integration for everyday automation.* Springer Nature, 2025.
- **[semiac4]** Yang, Qiaoyue, et al. *Learning Human–Robot Proxemics Models from Experimental Data.* Electronics 14(18), 2025. doi: 10.3390/electronics14183704
- **[semiac5]** Yang, Qiaoyue, et al. *Scene-Aware Prediction of Diverse Human Movement Goals.* Springer, 2025. doi: 10.1007/978-3-032-00986-9\_21
- **[semiac6]** Jung, Magnus, et al. *Eye contact based engagement prediction for efficient human–robot interaction.* Complex & Intelligent Systems 11(7), 2025. doi: 10.1007/s40747-025-01902-z
- **[semiac7]** Schulz, Paul, et al. *Automated 3D Dataset Generation for Arbitrary Objects.* IEEE Access, 2025. doi: 10.1109/ACCESS.2025.3617952
- **[semiac8]** Al-Tawil, Basheer, et al. *Mobile Robot Navigation with Enhanced 2D Mapping and Multi-Sensor Fusion.* Sensors 25(8), 2025. doi: 10.3390/s25082408
- **[semiac9]** Strazdas, Dominykas, et al. *Robot System Assistant (RoSA).* Frontiers in Robotics and AI 12, 2025. doi: 10.3389/frobt.2025.1561188
- **[semiac10]** Al-Tawil, Basheer, et al. *Multi-Head Attention-Based Framework with Residual Network for Human Action Recognition.* Sensors 25(9), 2025. doi: 10.3390/s25092930
- **[semiac11]** Abdelrahman, Ahmed A., et al. *Fine-grained gaze estimation.* Applied Intelligence 54(21), 2024. doi: 10.1007/s10489-024-05778-3
- **[semiac12]** Schulz, Paul, et al. *Automating 3D Dataset Generation with Neural Radiance Fields.* Springer, 2025. doi: 10.1007/978-3-032-00986-9\_3
- **[semiac13]** Schulz, Paul, et al. *Automating synthetic dataset generation for image-based 3D detection.* Artificial Intelligence Review 59(1), 2025. doi: 10.1007/s10462-025-11431-3
- **[semiac14]** *Joint Estimation of Affective and Attentional States from Egocentric Video Input for Human-Robot Interaction.* (under review)
- **[semiac15]** *GESTRO: Skeleton-based Dynamic Gesture Recognition for Robot Teleoperation.* (under review)
- **[semiac16]** *Intent Recognition in Speech-to-Text Processing in the Context of Natural Interaction with Cognitive Assistive Systems.* (under review)
- **[semiac17]** *REMA-Net: A Real-Time, Efficient Multistream Attention Network for Human Action Recognition in Robotic Applications.* (under review)
- **[semiac18]** *Gaze Matters: Eye Contact Detection in Unscripted Human-Robot Interaction Scenarios.* (under review)
- **[semiac19]** *SEMIAC: A Two-Site Human-Robot Collaboration Dataset for Exploring Socially-enriched Models for Implicit Action Coordination.* HRI 2026 (under review)
- **[semiac20]** *ODE-3D: A Dataset for Multimodal Attention-Based Object Detection in Human-Machine Interaction.* (in Vorbereitung)
- **[semiac21]** Yang, Qiaoyue, et al. *Long-Term Prediction of Local and Global Human Motion with Occlusion Recovery.* ISVC 2025, erscheint.
- **[semiac22]** *SAR-SLAM: Semantic Aware Recognition for Dynamic SLAM in Robotic Applications.* (in Vorbereitung)



# Founding
The project is funded by the German Research Foundation (DFG) under grant No. 502483052 and is planned with a project duration of 3 years (2023 to 2026).

