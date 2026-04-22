---
title: "EmbodiedBrain: Expanding Performance Boundaries of Task Planning for Embodied Intelligence"
collection: publications
category: manuscripts
permalink: /publications/embodiedbrain/
venue: "arXiv"
date: 2025-10-01
authors: "Ding Zou, Feng Wang, Ming Ge, Shuo Fan, Zhiqiang Zhang, Weinan Chen, Lingfeng Wang, Zhihao Hu, Wentao Yan, et al."
citation: "Ding Zou et al. EmbodiedBrain: Expanding Performance Boundaries of Task Planning for Embodied Intelligence. arXiv:2510.20578."
---
We present **EmbodiedBrain**, a large-scale embodied planning model trained with multimodal post-training and reinforcement learning.

EmbodiedBrain is built upon Qwen2.5VL-7B and 32B backbones and targets long-horizon task planning for embodied intelligence. We construct large-scale post-training datasets with **235k SFT samples** and **118k RL samples**, and propose **Step-GRPO**, an improved policy optimization algorithm tailored for long-horizon planning tasks.

A comprehensive evaluation framework is established, covering:
- Multimodal general capability benchmarks
- Static embodied planning benchmarks
- Simulation-based evaluation with AI2Thor

EmbodiedBrain significantly outperforms RoboBrain2.0 across multimodal reasoning, spatial perception, and task planning benchmarks.

The paper and codebase are publicly released.
