---
layout: page
title: Research
permalink: /research/
---

# Research Contributions

**Focus:** Computer Vision, Scientific Automation

---

## 🔬 Technical Deep Dive: Automated Cryo-EM Targeting

**Project:** Deep Learning for High-Throughput Microscope Guidance (2020–2021)  
**Stack:** PyTorch (`torch.nn`, `torchvision`, `torch.utils.data`), OpenCV, NumPy

### The Challenge
Cryo-EM data collection requires navigating a physical microscope to find rare, high-quality sample regions. Manual selection is a bottleneck. My goal was to replace human intuition with a computer vision model that could predict high-resolution quality from low-resolution "Atlas" scans.

### System Architecture

```mermaid
graph LR
    A[Input: Low-Res Atlas] --> B(PyTorch CNN)
    B --> C{Quality Heatmap}
    C -->|Deterministic Policy| D[Microscope Coordinates]
    D --> E[High-Res Acquisition]
    style C fill:#f9f,stroke:#333,stroke-width:2px
```