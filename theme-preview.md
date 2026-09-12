---
layout: default
title: Theme & Style Preview
permalink: /theme-preview/
---

# Theme & Style Explorer

Compare different visual themes featuring the **Lora** font family and warmer palettes. Click any option below to preview the theme live across this page and across the entire website.

<div class="theme-picker-panel">
  <div class="theme-button-group">
    <button class="theme-toggle-btn active" onclick="setTheme('')">
      <i class="fas fa-undo"></i> Default (Current)
    </button>
    <button class="theme-toggle-btn" onclick="setTheme('warm-terracotta')">
      <span class="theme-dot" style="background:#b85428;"></span> Variant 1: Warm Terracotta
    </button>
    <button class="theme-toggle-btn" onclick="setTheme('tuscan-editorial')">
      <span class="theme-dot" style="background:#c06122;"></span> Variant 2: Tuscan Editorial
    </button>
    <button class="theme-toggle-btn" onclick="setTheme('sage-sandstone')">
      <span class="theme-dot" style="background:#2d6a4f;"></span> Variant 3: Sage & Sandstone
    </button>
    <button class="theme-toggle-btn" onclick="setTheme('warm-slate')">
      <span class="theme-dot" style="background:#2b6cb0;"></span> Variant 4: Scholarly Slate
    </button>
  </div>
  <div class="theme-status" id="themeStatus">
    Currently active: <strong>Default (Cool Slate & Trebuchet)</strong>
  </div>
</div>

---

## Theme Breakdown

<div class="theme-cards-grid">

  <div class="theme-info-card" onclick="setTheme('warm-terracotta')">
    <h3>Variant 1: Warm Terracotta & Linen</h3>
    <div class="theme-badges">
      <span class="tag">Lora (Headings)</span>
      <span class="tag">Inter (Body)</span>
      <span class="tag">Terracotta #b85428</span>
    </div>
    <p>
      <strong>The Vibe:</strong> Modern academic hybrid. Warm unbleached paper background with rich espresso text and earthy terracotta links. Provides the warmth and intellectual authority of Lora for titles while keeping technical body text razor-sharp.
    </p>
    <div class="palette-swatches">
      <span class="swatch" style="background:#faf7f2;" title="Background"></span>
      <span class="swatch" style="background:#ffffff;" title="Card"></span>
      <span class="swatch" style="background:#e8e1d5;" title="Border"></span>
      <span class="swatch" style="background:#38322c;" title="Text"></span>
      <span class="swatch" style="background:#b85428;" title="Accent"></span>
    </div>
  </div>

  <div class="theme-info-card" onclick="setTheme('tuscan-editorial')">
    <h3>Variant 2: Tuscan Editorial & Amber</h3>
    <div class="theme-badges">
      <span class="tag">Full Lora (Headings & Body)</span>
      <span class="tag">Warm Amber #c06122</span>
    </div>
    <p>
      <strong>The Vibe:</strong> Pure literary / bookish essay. Uses Lora for both headings and body prose, paired with soft cream parchment and deep warm amber accents. Feels like a classic scientific essay or literary monograph.
    </p>
    <div class="palette-swatches">
      <span class="swatch" style="background:#fbf9f4;" title="Background"></span>
      <span class="swatch" style="background:#f7f2e8;" title="Sidebar"></span>
      <span class="swatch" style="background:#e9dfd1;" title="Border"></span>
      <span class="swatch" style="background:#2e2823;" title="Text"></span>
      <span class="swatch" style="background:#c06122;" title="Accent"></span>
    </div>
  </div>

  <div class="theme-info-card" onclick="setTheme('sage-sandstone')">
    <h3>Variant 3: Sage & Sandstone</h3>
    <div class="theme-badges">
      <span class="tag">Lora (Headings)</span>
      <span class="tag">Inter (Body)</span>
      <span class="tag">Deep Sage #2d6a4f</span>
    </div>
    <p>
      <strong>The Vibe:</strong> Organic and thoughtful. Warm sandstone backdrop with eucalyptus/forest green accents. Evokes your stated passion for the planet, wellbeing, and advancing science with a grounded, calm atmosphere.
    </p>
    <div class="palette-swatches">
      <span class="swatch" style="background:#f8f7f3;" title="Background"></span>
      <span class="swatch" style="background:#ffffff;" title="Card"></span>
      <span class="swatch" style="background:#e1ded6;" title="Border"></span>
      <span class="swatch" style="background:#303331;" title="Text"></span>
      <span class="swatch" style="background:#2d6a4f;" title="Accent"></span>
    </div>
  </div>

  <div class="theme-info-card" onclick="setTheme('warm-slate')">
    <h3>Variant 4: Scholarly Slate & Parchment</h3>
    <div class="theme-badges">
      <span class="tag">Lora (Headings)</span>
      <span class="tag">Inter (Body)</span>
      <span class="tag">Warm Brown Tags</span>
      <span class="tag">Slate Blue #2b6cb0</span>
    </div>
    <p>
      <strong>The Vibe:</strong> Balanced warmth and technical precision. Light, luminous warm ivory background (<code>#fcfbfa</code>) keeping text pages airy and effortless to read, warm parchment sidebar (<code>#f6f3ec</code>), elevated white cards with subtle warm shadow depth, rich warm brown tags (<code>#534537</code>), and intellectual slate-blue accents.
    </p>
    <div class="palette-swatches">
      <span class="swatch" style="background:#fcfbfa;" title="Background (#fcfbfa)"></span>
      <span class="swatch" style="background:#f6f3ec;" title="Sidebar (#f6f3ec)"></span>
      <span class="swatch" style="background:#ffffff;" title="Card (#ffffff)"></span>
      <span class="swatch" style="background:#ede7dc;" title="Tag Chip (#ede7dc)"></span>
      <span class="swatch" style="background:#534537;" title="Tag Font (#534537)"></span>
      <span class="swatch" style="background:#2b6cb0;" title="Accent (#2b6cb0)"></span>
    </div>
  </div>

</div>

---

## Live Component Preview

See how your actual portfolio components look under the selected theme:

### 1. Typography & Introduction
<div class="sample-intro-box">
  <h2>Hello, I'm Shay.</h2>
  <div class="cv-subtitle">ML Engineer</div>
  <p>
    I am a <strong>Machine Learning Engineer</strong> specializing in applied research, algorithm development, and building ML systems. My edge lies at the intersection of <em>applied research and production software engineering</em>: pairing mathematical rigor with the discipline required to build robust, scalable pipelines.
  </p>
</div>

### 2. Research Project Card
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
    <strong>Methodology:</strong> Utilizing tools from linear algebra, high-dimensional geometry, and classical ML to ensure statistical rigor.
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

### 3. CV Skills Entries
<div class="skills-container" style="margin-top: 10px;">
  <div class="skills-entry">
    <strong>ML & Algorithms:</strong>
    <span class="tag-list inline">
      <span class="tag">Reinforcement Learning</span>
      <span class="tag">NLP</span>
      <span class="tag">Deep Learning</span>
      <span class="tag">Mechanistic Interpretability</span>
      <span class="tag">Experiment Design</span>
    </span>
  </div>
  <div class="skills-entry">
    <strong>Tools & Frameworks:</strong>
    <span class="tag-list inline">
      <span class="tag">PyTorch</span>
      <span class="tag">Hugging Face</span>
      <span class="tag">Weights & Biases</span>
      <span class="tag">Docker</span>
      <span class="tag">Kubernetes</span>
    </span>
  </div>
</div>

<style>
/* --- THEME PREVIEW STYLES --- */
.theme-picker-panel {
    background-color: var(--sidebar-bg);
    border: 1px solid var(--border-color);
    border-radius: 10px;
    padding: 20px;
    margin: 24px 0;
    box-shadow: 0 2px 8px rgba(0,0,0,0.03);
}

.theme-button-group {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-bottom: 14px;
}

.theme-toggle-btn {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 8px 14px;
    border-radius: 6px;
    border: 1px solid var(--border-color);
    background-color: var(--card-bg);
    color: var(--text-color);
    font-size: 0.9rem;
    font-weight: 600;
    cursor: pointer;
    transition: all 0.2s ease;
    font-family: var(--font-body);
}

.theme-toggle-btn:hover {
    border-color: var(--link-color);
    color: var(--link-color);
}

.theme-toggle-btn.active {
    background-color: var(--link-color);
    border-color: var(--link-color);
    color: #ffffff;
}

.theme-dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
    display: inline-block;
}

.theme-status {
    font-size: 0.92rem;
    color: var(--text-muted);
}

.theme-cards-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    margin: 24px 0;
}

.theme-info-card {
    background-color: var(--card-bg);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 20px;
    cursor: pointer;
    transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}

.theme-info-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 16px rgba(0,0,0,0.06);
    border-color: var(--link-color);
}

.theme-info-card h3 {
    margin-top: 0;
    margin-bottom: 8px;
    font-size: 1.15rem;
}

.theme-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-bottom: 12px;
}

.palette-swatches {
    display: flex;
    gap: 8px;
    margin-top: 14px;
}

.swatch {
    width: 28px;
    height: 28px;
    border-radius: 4px;
    border: 1px solid rgba(0,0,0,0.12);
    display: inline-block;
}

.sample-intro-box {
    background-color: var(--card-bg);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 24px;
    margin-bottom: 24px;
}

.sample-intro-box h2 {
    margin-top: 0;
    border-bottom: none;
    padding-bottom: 0;
}
</style>

<script>
function setTheme(name) {
  if (name) {
    document.documentElement.setAttribute('data-theme', name);
    localStorage.setItem('portfolio-theme', name);
  } else {
    document.documentElement.removeAttribute('data-theme');
    localStorage.removeItem('portfolio-theme');
  }
  updateUI(name);
}

function updateUI(activeTheme) {
  var buttons = document.querySelectorAll('.theme-toggle-btn');
  buttons.forEach(function(btn) {
    btn.classList.remove('active');
  });

  var labelMap = {
    '': 'Default (Cool Slate & Trebuchet)',
    'warm-terracotta': 'Variant 1: Warm Terracotta & Linen (Lora + Inter)',
    'tuscan-editorial': 'Variant 2: Tuscan Editorial & Amber (Full Lora)',
    'sage-sandstone': 'Variant 3: Sage & Sandstone (Lora + Inter + Sage)',
    'warm-slate': 'Variant 4: Scholarly Slate & Parchment (Lora + Inter + Slate)'
  };

  var statusEl = document.getElementById('themeStatus');
  if (statusEl) {
    statusEl.innerHTML = 'Currently active: <strong>' + (labelMap[activeTheme] || activeTheme) + '</strong> <em>(applied site-wide in your browser!)</em>';
  }

  // Highlight active button
  buttons.forEach(function(btn) {
    if (activeTheme === '' && btn.textContent.indexOf('Default') !== -1) {
      btn.classList.add('active');
    } else if (activeTheme && btn.getAttribute('onclick') && btn.getAttribute('onclick').indexOf(activeTheme) !== -1) {
      btn.classList.add('active');
    }
  });
}

document.addEventListener('DOMContentLoaded', function() {
  var current = localStorage.getItem('portfolio-theme') || '';
  updateUI(current);
});
</script>
