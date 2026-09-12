---
layout: default
title: Research
permalink: /research/
---

# Research & Projects

<div class="projects-container">

  <!-- PROJECT 1: LLM Factuality Geometry -->
  <article class="project-card">
    <div class="project-header">
      <h2 class="project-title">Geometry of Factuality in LLM Internal Representations</h2>
      <span class="project-date">2026</span>
    </div>
    <div class="project-affiliation">
      <i class="fas fa-university"></i> Reichman University • MSc Research
    </div>
    <div class="tag-list">
      <span class="tag">NLP</span>
      <span class="tag">LLM Interpretability</span>
      <span class="tag">Representation Geometry</span>
      <span class="tag">Linear Probing</span>
    </div>
    <div class="project-body">
      <p>
        Investigating how factual statements, misconceptions, and falsehoods are geometrically encoded within the latent activation space of Large Language Models to detect unfaithfulness at inference time.
      </p>
      <strong>Infrastructure:</strong> Engineered versatile experimentation pipelines for parameter sweeps, probe training, activation extraction, and artifact tracking.
      <br>
      <strong>Methodology:</strong> Utilizing tools from linear algebra, high-dimensional geometry, and classical ML to ensure statistical rigor, control confounding features, and cross-validate probe performance across model scales.
      <br>
      <strong>Stack:</strong>
      <span class="tag-list inline">
        <span class="tag">PyTorch</span>
        <span class="tag">Hugging Face</span>
        <span class="tag">NumPy</span>
        <span class="tag">SciPy</span>
        <span class="tag">Scikit-Learn</span>
      </span>
    </div>
    <div class="project-links">
      <a href="https://github.com/lior-krinberg-msc/factgeom" class="project-btn" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i> Code</a>
      <a href="{{ '/assets/docs/factgeom_report.pdf' | relative_url }}" class="project-btn" target="_blank" rel="noopener noreferrer"><i class="fas fa-file-pdf"></i> Report</a>
    </div>
  </article>

  <!-- PROJECT 2: Multi-Task RL -->
  <article class="project-card">
    <div class="project-header">
      <h2 class="project-title">Multi-Task Navigation in Sparse Environments</h2>
      <span class="project-date">2025</span>
    </div>
    <div class="project-affiliation">
      <i class="fas fa-university"></i> Reichman University • MSc Project
    </div>
    <div class="tag-list">
      <span class="tag">Reinforcement Learning</span>
      <span class="tag">Multi-Task Grid World Environments</span>
    </div>
    <div class="project-body">
      <p>
        Designed, trained, and benchmarked RL agents capable of solving challenging multi-task MiniGrid grid-world navigation tasks characterized by extremely sparse reward signals.
      </p>
      <strong>Comparative Analysis:</strong> Conducted controlled experiments contrasting value-based and policy-gradient paradigms: DDQN with Prioritized Experience Replay (PER) vs. Advantage Actor-Critic (A2C) vs. Proximal Policy Optimization (PPO with GAE).
      <br>
      <strong>Dynamics & Optimization:</strong> Evaluated the impact of potential-based reward shaping, entropy regularization, and hyperparameter sweeps on sample efficiency, policy stability, and convergence.
      <br>
      <strong>Stack:</strong>
      <span class="tag-list inline">
        <span class="tag">PyTorch</span>
        <span class="tag">MiniGrid / Gymnasium</span>
        <span class="tag">Weights & Biases</span>
        <span class="tag">NumPy</span>
      </span>
    </div>
    <div class="project-links">
      <a href="https://github.com/shaytanne/runi-reinforcement_learning-final_project" class="project-btn" target="_blank"><i class="fab fa-github"></i> Code</a>
    </div>
  </article>

  <!-- PROJECT 3: Cryo-EM Scientific Automation -->
  <article class="project-card">
    <div class="project-header">
      <h2 class="project-title">Automated Cryo-EM Data Collection for Therapeutics</h2>
      <span class="project-date">2020 – 2021</span>
    </div>
    <div class="project-affiliation">
      <i class="fas fa-university"></i> University of British Columbia
    </div>
    <div class="project-affiliation">
      <i class="fas fa-microscope"></i> Program in Cryo-EM (lab)
    </div>
    <div class="tag-list">
      <span class="tag">Computer Vision</span>
      <span class="tag">Deep Learning</span>
      <span class="tag">Scientific Automation</span>
    </div>
    <div class="project-body">
      <p>
        Cryo-Electron Microscopy produces high-resolution 3D reconstructions of viral proteins for therapeutic drug design. However, navigating the physical microscope to find rare, high-quality sample regions historically consumed hundreds of manual operator hours.
      </p>
      <strong>Pipeline:</strong> Built an automated "Atlas-to-Target" computer vision decision pipeline using CNN-based models (ResNet, VGG-16) to predict high-resolution image usability directly from low-resolution scans.
      <br>
      <strong>Impact:</strong> Accelerated data collection bottleneck processes by <strong>4–10x</strong>, enabling rapid-turnaround structural determination during the COVID-19 pandemic.
      <br>
      <strong>Stack:</strong>
      <span class="tag-list inline">
        <span class="tag">PyTorch</span>
        <span class="tag">ResNet18</span>
        <span class="tag">VGG-16</span>
        <span class="tag">OpenCV</span>
        <span class="tag">NumPy</span>
        <span class="tag">Scikit-Learn</span>
      </span>
      <div class="publication-callout">
        <h4><i class="fas fa-book-open"></i> Research Enabled:</h4>
        <div class="publication-item">
          <strong>Science (2022):</strong>
          <a href="https://www.science.org/doi/10.1126/science.abn7760" target="_blank" rel="noopener noreferrer">
            <em>SARS-CoV-2 Omicron variant: Antibody evasion and cryo-EM structure of spike protein–ACE2 complex</em>
          </a>
        </div>
        <div class="publication-item">
          <strong>Nature Communications (2022):</strong>
          <a href="https://www.nature.com/articles/s41467-022-28324-6" target="_blank" rel="noopener noreferrer">
            <em>Structural and biochemical rationale for enhanced spike protein fitness in delta and kappa SARS-CoV-2 variants</em>
          </a>
        </div>
        <div class="publication-disclaimer">
          Note: Biological findings authored by the UBC lab team; my contribution was the automated high-throughput data collection infrastructure.
        </div>
      </div>
    </div>
  </article>

</div>
