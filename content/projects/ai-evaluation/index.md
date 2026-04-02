---
title: "AI Evaluation and Feedback System"
description: "Closed-loop evaluation framework for production AI systems"
tags: ["MLOps", "Evaluation", "Production ML"]
weight: 2
---

Designed and built an evaluation framework for Asurion's IVR and other production AI systems.

The system captures live interaction data, scores model outputs against quality benchmarks, and feeds structured signals back into the training pipeline. Instead of periodic manual reviews, the framework creates a closed loop where production performance data directly informs retraining priorities.

This lets the team catch degradation patterns early, measure the impact of model updates before full rollout, and systematically improve AI quality over time. The system is generalizable across any AI-powered workflow, not just the IVR.

**Tech:** Python, evaluation pipelines, model monitoring, feedback loops
