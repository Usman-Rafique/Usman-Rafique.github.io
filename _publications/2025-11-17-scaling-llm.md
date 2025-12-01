---
title: "On the Fundamental Limits of LLMs at Scale"
collection: publications
permalink: /scaling_llm/
excerpt: 'We take a deep dive into the theoretical limits of Large Language Models (LLMs)'
date: 2025-11-17
venue: 'Under Review'
---

![Problem overview](/images/llm_scaling_1.png)

##  &emsp; &emsp; [Paper](https://arxiv.org/abs/2511.12869) &emsp;  &emsp;  [PDF](https://arxiv.org/pdf/2511.12869) 


## Overview
![The Five Interacting Factors](/images/llm_scaling_2.png)

## Abstract
Large Language Models (LLMs) have benefited enormously from scaling, yet these gains are bounded by five fundamental limitations: (1) hallucination, (2) context compression, (3) reasoning degradation, (4) retrieval fragility, and (5) multimodal misalignment. While existing surveys describe these phenomena empirically, they lack a rigorous theoretical synthesis connecting them to the foundational limits of computation, information, and learning. This work closes that gap by presenting a unified, proof-informed framework that formalizes the innate theoretical ceilings of LLM scaling. First, computability and uncomputability imply an irreducible residue of error: for any computably enumerable model family, diagonalization guarantees inputs on which some model must fail, and undecidable queries (e.g., halting-style tasks) induce infinite failure sets for all computable predictors. Second, information-theoretic and statistical constraints bound attainable accuracy even on decidable tasks, finite description length enforces compression error, and long-tail factual knowledge requires prohibitive sample complexity. Third, geometric and computational effects compress long contexts far below their nominal size due to positional under-training, encoding attenuation, and softmax crowding. We further show how likelihood-based training favors pattern completion over inference, how retrieval under token limits suffers from semantic drift and coupling noise, and how multimodal scaling inherits shallow cross-modal alignment. Across sections, we pair theorems and empirical evidence to outline where scaling helps, where it saturates, and where it cannot progress, providing both theoretical foundations and practical mitigation paths like bounded-oracle retrieval, positional curricula, and sparse or hierarchical attention. 

Please refer to [the paper](https://arxiv.org/pdf/2511.12869) for more details.


## Recommended citation

<pre>
@article{mohsin2025fundamental,
  title={On the Fundamental Limits of LLMs at Scale},
  author={Mohsin, Muhammad Ahmed and Umer, Muhammad and Bilal, Ahsan and Memon, Zeeshan and Qadir, Muhammad Ibtsaam and Bhattacharya, Sagnik and Rizwan, Hassan and Gorle, Abhiram R and Kazmi, Maahe Zehra and Mohsin, Ayesha and Rafique, Muhammad Usman and He, Zihao and Mehta, Pulkit and Jamshed, Muhammad Ali Jamshed and Cioffi, John M.},
  journal={arXiv preprint arXiv:2511.12869},
  year={2025}
}
</pre>
