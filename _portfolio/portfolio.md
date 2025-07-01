---
title:        "Research & Projects"
permalink:    /portfolio/          # ← must match your nav‑bar link
layout:       single
author_profile: true               # shows avatar + sidebar
classes:      wide                 # optional wider text column
---

<style>
/* ──────────────────────────────────────────────────────
   Page‑local CSS – only the two numbers below changed
   ──────────────────────────────────────────────────── */
.thrust-row        {display:flex; flex-wrap:wrap; gap:1.25rem; margin:2rem 0;}
.thrust-row img    {width:240px; height:180px; object-fit:cover; border-radius:4px;}
.thrust-content h3 {margin:0 0 0.5rem 0; font-size:1.15rem;}
.paper-links a     {margin-right:0.6rem;}
/* ──────────────────────────────────────────────────── */
</style>

## Project Portfolio

My work is grounded in building **trustworthy AI systems** that are not only effective but also safe, fair, and respectful of user privacy. I'm especially interested in designing machine‑learning pipelines that are resilient against privacy attacks, robust to adversarial manipulation, and transparent in their decision‑making. This includes working on differential privacy, vertical federated learning, explanation robustness, and bias mitigation in large language models. I approach these challenges with an emphasis on **translational impact**, aiming to bring theoretical guarantees into practical use—especially in sensitive domains like healthcare and security.

---

<div class="thrust-row">
  <img src="{{ '/images/thrust1.PNG' | relative_url }}" alt="Thrust 1">
  <div class="thrust-content">
    <h3>⚠️ Thrust 1 · Adversarial Attacks Leveraging Harmful Content</h3>
    <p><strong>Objective:</strong> This thrust focuses on evaluating how adversarial prompts can exploit weaknesses in content moderation and factual reasoning in large language and multimodal models. It systematically analyzes model vulnerabilities and demonstrates the need for robust, context-aware defenses against misinformation.</p>
    <p class="paper-links">
      <strong>Papers:</strong>
      <a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.174537593.33953859">Paper 1</a>
      <a href="https://aclanthology.org/2025.trustnlp-main.28/">Paper 2</a>
    </p>
  </div>
</div>

---

<div class="thrust-row">
  <img src="{{ '/images/thrust2.PNG' | relative_url }}" alt="Thrust 2">
  <div class="thrust-content">
    <h3>⚖️ Thrust 2 · Fairness & Bias Mitigation in LLM Recommendations</h3>
    <p><strong>Objective:</strong> This thrust investigates how demographic and cultural biases shape the recommendations of large language models across diverse user groups. It quantifies the extent of these biases and demonstrates that context and user attributes can amplify unfairness, while also showing that interventions like prompt engineering and retrieval-augmented generation can effectively reduce bias and promote more equitable AI outcomes.</p>
    <p class="paper-links">
      <strong>Papers:</strong>
      <a href="https://ieeexplore.ieee.org/abstract/document/10825082">Paper 1</a>
      <a href="https://ui.adsabs.harvard.edu/abs/2024arXiv240910825B/abstract">Paper 2</a>
    </p>
  </div>
</div>

---

<div class="thrust-row">
  <img src="{{ '/images/thrust3.JPG' | relative_url }}" alt="Thrust 3">
  <div class="thrust-content">
    <h3>🔒 Thrust 3 · Privacy Leakage Metrics Under Incomplete Information </h3>
    <p><strong>Objective:</strong> This thrust focuses on developing realistic information leakage metrics for privacy scenarios where adversaries have imperfect or incomplete knowledge about the data or the privacy mechanism. Unlike traditional approaches, which assume attackers know the entire statistical structure of the system, these works recognize that real-world adversaries often operate with only partial or estimated information. The thrust systematically introduces new subjective and objective leakage metrics that capture both the beliefs of adversaries and the actual leakage from the system, analyzing and optimizing these metrics for different privacy mechanisms, including extensions to complex, high-dimensional, and non-Bayesian settings.</p>
    <p class="paper-links">
      <strong>Papers:</strong>
      <a href="https://ieeexplore.ieee.org/abstract/document/10795215">Paper 1</a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10221931">Paper 2</a>
      <a href="https://dl.acm.org/doi/full/10.1145/3624982">Paper 3</a>
      <a href="https://ieeexplore.ieee.org/abstract/document/9500401">Paper 4</a>
    </p>
  </div>
</div>

---

<div class="thrust-row">
  <img src="{{ '/images/thrust4.PNG' | relative_url }}" alt="Thrust 4">
  <div class="thrust-content">
    <h3>🛡️ Thrust 4 · Scalable Privacy & Security Solutions</h3>
    <p><strong>Objective:</strong> This thrust develops practical, scalable methods to protect sensitive data in AI and networked systems, including privacy-preserving learning, secure data sharing, and robust key management. It emphasizes solutions that balance strong privacy guarantees with real-world usability and performance.</p>
    <p class="paper-links">
      <strong>Papers:</strong>
      <a href="https://ieeexplore.ieee.org/abstract/document/9895310">Paper 1</a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10527266">Paper 2</a>
      <a href="https://ojs.aaai.org/index.php/AAAI-SS/article/view/31809">Paper 3</a>
    </p>
  </div>
</div>

---

Feel free to <a href="mailto:ssakib1@utc.edu">contact me</a> if you’d like to discuss collaboration, mentoring, or any of these topics further.
