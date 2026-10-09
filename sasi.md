---
layout: page
title: SASI
description: Sub-Action Semantics Integrated cross-modal fusion for robust early action recognition
img: assets/img/publication_preview/sasi-placeholder.svg
importance: 1
category: work
related_publications: cao2026sasi
---

<div class="paper-page" markdown="1">
  <div class="paper-hero">
    {% include figure.html
      path="assets/img/publication_preview/sasi-arch.png"
      class="img-fluid rounded z-depth-1"
      alt="SASI project preview placeholder" %}
  </div>

  <p class="paper-authors">
    <strong>Yongpeng Cao</strong>, Masahiro Hirano, Hyuno Kim, and Yuji Yamakawa
  </p>

  <div class="paper-links" aria-label="Paper resources">
    <a class="btn btn-outline-primary" href="https://arxiv.org/abs/2604.27508"><i class="ai ai-arxiv"></i> arXiv</a>
    <a class="btn btn-outline-primary" href="https://arxiv.org/pdf/2604.27508"><i class="fa-solid fa-file-pdf"></i> PDF</a>
    <a class="btn btn-outline-primary" href="https://github.com/SavickTso/SASI"><i class="fa-solid fa-code"></i> Code</a>
    <a class="btn btn-outline-primary" href="https://youtu.be/2-Rs6Ri9oN8"><i class="fa-brands fa-youtube"></i> Video</a>
    <a class="btn btn-outline-primary" href="#citation"><i class="fa-solid fa-quote-right"></i> BibTeX</a>
  </div>

  <p class="paper-tldr"><strong>TL;DR:</strong> SASI uses sub-action semantics to help a skeleton-based model recognize human actions earlier from incomplete observations.</p>

  <h2>Abstract</h2>

  <p>
    Human actions are naturally composed of smaller, meaningful sub-actions. SASI integrates those semantics with skeleton-based spatiotemporal features through a dual-branch, cross-modal fusion framework. The method is designed for robust early action recognition in human–robot interaction and runs in real time at 29 Hz. Experiments on BABEL show improved recognition from both complete and partial action sequences.
  </p>

  <h2>Method</h2>

  <div class="paper-summary-grid">
    <div class="paper-summary-card">
      <span class="paper-step">01</span>
      <h3>Kinematic branch</h3>
      <p>A GCN backbone extracts spatial and temporal features from the skeleton sequence.</p>
    </div>
    <div class="paper-summary-card">
      <span class="paper-step">02</span>
      <h3>Semantic branch</h3>
      <p>Predicted sub-actions are represented as language features, exploring fine-grained semantic relationship in motion.</p>
    </div>
    <div class="paper-summary-card">
      <span class="paper-step">03</span>
      <h3>Cross-modal fusion</h3>
      <p>Cross-attention aligns kinematic features with sub-action semantics to recognize actions from partial observations.</p>
    </div>
  </div>

  <h2>Results</h2>

  {% include figure.html
    path="assets/img/publication_preview/sasi-result.png"
    class="img-fluid rounded z-depth-1"
    zoomable=true
    alt="SASI qualitative results for action and sub-action recognition" %}

  <h2>Video</h2>

  <div class="embed-responsive embed-responsive-16by9 rounded z-depth-1">
    <iframe
      class="embed-responsive-item"
      src="https://www.youtube-nocookie.com/embed/2-Rs6Ri9oN8"
      title="SASI: Leveraging Sub-Action Semantics for Early Action Recognition in Human-Robot Interaction"
      loading="lazy"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      referrerpolicy="strict-origin-when-cross-origin"
      allowfullscreen>
    </iframe>
  </div>

  <h2 id="citation">Citation</h2>

```bibtex
@misc{cao2026sasi,
  title         = {SASI: Leveraging Sub-Action Semantics for Robust Early Action Recognition in Human-Robot Interaction},
  author        = {Yongpeng Cao and Masahiro Hirano and Hyuno Kim and Yuji Yamakawa},
  year          = {2026},
  eprint        = {2604.27508},
  archivePrefix = {arXiv},
  primaryClass  = {cs.RO}
}
```

  <p class="paper-page-note">We used AI tools to create this page.</p>
</div>
