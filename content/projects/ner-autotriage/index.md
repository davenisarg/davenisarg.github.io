---
title: "NER-Based Auto-Triage for Field Services"
description: "NLP engine automating appliance repair triage across 17 markets, saving 5,900+ expert hours/year"
tags: ["NLP", "NER", "Production ML"]
weight: 3
---

At Asurion, I built an NLP system that automatically triages major appliance repair requests using Named Entity Recognition—removing the bottleneck of mandatory expert review for every incoming request.

## The Problem

Every major appliance repair request required a human expert to read the intake data, identify the product and symptoms, and decide the right repair path. This consumed thousands of expert hours annually and slowed down time-to-repair for customers across 17 markets.

## What I Built

The model extracts structured information from unstructured customer intake data: product details, symptom descriptions, fault indicators, and contextual signals. It then classifies the issue type and recommends the optimal repair path—whether that's dispatching a specific technician specialty, ordering parts in advance, or escalating to a senior expert.

The system handles the full spectrum of major appliance categories and was deployed across all 17 Asurion service markets with market-specific tuning for regional product mixes and service patterns.

## Impact

- **10% of all triage decisions fully automated** (no human touch)
- **First-trip-fix rate improved by 10%** (right diagnosis means right parts on the truck)
- **5,900+ expert-assist hours saved per year**
- **$150K+ in annual cost savings** across 17 markets

## Tech Stack

Named Entity Recognition, NLP pipelines, production deployment, multi-market rollout
