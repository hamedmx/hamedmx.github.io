---
layout: archive
title: "Research Activities"
permalink: /research/
author_profile: true
---

My research focuses on **trustworthy AI and machine learning** with an emphasis on **uncertainty quantification**, **conformal prediction and risk control (distribution-free reliability guarantees)**, **evidential deep learning**, and **robust machine learning**. I develop methods that provide reliable decision-making signals such as prediction sets, abstention rules, calibrated uncertainty measures, and OOD scoring, for deep models through optimization and/or post-hoc techniques in classification, medical imaging, and language models.

### Themes
- Conformal prediction & risk control
- Evidential/Bayesian deep learning for epistemic uncertainty
- OOD detection & robustness
- Uncertainty in large language models (LLMs)

### Ongoing Projects (selected)
- Spatially-adaptive conformal prediction for medical image segmentation
- Evidential OOD detection using misclassification cost through information-theoretic regularization
- Adaptive conformal semantic entropy for LLM uncertainty calibration
- Adaptive conformal risk control in LLMs


## Research Experience

### Evidential Out-of-Distribution Detection Using Misclassification Cost and Information-Theoretic Regularization  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Winter 2025 – Present*  
Developing an evidential OOD detection framework for deep classifiers by introducing a **class-wise misclassification cost** and evidential regularizer that reshape evidence allocation during training. The method uses a **two-factor OOD score** combining evidence scarcity and class conflict at inference, with theoretical analysis linking regularizer gradients to evidence dynamics and improved ID–OOD separability.

### Uncertainty Quantification in Language Models Using Adaptive Conformal Semantic Entropy  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Fall 2025 – Winter 2026*  
Designed an adaptive **Semantic Entropy** framework that estimates LLM uncertainty using dispersion of sentence embeddings over clustered generations, then **inflates/adjusts uncertainty** to improve conservativeness and mitigate hallucinations. The approach applies **conformal calibration** to obtain distribution-free, guaranteed **prompt-level accept/abstain** decisions and **response-level prediction sets**. (Ongoing work includes guaranteed risk control for generative tasks.)

### HEAR: Hybrid Ensemble Adversarial Robustness in Neural Networks  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Summer 2025 – Present*  
Proposing a hybrid ensemble defense combining variable Gaussian augmentation and temperature-scaled distillation with noisy logits and a robust weighted ensemble at inference. Extends randomized smoothing to ensembles to improve certified accuracy, robustness radius, and resistance to strong white-box attacks on image classification benchmarks.

### SACP: Spatially-Adaptive Conformal Prediction in Uncertainty Quantification of Medical Image Segmentation  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Fall 2024 – Summer 2025*  
Developed a spatially-adaptive conformal prediction framework for medical image segmentation that augments standard CP with class-conditional calibration and distance-weighted nonconformity scores. Produces anatomically informed prediction sets that expand near critical tumor–vessel interfaces while preserving finite-sample coverage guarantees across multi-centre pancreatic tumor datasets.

### Model Uncertainty Quantification in Deep Neural Networks Using Evidential Properties and Conformal Prediction  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Fall 2023 – Fall 2024*  
Designed conformal nonconformity scores that incorporate evidential and information-theoretic properties to quantify model (epistemic) uncertainty in deep classifiers. Generates adaptive prediction sets while maintaining empirical coverage of the ground truth; ongoing direction includes conformal risk control for deployment.

### Certified Robustness in Deep Neural Networks Using Diverse Ensemble and Noisy Logits  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Winter 2024*  
Proposed a two-phase training method: train architecturally diversified models individually, then train the ensemble with a diversity-promoting loss. Combined with noise injection at inference, this improves resistance to adversarial attacks while maintaining reasonable accuracy.

### Quantifying Deep Learning Model Uncertainty in Conformal Prediction  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Spring – Summer 2023*  
Proposed a probabilistic approach to quantify model uncertainty derived from conformal prediction sets and provided certified bounds for the computed uncertainty, enabling comparisons between CP-based uncertainty and other uncertainty quantification methods.

### Evidence-based Model Predictive Confidence in Deep Classifiers  
**Toronto Metropolitan University (TAILab), Toronto, ON, Canada** — *Winter 2021 – 2022*  
Developed a method grounded in Dempster–Shafer theory of evidence and Subjective Logic to quantify predictive confidence by separating uncertainty due to ambiguous/conflicting information from uncertainty due to lack of sufficient information.

### Ontology Alignment Using Word/Sentence Embedding Methods (M.Sc. Thesis)  
**University of Tehran, Tehran, Iran** — *Winter 2019 – Summer 2020*  
Proposed an approach to discover valid mappings between biomedical ontologies using Word2Vec-based representations and semantic similarity (Maximum Matching), combined with retrofitting using WordNet to improve alignment quality.

### A Learning-based Approach for Ontology Alignment Using Inductive Logic Programming (ILP)  
**University of Tehran, Tehran, Iran** — *Fall 2017 – 2018*  
Developed an ontology mapping method based on Inductive Logic Programming (ILP): interpret OWL ontologies into first-order logic predicates, then apply inductive reasoning with background knowledge to discover hidden rules and propose valid alignments via structural similarities.

### Implementing YAD: An Inductive Logic Programming Tool  
**University of Tehran, Tehran, Iran** — *Summer 2018*  
Implemented an ILP tool for multidimensional and multi-tabular learning using first-order logic representations of positive/negative examples to discover rules and relations.

### Reinforcement Learning Approach in Multi-Agent Systems Based on Cooperation (B.Sc. Final Project)  
**Shahid Beheshti University, Tehran, Iran** — *Summer 2016*  
Studied cooperative multi-agent reinforcement learning and proposed an RL-based approach in the problem space (beyond the optimal point), analyzing performance and efficiency tradeoffs.


