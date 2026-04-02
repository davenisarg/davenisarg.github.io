---
title: "ML-Powered Medical Diagnostics (FDA Class II)"
description: "Computer vision pipeline for point-of-care diagnostic device with patent and publication"
tags: ["Computer Vision", "Healthcare", "Production ML"]
weight: 6
---

Built the core data science pipeline for a point-of-care colorimetric diagnostic device at HueDx (Group K Diagnostics).

The system uses smartphone imaging and machine learning to quantify biomarker concentrations from paper-based microfluidic test strips. The image processing pipeline (OpenCV) handles noise removal, boundary detection, and morphological shape analysis. ML models convert color intensity readings into analyte concentrations for liver, renal, metabolic, and cardiac markers.

Designed to work without lab infrastructure in resource-limited clinical settings. All development followed FDA 510(k) regulatory constraints.

**Outcomes:**
- Granted patent: [WO2022/159570](https://patents.google.com/patent/WO2022159570A1/en)
- Published: [Frontiers in Chemistry, 2022](https://www.frontiersin.org/articles/10.3389/fchem.2022.707689/full)

**Tech:** OpenCV, computer vision, ML regression models, FDA 510(k), smartphone imaging
