---
title: "Courses"
date: 2025-07-29
layout: courses
---

## Courses and Theses'

A selection of courses I have taken during my Master's and Ph.D. studies.

---

### Friedrich-Alexander-Universität Erlangen-Nürnberg  
*(M.Sc. Studies)*

Grades are on a scale from 1.0 (very good) to 4.0 (sufficient), with 1.0 being the best grade. (German grading system - Steps: 1.0, 1.3, 1.7, 2.0, 2.3, 2.7, 3.0, 3.3, 3.7, 4.0)

- Advanced Topics in Information Theory (1.0)  
- Audio Processing Seminar (1.0)  
- Audio Processing Laboratory (pass)
- Communication Electronics (1.3)  
- Communication Networks (2.3)  
- Digital Communications (2.7)  
- Digital Signal Processing (1.7) 
- Digital Signal Processing Laboratory (pass) 
- Equalization and Adaptive Systems for Digital Communications (1.0)  
- Global Navigation Satellite Systems (1.3)  
- Information Theory and Coding (1.3)  
- Microwave Engineering (2.3)  
- Medical Electronics (1.7)
- Mobile Communications (2.0)  
- Photonics 1 (2.3)
- Speak convincingly and present yourself with confidence (1.3)
- Speech Enhancement (1.0)  
- Speech and Audio Signal Processing (2.3)  
- Statistical Signal Processing (2.3)

#### Research Project

**Block-Online Implementation of Independent Vector Analysis (Python)**  
Implemented a block-online version of Independent Vector Analysis (IVA) for blind source separation of convolutive mixtures. The approach processes audio in chunks, enabling real-time applications and dynamic source scenarios. Performance was benchmarked against traditional online IVA and evaluated in simulated reverberant environments with moving sources.

#### Master's Thesis
[**Impact of Diffuse and Disturbed Reflection on Room Geometry Inference Algorithms**](/uploads/thesis.pdf)

**Abstract**
Room geometry inference algorithms are used to provide information about the reflector locations.
These algorithms are applied in the context of e.g. sound-source localization, speaker tracking
and dereverberation. For the estimation of the reflector locations, the sound reflections of the
walls are used. As we don’t live in a perfect world, reflections occur which are not reflected
specular, but into random directions. These reflections can impair the performance of such
algorithms. In this context, it is needed to study the impact of these diffuse reflections.
In this thesis, we address the problem of simulating first-order diffuse reflections. An approach is
proposed to simulate these reflections with three different models and directly obtain the pressure
room impulse response. With the three models, it is possible to simulate different conditions.
Further, we examine the behavior of the simulation and the different methods.
With the simulation of the diffuse reflections, the impact on a state-of-the-art room geometry
inference algorithm is carried out. We show the performance under different diffuse conditions
with a microscopic and a macroscopic view. The microscopic view is concerned with the impact
on the time-of-arrival detection of the wall reflections. On the other hand, the macroscopic
view provides an overview of average performance metrics. By the gained knowledge, we then
propose filtering techniques to cope with diffuse reflections for robustness in diffuse conditions.
Specifically, we use image-based filtering techniques, the bilateral filter, and an extended gradient
filter to equalize the impact of diffuse reflections. With the application of the filtering techniques,
we are able to improve the overall performance of the algorithm in diffuse conditions.

Grade: 1.0 (very good)

Supervisor: Prof. Dr. ir. Emanuël Habets

Advisor: Dr. Youssef El Baba

AudioLabs Erlangen (Joint Institute of the University of Erlangen-Nürnberg and Fraunhofer IIS)

---

### Aalto University  
*(Ph.D. Studies)*

Grades are on a scale from 1 to 5, with 5 being the best grade.

- Coding Virtual Worlds (5/5)  
- Deep Learning (5/5)  
- Kernel Methods in Machine Learning (5/5)  
- Machine Learning for Mobile and Pervasive Systems (5/5)  
- Machine Learning with Python (5/5)  
- Machine Learning: Supervised Methods (5/5)  
- Virtual Acoustics (5/5)

#### PhD Thesis
[**Spatial post-filtering for speech enhancement and source separation**](https://aaltodoc.aalto.fi/items/36f91973-b85b-4861-b91c-c12d71afe219)


**Abstract**
Microphone arrays with limited spatial resolution, such as compact and low-order configurations, present challenges for spatial audio processing tasks including sound source separation and interference suppression. Traditional beamforming methods alone may lack the robustness and adaptability required for practical audio scenarios, particularly under constrained sensor arrangements. Further, despite advancements in spatial audio, most common spatial recording devices only utilize low-order, often first-order, directional signals. This thesis addresses these challenges by developing spatial post-filtering techniques inspired by the Cross-Pattern Coherence (CroPaC) algorithm, aiming to enhance the performance of omnidirectional and low-order directional microphone arrays.  

First, we formulate a CroPaC-based post-filter estimated from low-order beamformer outputs. Even when the array departs from ideal geometric assumptions, simulations in multi-speaker conditions demonstrate consistent suppression of interference and background noise. Second, we investigate a space-domain variant (SD-CroPaC) for linear arrays with a focus on speech enhancement. Using single- and dual-line uniform linear arrays (ULAs), common beamforming ambiguities (e.g., front–back) can be suppressed. A combination that uses two post-filters yields stronger separation than either filter alone while preserving target speech.  

Third, building on these insights, we propose a non-linear combination strategy that optimizes the merging of multiple CroPaC post-filters estimated from low-order directional signals. This approach improves spatial selectivity and hence interferer suppression, and outperforms a higher-order CroPaC baseline under the same conditions. Finally, we generalize coherence-driven post-filtering to distributed omnidirectional microphones by introducing aggregated pairwise similarity measures. This results in a soft mask that remains effective when sensors are spatially separated, with positional errors, and in a reverberant acoustic environment.  

Collectively, these contributions significantly advance spatial audio processing techniques, providing robust and practical solutions to improve spatial selectivity and interference suppression capabilities of low-order and distributed microphone array systems, with applications to portable recorders, headsets, smartphones, and distributed omnidirectional microphone systems.

Supervisor: Prof. Ville Pulkki

Aalto Acoustic Labs, Department of Information and Communication Engineering, Aalto University 

--- 
