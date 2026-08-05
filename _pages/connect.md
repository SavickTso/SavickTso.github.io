---
layout: connect
title: Connect
permalink: /connect/
nav: true
nav_order: 5
description: Connect with Yongpeng Cao — research engineer working on human motion, multimodal behaviour, and robotics.
---

<div class="connect-page">
  <section class="connect-hero" aria-labelledby="connect-name">
    <div class="connect-portrait-wrap">
      <img class="connect-portrait" src="{{ '/assets/img/me.png' | relative_url }}" alt="Portrait of Yongpeng Cao">
      <span class="connect-status"><span aria-hidden="true"></span> Tokyo, Japan</span>
    </div>

    <div class="connect-intro">
      <p class="connect-kicker">Hello, I’m</p>
      <h1 id="connect-name">Yongpeng Cao<span aria-hidden="true"></span></h1>
      <p class="connect-role">Research Engineer <span>@</span> <a href="https://www.nablas.com/en" target="_blank" rel="noopener">Nablas Inc.</a></p>
      <p class="connect-role connect-role-secondary">Associate Research Fellow <span>@</span> <a href="https://www.iis.u-tokyo.ac.jp/en/" target="_blank" rel="noopener">IIS, The University of Tokyo</a></p>
      <p class="connect-summary">
        I work at the intersection of <strong>human motion understanding and generation</strong>,
        <strong>multimodal human behaviour analysis</strong>, <strong>human–robot interaction</strong>,
        and <strong>assistive robotics</strong>.
      </p>
      <div class="connect-primary-actions">
        <a class="connect-button connect-button-primary" href="https://www.linkedin.com/in/{{ site.linkedin_username }}" target="_blank" rel="noopener">
          <i class="fa-solid fa-paper-plane" aria-hidden="true"></i> Connect &amp; Say Hi
        </a>
        <a class="connect-button" href="{{ '/assets/pdf/Resume2026.pdf' | relative_url }}" target="_blank" rel="noopener">
          <i class="fa-solid fa-file-lines" aria-hidden="true"></i> View CV
        </a>
      </div>
    </div>
  </section>


  <section class="connect-section connect-links-section" aria-labelledby="links-heading">
    <div class="connect-section-heading">
      <p>Let’s keep in touch.</p>
      <!-- <h2 id="links-heading">Let’s keep in touch.</h2> -->
    </div>
    <div class="connect-link-grid">
      <a class="connect-link-card" href="https://www.linkedin.com/in/{{ site.linkedin_username }}" target="_blank" rel="noopener">
        <i class="fa-brands fa-linkedin-in" aria-hidden="true"></i>
        <span><strong>LinkedIn</strong><small>Connect and link</small></span>
        <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i>
      </a>
      <a class="connect-link-card" href="https://scholar.google.com/citations?user=uQppwv8AAAAJ&hl=en" target="_blank" rel="noopener">
        <i class="ai ai-google-scholar" aria-hidden="true"></i>
        <span><strong>Google Scholar</strong><small>Explore my research</small></span>
        <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i>
      </a>
      <a class="connect-link-card" href="https://github.com/{{ site.github_username }}" target="_blank" rel="noopener">
        <i class="fa-brands fa-github" aria-hidden="true"></i>
        <span><strong>GitHub</strong><small>Check the code</small></span>
        <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i>
      </a>
      <div class="connect-link-card" aria-label="WeChat ID: yiweicixiangdefuqin">
        <i class="fa-brands fa-weixin" aria-hidden="true"></i>
        <span><strong>WeChat ID</strong><small>yiweicixiangdefuqin</small></span>
        <i class="fa-solid fa-user-plus" aria-hidden="true"></i>
      </div>
      <a class="connect-link-card" href="mailto:{{ site.email | encode_email }}">
        <i class="fa-solid fa-envelope" aria-hidden="true"></i>
        <span><strong>Email</strong><small>{{ site.email }}</small></span>
        <i class="fa-solid fa-arrow-right" aria-hidden="true"></i>
      </a>
    </div>
  </section>

  <aside class="connect-callout" aria-label="Hello invitation">
    <span class="connect-callout-icon" aria-hidden="true"><i class="fa-regular fa-comments"></i></span>
    <div>
      <h2>Come say hello.</h2>
      <span>I’m always glad to exchange ideas about motion, multimodal AI, and robots that understand people.</span>
    </div>
    <a href="mailto:{{ site.email | encode_email }}?subject=Hello%20from%20" aria-label="Email Yongpeng Cao">Email me <i class="fa-solid fa-arrow-right" aria-hidden="true"></i></a>
  </aside>
</div>
