---
layout: default
title: Research
permalink: /research/
---

# Research Contributions

**Focus:** Computer Vision, Scientific Automation

---

## Smart Automated Data Collection - Cryo-EM Imaging for Drug Development (2020-2021)

### University of British Columbia - Program in Cryo-EM

**Project:** Cryo-Electron Microscopy is used to generate high-quality 3D reconstructions of virus molecules in the process of developing therapeutics. The 3D reconstruction requires large amounts of high-resolution images of individual molecules, which are obtained by navigating the physical microscope to find rare, high-quality sample regions. The manual process starting with low-resolution scans and iteratively selecting sample regions for focused imaging - is a bottleneck which would historically consume hundreds of operator hours. The project aimed to replace human intuition and operating with a computer vision-based pipeline to predict high-resolution quality from low-resolution "Atlas" scans, thus providing a missing link in automating the lab's data collection workflow.

**Stack:** PyTorch, ResNet18, VGG-16, OpenCV, NumPy

### Research Enabled:

The papers below describe advances made by the UBC lab in the rapid, time-sensitive study of SARS-CoV-2 (COVID-19) variants. The pipeline I built to automate the "Atlas-to-Target" decision process removed a significant data collection bottleneck. This helped **accelerate the experimental timeline** toward results and publication, contributing to the rapid response capability for which these studies are recognized.

_**Disclaimer:** I am not a co-author on the biological findings. My contribution was engineering infrastructure that enabled the high-throughput data acquisition required for these studies._

<br>

[*SARS-CoV-2 Omicron variant: Antibody evasion and cryo-EM structure of spike protein–ACE2 complex*](https://www.science.org/doi/10.1126/science.abn7760) \
**Authors:** D Mannar, J Saville, X Zhu, S Srivastava, A Berezuk, K Tuttle, A Marquez, I Sekirov, S Subramaniam \
**Journal:** *Science* (2022)

<br>

[*Structural and biochemical rationale for enhanced spike protein fitness in delta and kappa SARS-CoV-2 variants* ](https://www.nature.com/articles/s41467-022-28324-6) \
**Authors:** J Saville, D Mannar, X Zhu, S Srivastava, A Berezuk, J Demers, S Zhou, K Tuttle, I Sekirov, A Kim, W Li, D Dimitrov, S Subramaniam \
**Journal:** *Nature Communications* (2022)

### System Architecture

<div class="mermaid">
graph LR
    A[Input: Low-Res Atlas] --> B(PyTorch CNN)
    B --> C{Quality Heatmap}
    C -->|Deterministic Policy| D[Microscope Coordinates]
    D --> E[High-Res Acquisition]
    style C fill:#f9f,stroke:#333,stroke-width:2px
</div>

