---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi👋! I am a fourth-year PhD student in Computer and Information Science at the University of Pennsylvania, advised by Prof. [Dan Roth](https://www.cis.upenn.edu/~danroth/), and currently a research intern at Meta. I received my Master's degree in Economics and Computer Science from Duke University, advised by Prof. [Sam Wiseman](https://swiseman.github.io/). Before that, I graduated from Renmin University of China (RUC) with a major in Mathematics and Applied Mathematics and a minor in Computer Science, where I worked with Prof. [Jing Zhang](https://scholar.google.com/citations?user=T7Wa3GQAAAAJ&hl=en) and Prof. [Xin Zhao](https://scholar.google.com/citations?hl=en&user=JNhNacoAAAAJ&view_op=list_works&sortby=pubdate).

My research goal is to build LLM systems that are **reliable**:

* **Reliable reasoning with symbolic tools.** I combine the flexibility of LLMs with the reliability and verifiability of symbolic tools (solvers, probabilistic programs, and formal verification) so that systems reason, plan, and make decisions consistently. Examples include Bayesian inference for trustworthy decision probabilities ([BIRD](https://openreview.net/forum?id=fAAaT826Vv)), solver-based verification of chain-of-thought ([VeriCoT](https://openreview.net/pdf?id=zHuV3Vatov)), treating chain-of-thought as tractable probabilistic programs ([Copper](https://openreview.net/forum?id=j1wLo06bmx)), multi-agent uncertainty estimation for black-box LLMs ([DiverseAgentEntropy](https://aclanthology.org/2025.findings-emnlp.660/)), and showing that the gains from tool-augmented reasoning come mainly from reliable execution rather than from writing reasoning as code ([Is Code Better Than Language?](https://arxiv.org/abs/2606.15589)).

* **Reliable agents.** I study agents that proactively gather information, reason over evidence, and act safely under uncertainty. This includes training agents to discover reusable abstractions, skills, and computational structure instead of memorizing task-specific solutions([ReuseRL](https://arxiv.org/abs/2605.31509)), diagnosing search agents' process through evidential query graphs ([SearchAtlas](https://arxiv.org/abs/2609.10901)), evaluating whether agents recognize risks and act on them ([AURA-Eval](https://arxiv.org/abs/2609.06783)).
  
📑 Selected Research Projects
------
[CoTs as Tractable Probabilistic Programs](https://openreview.net/forum?id=j1wLo06bmx)  <br>
Kyle Richardson *, **Yu Feng** *, Poorva Garg, Junyan Cheng, Guy Van den Broeck, Dan Roth  <br>
NeurIPS 2026; * equal contribution; earlier version at the 9th Workshop on Tractable Probabilistic Modeling (TPM 2026)

[VeriCoT: Neuro-symbolic Chain-of-Thought Validation via Logical Consistency Checks](https://openreview.net/pdf?id=zHuV3Vatov) <br>
**Yu Feng**, Nathaniel Weir, Kaj Bostrom, Sam Bayless, Darion Cassel, Sapana Chaudhary, Benjamin Kiesl-Reiter, Huzefa Rangwala<br>
ICLR 2026

[BIRD: A Trustworthy Bayesian Inference Framework for Large Language Models](https://openreview.net/forum?id=fAAaT826Vv) <br>
**Yu Feng**, Ben Zhou, Weidong Lin, Dan Roth<br>
ICLR 2025 (Oral)

[Skill Reuse as Compression in Agentic RL](https://arxiv.org/abs/2605.31509)<br>
Zhikun Xu, **Yu Feng**, Jacob Dineen, Taiwei Shi, Jieyu Zhao, Ben Zhou<br>
EMNLP 2026 (Main)

[Is Code Better Than Language for Algorithmic Reasoning?](https://arxiv.org/abs/2606.15589) <br>
Terry Tong, **Yu Feng**, Surbhi Goel, Dan Roth <br>
ICML 2026

[Rethinking LLM Uncertainty: A Multi-Agent Approach to Estimating Black-Box Model Uncertainty](https://arxiv.org/pdf/2412.09572) <br>
**Yu Feng**, Phu Mon Htut, Zheng Qi, Wei Xiao, Manuel Mager, Nikolaos Pappas, Kishaloy Halder, Yang Li, Yassine Benajiba, Dan Roth <br>
EMNLP 2025 (Findings)

[BLINK: Multimodal Large Language Models Can See but Not Perceive](https://arxiv.org/pdf/2404.12390) <br>
Xingyu Fu*, Yushi Hu*, Bangzheng Li, **Yu Feng**, Haoyu Wang, Xudong Lin, Dan Roth, Noah A. Smith, Wei-Chiu Ma, Ranjay Krishna <br>
ECCV 2024
