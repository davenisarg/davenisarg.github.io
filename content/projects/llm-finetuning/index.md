---
title: "LLM Fine-Tuning and Enterprise AI Prototyping"
description: "Adapting open-source LLMs for enterprise deployments across HP, Amazon, and internal channels"
tags: ["LLMs", "GenAI", "RAG", "Fine-tuning"]
weight: 5
---

At Asurion, I led R&D on adapting open-source large language models for enterprise client use cases—building the technical playbook for how the company evaluates, customizes, and deploys LLMs across its product lines.

## The Problem

Enterprise clients needed AI capabilities tailored to their specific domains, terminology, and workflows. Off-the-shelf models hallucinated on domain-specific questions, lacked context about internal processes, and couldn't be deployed without significant customization.

## What I Built

**Fine-tuning pipeline:** Adapted LLaMA and Mistral models using LoRA and self-instruct pipelines on domain-specific data. This gave each model deep knowledge of client-specific products, policies, and service workflows without the cost of full model retraining.

**Synthetic data generation:** Built workflows to augment limited labeled datasets with high-quality synthetic examples, solving the cold-start problem for new client domains where labeled data was scarce.

**RAG prototypes:** Developed Retrieval-Augmented Generation systems that connect LLMs to internal knowledge bases, grounding responses in actual documentation rather than relying on parametric memory alone.

## Impact

- Delivered working prototypes for **HP**, **Amazon**, and internal service channels
- Established Asurion's technical playbook for LLM evaluation and deployment
- Reduced time-to-prototype for new client LLM use cases

## Tech Stack

LLaMA, Mistral, LoRA, self-instruct pipelines, RAG, synthetic data generation, Hugging Face, AWS
