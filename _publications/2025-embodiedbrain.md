---
title: "EmbodiedBrain: Expanding Performance Boundaries of Task Planning for Embodied Intelligence"
collection: publications
category: report
permalink: /publication/embodiedbrain
venue: "Technical Report"
date: 2025-01-01
authors: "Ding Zou"
---

We present **EmbodiedBrain**, a large-scale embodied planning model trained with multimodal post-training and reinforcement learning.

EmbodiedBrain is built upon Qwen2.5VL-7B and 32B backbones and targets long-horizon task planning for embodied intelligence. We construct large-scale post-training datasets with **235k SFT samples** and **118k RL samples**, and propose **Step-GRPO**, an improved policy optimization algorithm tailored for long-horizon planning tasks.

A comprehensive evaluation framework is established, covering:
- Multimodal general capability benchmarks
- Static embodied planning benchmarks
- Simulation-based evaluation with AI2Thor

EmbodiedBrain significantly outperforms RoboBrain2.0 across multimodal reasoning, spatial perception, and task planning benchmarks.

The technical report and codebase are publicly released.
