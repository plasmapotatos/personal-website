---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: base
permalink: /
---

<div style="display: flex; align-items: center; gap: 30px;">

  <!-- Left column: profile pic -->
  <div style="flex-shrink: 0;">
    <img src="assets/images/cropped_circle_image.png" alt="Timothy Wei" style="border-radius: 50%; width: 160px;">
  </div>

  <!-- Right column: text + links -->
  <div>
    <h1 style="margin: 0;">Hey, I'm Timothy! 👋</h1>
    <h3 style="margin: 5px 0; font-weight: normal; color: gray;">
      Statistics & Computer Science Student · AI/ML Enthusiast
    </h3>

    <!-- Contact Icons -->
    <div class="contact-icons" style="margin: 10px 0; font-size: 1.6em;">
      <a href="https://github.com/plasmapotatos" target="_blank"><i class="fab fa-github"></i></a>
      <a href="https://www.linkedin.com/in/timothyswei/" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="mailto:tsw4@illinois.edu"><i class="fas fa-envelope"></i></a>
      <a href="https://instagram.com/timothyswei" target="_blank"><i class="fab fa-instagram"></i></a>
    </div>

    <!-- Short intro -->
    <p>
      I'm a <strong>Statistics and Computer Science</strong> student at the University of Illinois Urbana-Champaign,
      passionate about <strong>AI-driven applications</strong>. In my free time, I enjoy
      <a href="https://codeforces.com/profile/duckier" target="_blank" rel="noopener noreferrer">competitive programming</a>
      and playing badminton. Check out some of the stuff I do below!
    </p>

  </div>

</div>

<!-- # Hey, I'm Timothy! 👋

I'm a **Statistics and Computer Science** student at the University of Illinois at Urbana-Champaign passionate about **AI-driven applications**. In my free time, I love doing <a href="https://codeforces.com/profile/duckier" target="_blank" rel="noopener noreferrer">competitive programming</a> and playing badminton. Check out some of my past projects below! -->

---

## Work Experience {#work-experience}

### <a href="https://www.coverbase.com" target="_blank" rel="noopener noreferrer">Coverbase Internship</a>

**Software Engineer Intern**
May 2025—August 2025

- Integrated **Retrieval Augmented Generation (RAG)** with **Amazon Knowledge Base** to create a vendor factsheet feature with modularized **Tavily API + LLM queries**, improving information retrieval speed by **~75%**, deployed to all Coverbase customers
- Refactored **multi-LLM Amazon Bedrock pipeline**, resulting in faster execution and improved instruction-following by **~60%** while reducing the API calls needed by **~50%**

### <a href="https://tsaweb.org/" target="_blank" rel="noopener noreferrer">Technology Student Association</a> <span><a href="https://github.com/plasmapotatos/EcoEats-App" target="_blank" rel="noopener noreferrer"><img src="/assets/images/github-mark.svg" alt="GitHub" class="icon"></a></span>

**Software Developer**
December 2024—June 2025

- **Top 12 of 100** teams at the National Technology Student Association Conference
- Created an **end-to-end full-stack Flutter application** with a **Flask API backend** to assist sustainable eating with real-time analysis through a custom locally hosted prompt-tuned **Vision Language Model (LLaVA 13B)**
- Developed a RAG pipeline with **vector embeddings**, reducing **LLM hallucinations by ~90%** and improving reliability

### <a href="https://sip.ucsc.edu/" target="_blank" rel="noopener noreferrer">University of California, Santa Cruz Summer Internship Program (SIP)</a> <span><a href="https://github.com/plasmapotatos/sip-server" target="_blank" rel="noopener noreferrer"><img src="/assets/images/github-mark.svg" alt="GitHub" class="icon"></a></span>

**Software Development Lead**
June 2024—August 2024

- Led software development for a 4-person team, building an end-to-end elderly fall detection system with **Python, Android Studio, and Raspberry Pi** for real-time video/audio streaming and processing.
- Enhanced fall detection accuracy by **~20%** by integrating **vision language models (Video-LLaVA, PaliGemma) with AlphaPose**.
- Coordinated team efforts across hardware setup, ML integration, and Android app development; owned **streaming pipeline + ML logic + notification system**.

### <a href="https://www.edubeyond.ai/" target="_blank" rel="noopener noreferrer">EduBeyond Internship</a>

**Web Developer Intern**
June 2023—Dec 2023

- Developed proficiency in web development using **ReactJS, TailwindCSS, and MaterialUI**
- Deployed 10+ features, such as password-protected classroom invites and a classroom settings page, to the Learning Management System

---

## Research {#research}

### <a href="https://arxiv.org/abs/2410.12165" target="_blank" rel="noopener noreferrer">Dual-Model Distillation for Efficient Action Classification with Hybrid Edge-Cloud Solution (NeurIPS Workshop on VLMs 2024)</a> <span><a href="https://arxiv.org/abs/2410.12165" target="_blank" rel="noopener noreferrer"><img src="/assets/images/arxiv-logomark-small.svg" alt="arXiv" class="icon"></a></span>

- Created an optimized action-classification model through a hybrid edge-cloud solution by training a **Multi-Layer Perceptron** to route queries between various open-source **Video-Language Models (ViLT, LLaVA)**

### <a href="https://ieeexplore.ieee.org/abstract/document/10771011" target="_blank" rel="noopener noreferrer">Enhancing the Binary Classification of Wildfire Smoke Through Vision-Language Models (AIxSET IEEE 2024)</a> <span><a href="https://ieeexplore.ieee.org/abstract/document/10771011" target="_blank" rel="noopener noreferrer"><img src="/assets/images/arxiv-logomark-small.svg" alt="arXiv" class="icon"></a></span>

- Applied NLP innovations through Vision Language Models to camera imagery to enable early detection of wildfire smoke

### <a href="https://arxiv.org/abs/2410.15163" target="_blank" rel="noopener noreferrer">Optimizing Large Language Models for Dynamic Constraints Through Human-in-the-Loop Discriminators (JMM 2025)</a> <span><a href="https://arxiv.org/abs/2410.15163" target="_blank" rel="noopener noreferrer"><img src="/assets/images/arxiv-logomark-small.svg" alt="arXiv" class="icon"></a></span>

- Used Large Language Models, human-in-the-loop, and automatic prompt-tuning to create smart agents for travel planning
