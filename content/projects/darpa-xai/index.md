---
title: "DARPA Explainable AI (XAI)"
description: "Interpretable deep learning for high-stakes image recognition under DARPA/U.S. Department of Defense"
tags: ["Explainable AI", "Deep Learning", "Research", "DARPA"]
weight: 7
---

As a Research Scientist at Michigan Technological University, I worked on DARPA's Explainable AI (XAI) program—a U.S. Department of Defense initiative focused on making deep learning models interpretable for high-stakes deployment.

## The Problem

Deep neural networks achieve impressive accuracy on benchmarks but operate as black boxes. In defense and safety-critical applications, a model that says "96% confident this is a tank" is useless if no one can understand *why* it made that classification. DARPA's XAI program aimed to build AI systems whose decisions humans can understand, trust, and effectively manage.

## What I Did

**Model development:** Retrained Google's Inception classifier and developed CNN architectures using GoogLeNet, AlexNet, ResNet-51, and ResNet-101 on ImageNet, achieving 96-98% top-5 accuracy. All training ran on HPC infrastructure with automated workflows and transfer learning.

**Interpretability research:** Investigated Choquet Integral-based computational intelligence methods to generate human-interpretable explanations for model predictions—moving beyond saliency maps toward mathematically grounded explanation frameworks.

**Robustness analysis:** Studied how deep image classifiers fail under real-world input variations. Showed that standard classifiers degrade significantly under image transformations (shape, size, orientation) that are trivial for humans. Ran parallel behavioral experiments with human subjects on the same tasks to quantify the human-machine performance gap.

## Outcomes

- **Published:** [The Unreasonable Ineptitude of Deep Image Classification Networks](https://github.com/davenisarg/unreasonable) — 35th ICML Workshop
- **Advisor:** Dr. Timothy Havens, Director of ICC Data Sciences at Michigan Tech

## Tech Stack

TensorFlow, CNNs (GoogLeNet, ResNet-51, ResNet-101, AlexNet), HPC infrastructure, transfer learning, ImageNet
