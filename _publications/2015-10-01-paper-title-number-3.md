---
title: "Marginal Benefit Induced Unsupervised Environment Design"
collection: Preprint
permalink: https://arxiv.org/pdf/2302.02119.pdf
excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2023
venue: 'Journal 1'
paperurl: '[download the PDF here.](https://arxiv.org/pdf/2302.02119.pdf)'
citation: '@article{li2023diversity,
  title={Diversity Induced Environment Design via Self-Play},
  author={Li, Dexun and Li, Wenjun and Varakantham, Pradeep},
  journal={arXiv preprint arXiv:2302.02119},
  year={2023}
}'
---
Training generally capable Reinforcement Learning agents in complex environments is a challenging task that involves designing appropriate distributions of environments. Recent research has highlighted the potential of the Unsupervised Environment Design framework, which generates environment instances/levels at the frontier of the agent’s capabilities through adaptive curriculum learning using regret-based measures. While regret-based approaches have shown great promise in generating feasible environments, they can produce difficult environments that are challenging for an RL agent to learn from. This is because regret represents the best-case learning potential of an environment, without indicating how much the agent can actually learn from it. To address this limitation, we propose an alternative objective that employs marginal benefit, focusing on the improvement in the agent policy associated with the environment. This new objective is agent-focused and ensures that the environment is generated at a suitable pace for the agent's learning, resulting in rapid convergence. More importantly, we provide a closed-loop controlled environment generation approach that employs the Marginal Benefit and a new notion of environment diversity to improve the generalizability of the agent. Finally, we provide detailed experimental results and ablation analysis to showcase the effectiveness of our new methods.

[Download paper here](http://academicpages.github.io/files/paper3.pdf)

Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3).
