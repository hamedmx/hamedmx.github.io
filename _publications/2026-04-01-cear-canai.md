---
title: "CEAR: Certified Ensemble Adversarial Robustness in DNNs"
collection: publications
category: conferences
permalink: /publication/2026-cear-canai
excerpt: "An ensemble-based robust method that utilizes a hybrid of empirical and certified defense mechanisms."
date: 2026-04-01
venue: "Proceedings of the Canadian Conference on Artificial Intelligence (Canadian AI)"
paperurl: ""
status: "Accepted to appear in the Proceedings of Canadian conference on Artificial Intelligence"
citation: 'Sadig, D., Maleki, M., Karimi, H., & Samavi, R. (2026). “CEAR: Certified Ensemble Adversarial Robustness in DNNs.” Accepted to be published in the 39th Canadian Conference on Artificial Intelligence (Canadian AI 2026).'
---

<div class="justify-text">
Deep Neural Networks (DNNs) are highly susceptible to adversarial perturbations, leading to extensive research on robustness for safety-critical applications. State-of-the-art empirical defense mechanisms improve the robustness of DNNs through the training phase, but still struggle against adaptive white-box attacks. On the other hand, certified defenses offer provable guarantees of robustness within a specified perturbation bound. These guarantees hold regardless of the level of perturbations, even if the attacker is given full knowledge of the model. In this paper, we propose CEAR, an ensemble-based robust method that utilizes a hybrid of empirical and certified defense mechanisms. CEAR trains each network within the ensemble using varying Gaussian noise and temperatures to obfuscate gradients and logits, making the model more resistant to stronger gradient-based attacks. We then use noisy logits and propose two different voting mechanisms to further improve robustness. Furthermore, we extend randomized smoothing to verify the robustness of ensemble-based classifiers. Our experimental evaluations on MNIST, CIFAR10, and TinyImageNet datasets demonstrate superior certified accuracy on average, increased robustness radius, and decreased transferability compared to baseline methods.
</div>
<br><br>
