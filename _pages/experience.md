---
permalink: /experience/
title: "Experience"
layout: claude
nav_active: experience
show_header: false
excerpt: "Experience — An RuiHe, MS student at NUS."
---

<section id="education" class="fade-section">
  <h2>Education</h2>
  <div class="exp-item">
    <div class="exp-header">
      <span class="exp-title">National University of Singapore (NUS)</span>
      <span class="exp-period">2026 – Present</span>
    </div>
    <div class="exp-org">MS in Computer Science</div>
    <div class="exp-sub">Advisor: Prof. Mike Zheng Shou &nbsp;·&nbsp; Show Lab</div>
  </div>
  <div class="exp-item">
    <div class="exp-header">
      <span class="exp-title">Zhejiang University</span>
      <span class="exp-period">Aug 2022 – Jul 2026</span>
    </div>
    <div class="exp-org">B.E. in Computer Science</div>
    <div class="exp-sub">Advisor: Prof. Juncheng Li</div>
  </div>
</section>

<section id="experience" class="fade-section">
  <h2>Internships</h2>
  <p class="section-hint">Click any role to expand the project details.</p>

  <details class="collapse" open>
    <summary>
      <span class="summary-main">
        <span class="exp-title">Data &amp; Algorithm Intern</span>
        <span class="exp-org">Alibaba Tongyi Lab (Wanxiang)</span>
      </span>
      <span class="exp-period">Mar 2026 – Present <span class="summary-chevron">&#9654;</span></span>
    </summary>
    <div class="collapse-body">
      <ul class="exp-desc">
        <li><strong>Ego-centric Video World Model (WanFunHands):</strong> On top of the Wan2.2-Fun-5B base, independently designed a hand-conditioning injection architecture (skeleton channel-concat + HPP token injection + camera LoRA, all zero-initialized to preserve base priors). Processed 3,600 hours of ego-centric data into trainable multimodal condition latents and delivered usable 480p and 720p model weights with full inference/training scripts and demos.</li>
        <li><strong>NitroGen Semantic Data Engine:</strong> Independently built a production-grade distributed annotation pipeline (~15k lines) for NVIDIA NitroGen game data, supporting ~10-machine sharded parallelism, checkpoint resume, and exponential-backoff retries. Produced ~1.3M training samples (~3,500 hours) of high-quality image–action aligned data via three-channel VLM semantic reasoning.</li>
        <li><strong>P2P → NitroGen Format Conversion:</strong> Built a full conversion pipeline mapping keyboard/mouse data to gamepad format, with a routing system covering 7 game categories and 94 combinations. Implemented mouse→right-stick PD+EMA smoothing and W→trigger throttle ramps, converting all 108,851 clips (~10k hours) with a three-tier validation system.</li>
      </ul>
    </div>
  </details>

  <details class="collapse">
    <summary>
      <span class="summary-main">
        <span class="exp-title">Embodied Intelligence Intern</span>
        <span class="exp-org">ACE Robotics</span>
      </span>
      <span class="exp-period">Nov 2025 – Jan 2026 <span class="summary-chevron">&#9654;</span></span>
    </summary>
    <div class="collapse-body">
      <ul class="exp-desc">
        <li><strong>Data Pipeline:</strong> Developed a high-efficiency pipeline converting heterogeneous spatial intelligence datasets (3D Grounding, 6DoF) into Qwen SFT formats.</li>
        <li><strong>Model Training &amp; Evaluation:</strong> Executed full-parameter fine-tuning on Qwen3-VL and established a comprehensive benchmark evaluation system for embodied tasks.</li>
      </ul>
    </div>
  </details>

  <details class="collapse">
    <summary>
      <span class="summary-main">
        <span class="exp-title">Assistant Engineer</span>
        <span class="exp-org">Unitree Robotics</span>
      </span>
      <span class="exp-period">Apr 2025 – Sep 2025 <span class="summary-chevron">&#9654;</span></span>
    </summary>
    <div class="collapse-body">
      <ul class="exp-desc">
        <li><strong>Unitree G1 Guidance System:</strong> Designed and optimized robotic motion libraries for guided navigation, integrating custom action sequences with real-time kinematic control.</li>
        <li><strong>LLM-Driven Data Production Pipeline:</strong> Explored an LLM-driven data production pipeline using NVIDIA Isaac Sim API to automatically generate USD files from scene configs for simulation training environment construction.</li>
        <li>Co-authored a research paper from this work.</li>
      </ul>
    </div>
  </details>
</section>
