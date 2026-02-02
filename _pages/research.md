---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<div class="justify-text">
My research focuses on <i>trustworthy AI and machine learning</i> with an emphasis on <i>uncertainty quantification</i>, <i>conformal prediction and risk control (distribution-free reliability guarantees)</i>, <i>evidential deep learning</i>, and <i>robust machine learning</i>. I develop methods that provide reliable decision-making signals such as prediction sets, abstention rules, calibrated uncertainty measures, and OOD scoring, for deep models through optimization and/or post-hoc techniques in classification, medical imaging, and language models.
</div>

### Research Themes
- Conformal prediction and risk control
- Evidential/Bayesian deep learning for epistemic uncertainty
- OOD detection and robustness
- Uncertainty in large language models (LLMs)

### Selected Ongoing Projects
- Spatially-adaptive conformal prediction for medical image segmentation
- Evidential OOD detection using misclassification cost through information-theoretic regularization
- Adaptive conformal semantic entropy for LLM uncertainty calibration
- Adaptive conformal risk control in LLMs

## Research Experience

### Evidential Out-of-Distribution Detection Using Misclassification Cost and Information-Theoretic Regularization
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Winter 2025 – Present</em></span>
</div>

Developing an evidential OOD detection framework for deep classifiers by introducing a <i>class-wise misclassification cost</i> and evidential regularizer that reshape evidence allocation during training. The method uses a <i>two-factor OOD score</i> combining evidence scarcity and class conflict at inference, with theoretical analysis linking regularizer gradients to evidence dynamics and improved ID–OOD separability.


### Uncertainty Quantification in Language Models Using Adaptive Conformal Semantic Entropy
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Fall 2025 – Winter 2026</em></span>
</div>

Designed an adaptive <i>Semantic Entropy</i> framework that estimates LLM uncertainty using dispersion of sentence embeddings over clustered generations, then <i>inflates/adjusts uncertainty</i> to improve conservativeness and mitigate hallucinations. The approach applies <i>conformal calibration</i> to obtain distribution-free, guaranteed <i>prompt-level accept/abstain** decisions and <i>response-level prediction sets</i>.<br><i>Ongoing work includes guaranteed risk control for generative tasks.</i>

  
### HEAR: Hybrid Ensemble Adversarial Robustness in Neural Networks
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Summer 2025 – Present</em></span>
</div>

Proposing a hybrid ensemble defense combining variable Gaussian augmentation and temperature-scaled distillation with noisy logits and a robust weighted ensemble at inference. Extends randomized smoothing to ensembles to improve certified accuracy, robustness radius, and resistance to strong white-box attacks on image classification benchmarks.


### SACP: Spatially-Adaptive Conformal Prediction in Uncertainty Quantification of Medical Image Segmentation
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Fall 2024 – Summer 2025</em></span>
</div>
<div class="justify-text">
Developed a spatially-adaptive conformal prediction framework for medical image segmentation that augments standard CP with class-conditional calibration and distance-weighted nonconformity scores. Produces anatomically informed prediction sets that expand near critical tumor–vessel interfaces while preserving finite-sample coverage guarantees across multi-centre pancreatic tumor datasets.
</div>

### Model Uncertainty Quantification in Deep Neural Networks Using Evidential Properties and Conformal Prediction
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Fall 2023 – Fall 2024</em></span>
</div>
<div class="justify-text">
Designed conformal nonconformity scores that incorporate evidential and information-theoretic properties to quantify model (epistemic) uncertainty in deep classifiers. Generates adaptive prediction sets while maintaining empirical coverage of the ground truth.<br><i>Ongoing direction includes conformal risk control for deployment</i>.
</div>

### Certified Robustness in Deep Neural Networks Using Diverse Ensemble and Noisy Logits
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Winter 2024</em></span>
</div>
<div class="justify-text">
Proposed a two-phase training method: train architecturally diversified models individually, then train the ensemble with a diversity-promoting loss. Combined with noise injection at inference, this improves resistance to adversarial attacks while maintaining reasonable accuracy.
</div>

### Quantifying Deep Learning Model Uncertainty in Conformal Prediction
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Spring – Summer 2023</em></span>
</div>
<div class="justify-text">
Proposed a probabilistic approach to quantify model uncertainty derived from conformal prediction sets and provided certified bounds for the computed uncertainty, enabling comparisons between CP-based uncertainty and other uncertainty quantification methods.
</div>

### Evidence-based Model Predictive Confidence in Deep Classifiers
<div class="cv-meta">
  <span class="where"><strong>Toronto Metropolitan University (TAILab), Toronto, ON, Canada</strong></span>
  <span class="when"><em>Winter 2021 – 2022</em></span>
</div>
<div class="justify-text">
Developed a method grounded in Dempster–Shafer theory of evidence and Subjective Logic to quantify predictive confidence by separating uncertainty due to ambiguous/conflicting information from uncertainty due to lack of sufficient information.
</div>

### Ontology Alignment Using Word/Sentence Embedding Methods (M.Sc. Thesis)
<div class="cv-meta">
  <span class="where"><strong>University of Tehran, Tehran, Iran</strong></span>
  <span class="when"><em>Winter 2019 – Summer 2020</em></span>
</div>
<div class="justify-text">
Proposed an approach to discover valid mappings between biomedical ontologies using Word2Vec-based representations and semantic similarity (Maximum Matching), combined with retrofitting using WordNet to improve alignment quality.
</div>

### A Learning-based Approach for Ontology Alignment Using Inductive Logic Programming (ILP)
<div class="cv-meta">
  <span class="where"><strong>University of Tehran, Tehran, Iran</strong></span>
  <span class="when"><em>Fall 2017 – 2018</em></span>
</div>
<div class="justify-text">
Developed an ontology mapping method based on Inductive Logic Programming (ILP): interpret OWL ontologies into first-order logic predicates, then apply inductive reasoning with background knowledge to discover hidden rules and propose valid alignments via structural similarities.
</div>

### Implementing YAD: An Inductive Logic Programming Tool
<div class="cv-meta">
  <span class="where"><strong>University of Tehran, Tehran, Iran</strong></span>
  <span class="when"><em>Summer 2018</em></span>
</div>
<div class="justify-text">
Implemented an ILP tool for multidimensional and multi-tabular learning using first-order logic representations of positive/negative examples to discover rules and relations.
</div>

### Reinforcement Learning Approach in Multi-Agent Systems Based on Cooperation (B.Sc. Final Project)
<div class="cv-meta">
  <span class="where"><strong>Shahid Beheshti University, Tehran, Iran</strong></span>
  <span class="when"><em>Summer 2016</em></span>
</div>
<div class="justify-text">
Studied cooperative multi-agent reinforcement learning and proposed an RL-based approach in the problem space (beyond the optimal point), analyzing performance and efficiency tradeoffs.
</div>



