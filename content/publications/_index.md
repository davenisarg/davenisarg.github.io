---
title: "Publications & Patent"
description: "Research publications and intellectual property"
---

## Patent

### Microfluidic Devices and Rapid Processing Thereof
**WO2022/159570 | Issued Jul 28, 2022** | [View Patent](https://patents.google.com/patent/WO2022159570A1/en)

This patent covers a point-of-care diagnostic system that combines paper-based microfluidic devices, a controlled imaging enclosure, and an ML-powered image processing pipeline to quantify biomarkers from biological samples using a smartphone.

A biological sample is deposited onto a microfluidic device with recessed channels and diagnostic chambers. The sample flows via capillary action, reacts with pre-applied reagents, and produces color changes. The device is placed in a viewing box with internal LED lighting that eliminates ambient light for consistent imaging.

The image processing system (OpenCV) applies filters to remove noise, runs boundary detection on diagnostic chambers, and uses morphological shape detection to analyze devices of varying geometries without preprogrammed templates. The system clusters pixels by color, computes median RGB values, and feeds them into regression models that map color intensity to analyte concentration.

Detects liver markers (bilirubin, AST, ALT, alkaline phosphatase), renal markers (creatinine, BUN), metabolic markers (glucose, cholesterol, electrolytes), and cardiac markers (LDH). Designed for resource-limited clinical settings.

I built the core CV/ML pipeline: object detection, morphological shape analysis, color quantification, and the regression models. This work supports the KromaHealth Kit product submitted for FDA review.

---

## Publications

### A Low-Cost Paper-Based Device for the Colorimetric Quantification of Bilirubin in Serum Using Smartphone Technology
**Frontiers in Chemistry | Jul 2022**

Presents the KromaHealth Kit, a paper-based diagnostic device that uses smartphone imaging and machine learning to measure bilirubin concentrations in blood serum. The system captures colorimetric changes on diagnostic paper pads, then applies image processing and ML algorithms to quantify bilirubin levels between 0.5 and 7.0 mg/dl. Testing showed precision comparable to conventional laboratory methods, with stable performance over a six-month evaluation period. Designed as an affordable alternative to standard bilirubin testing for resource-limited clinical settings. Two patent applications were filed and the device was submitted for FDA review.

---

### The Unreasonable Ineptitude of Deep Image Classification Networks
**35th International Machine Learning Conference (ICML) | 2019** | [Code & Data](https://github.com/davenisarg/unreasonable)

Investigates a fundamental gap in deep neural network image classifiers: they fail on image variations that are trivial for humans. We tested state-of-the-art CNNs (GoogLeNet, ResNet) on transformed versions of standard test images, applying changes in shape, size, orientation, and other properties that do not confuse human observers. The models showed significant accuracy degradation under these conditions, despite achieving 96-98% top-5 accuracy on standard benchmarks. We ran parallel behavioral experiments with human subjects on the same classification tasks to quantify the human-machine performance gap. Part of DARPA's Explainable AI program.

---

### Modelling and Performance Analysis of Various CMOS Applications based on Recent Technologies
**IEEE CICN 2015 | Dec 2015**

Analyzes the performance characteristics of CMOS circuit designs across different technology nodes as transistor scaling approaches physical limits. Modeled and simulated various CMOS application circuits at advanced technology nodes to evaluate how shrinking process geometries affect power consumption, speed, and signal integrity. Published at the IEEE International Conference on Computational Intelligence and Communication Networks.

---

### System on Chip
**IJCESR | Apr 2015**

Examines System-on-Chip (SoC) design principles and integration methodologies, covering how processors, memory, and I/O interfaces are integrated onto a single chip to reduce power consumption, cost, and physical footprint. Published in the International Journal of Computer Engineering and Scientific Research.
