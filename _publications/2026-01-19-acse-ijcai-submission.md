<!--
---
title: "LLMs Uncertainty Quantification via Adaptive Conformal Semantic Entropy"
collection: publications
category: manuscripts
permalink: /publication/2026-acse-ijcai-submission
excerpt: "Under review (IJCAI 2026): Adaptive semantic entropy for reliable LLM prompt-level uncertainty and response-level prediction sets."
date: 2026-01-19
venue: "Submission: The 35th International Joint Conference on Artificial Intelligence (IJCAI)"
status: "Under Review"
note: "Manuscript ID: 7054; available upon request."
citation: 'Karimi, H., Meyappan, V., & Samavi, R. (2026). “LLMs Uncertainty Quantification via Adaptive Conformal Semantic Entropy.” Submitted to the 35th International Joint Conference on Artificial Intelligence (IJCAI 2026), under review.'
---


<div class="justify-text">
LLMs' overconfidence, particularly when hallucinating, poses a significant challenge for the deployment of the models in safety-critical settings and makes a reliable estimation of uncertainty necessary. Existing approaches for uncertainty quantification typically prioritize lexical or probabilistic measures; however, these techniques often ignore the semantic variance of different responses with similar meaning. In this paper, we propose Adaptive Conformal Semantic Entropy (ACSE), a method for estimating prompt-level uncertainty by adaptively measuring semantic dispersion in LLMs outputs. 
Our uncertainty scoring function is based on clustering semantic entropy of multiple diverse responses to the same prompt. The function adaptively adjusts the uncertainty score based on semantic features of each cluster. To ensure statistical reliability of our score, we use conformal calibration to apply a decision rule to accept/abstain the prompts, providing a finite-sample, distribution-free guarantee such that the error rate among the accepted responses remains bounded by a user-specified tolerance. Our extensive experimental evaluations using different LLMs and datasets, demonstrate that our approach consistently outperforms state-of-the-art uncertainty quantification baselines using discriminative performance, conformal guarantees, and probabilistic calibration indicators. As a highlight, for TriviaQA dataset, AUROC of our approach is $0.88$ compared to $0.65$ produced by the token entropy approach. 
</div>
<br><br>

-->
