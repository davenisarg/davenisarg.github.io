---
title: "GenAI-Powered IVR for Claims Automation"
description: "End-to-end Generative AI system automating insurance claims processing, saving $5-10M/year"
tags: ["GenAI", "LLMs", "NLP", "Conversational AI", "Production ML"]
weight: 1
---

At Asurion, I architected a Generative AI-powered Interactive Voice Response system that automates insurance claims processing from intake through resolution—no human in the loop.

## The Problem

Claims processing at Asurion's scale meant thousands of daily calls routed through human agents for intake, classification, and resolution. Each call carried labor costs, wait times, and inconsistent handling across service channels.

## What I Built

The system uses fine-tuned large language models and NLP to understand customer intent in real time, classify claim types, extract relevant policy and device information, and either resolve the claim automatically or route it to the appropriate specialist. The architecture supports multi-turn conversations, handling edge cases like ambiguous claims or missing information through structured follow-up prompts.

I designed the system for multi-tenant SaaS deployment from the ground up, enabling rapid onboarding of enterprise clients. Each tenant gets customized claim flows, terminology, and routing logic without requiring separate model instances.

## Impact

- **$5-10M in annual operating cost reduction**
- Now serving enterprise clients including **Amazon** and **McAfee**
- End-to-end automation from claim intake through resolution
- Multi-tenant architecture enabling rapid client onboarding

## Tech Stack

LLM fine-tuning (LoRA), NLP, real-time inference, multi-tenant SaaS architecture, AWS
