---
title: "ML-Powered Medical Diagnostics (FDA Class II)"
description: "Computer vision and ML pipeline for a point-of-care diagnostic device — patent granted, published in Frontiers in Chemistry"
tags: ["Computer Vision", "Healthcare", "ML", "FDA"]
weight: 6
---

At HueDx (formerly Group K Diagnostics), I led the data science function for one of the first ML-powered point-of-care colorimetric diagnostic devices—a Class II FDA-regulated product designed to work without laboratory infrastructure.

## The Problem

Diagnosing liver, renal, metabolic, and cardiac conditions typically requires lab equipment costing tens of thousands of dollars and trained technicians. In resource-limited clinical settings—rural clinics, field hospitals, developing regions—this infrastructure simply doesn't exist. The goal was to build a diagnostic system that uses only a smartphone and a paper-based test strip.

## What I Built

The system uses smartphone imaging and machine learning to quantify biomarker concentrations from paper-based microfluidic test strips:

**Image processing (OpenCV):** Noise removal via dilation and smoothing filters, boundary detection to identify diagnostic chamber contours, and morphological shape analysis that fits polygons to boundary points—allowing analysis of devices with varying geometries without preprogrammed shape templates.

**Color quantification:** Pixel clustering by color value, median RGB computation, and HEX conversion to extract raw colorimetric readings from each diagnostic chamber.

**ML models:** Linear and ridge regression models that map color intensities to analyte concentrations for bilirubin, AST, ALT, alkaline phosphatase, creatinine, BUN, glucose, cholesterol, and other biomarkers.

All development followed FDA 510(k) regulatory constraints. I built production-grade data collection, preprocessing, and model validation workflows ensuring clinical safety across iterative product releases, and collaborated directly with the R&D team to translate clinical requirements into ML system design.

## Outcomes

- **Granted patent:** [WO2022/159570](https://patents.google.com/patent/WO2022159570A1/en) — Microfluidic Devices and Rapid Processing Thereof
- **Published:** [A Low-Cost Paper-Based Device for Colorimetric Quantification of Bilirubin](https://www.frontiersin.org/articles/10.3389/fchem.2022.707689/full) — Frontiers in Chemistry, 2022
- Device submitted for FDA review as the KromaHealth Kit

## Tech Stack

OpenCV, computer vision, ML regression models, Python, FDA 510(k), smartphone imaging
