---
layout: default
title: Juan Esteban Agudelo Ortiz — ML Engineer, Computer Vision & Multimodal AI
description: Portfolio of production ML/CV systems and applied AI research
---

# Juan Esteban Agudelo Ortiz

**Machine Learning Engineer — Computer Vision & Multimodal AI**

I build production computer vision systems and applied AI research, currently working at the intersection of vision transformers and language models for scientific data. Roughly 4.5 years of industry experience shipping CV pipelines and model APIs at Planet AI Space Group and Fregata Space, plus applied LLM evaluation work at d_model. I am completing a PhD in Astronomy at Universidad Nacional de Colombia, where I connect NASA/IBM's Surya spatiotemporal transformer to a language model for solar physics image understanding.

[LinkedIn](https://www.linkedin.com/in/juanessao) · [GitHub](https://github.com/juagudeloo) · [Datos de Ciencia LAT (YouTube)](#) · [Download CV](#)

---

## Featured Projects

### 1. MUISCA — Physics-Informed CNN for Solar Atmosphere Inversion

A multi-scale convolutional neural network that recovers physical parameters of the solar atmosphere (temperature, velocity, magnetic field) directly from spectropolarimetric observations, trained on 700+ GB of MHD simulation data.

**Why it matters:** classical inversion methods for this problem are computationally expensive and depend on strong physical assumptions. This model combines deep learning with physical constraints from the simulation itself, cutting inversion error by roughly 38% against the classical baseline while running orders of magnitude faster.

**Stack:** PyTorch, NumPy, HPC cluster training, physics-informed loss design

[View repository →](https://github.com/juagudeloo/MUISCA)

---

### 2. SDO Paper-to-Observations Matcher

A computer vision pipeline that takes a solar physics figure from a scientific paper and finds the exact original observation it came from in NASA's Solar Dynamics Observatory (SDO) archive, using normalized cross-correlation and LightGlue-based feature matching.

**Why it matters:** this is the backbone of the data pipeline for my PhD's vision-language model. Scientific papers describe observations in natural language and figures, but rarely link back to the raw, machine-readable data. This closes that gap automatically, at a scale that would be impractical to do by hand across thousands of papers.

**Stack:** OpenCV, LightGlue, SIFT/ORB + RANSAC, sunpy/Fido

[View repository →](https://github.com/juagudeloo/SDO_paper_to_observations)

---

### 3. NASA ADS → SDO Metadata API

A pipeline and REST API that extracts structured metadata from NASA ADS papers referencing Solar Dynamics Observatory instruments, making unstructured academic literature queryable for downstream research tools.

**Why it matters:** it demonstrates the same pattern I used in production at Planet AI — turning a messy, high-volume unstructured source into a clean, servable API — applied here to scientific literature instead of satellite imagery.

**Stack:** Python, FastAPI, NASA ADS API

[View repository →](https://github.com/juagudeloo/NASA_ADS_SDO)

---

### 4. Flashcard Generator — Local-First RAG with a Small Language Model

A study tool that generates flashcards from PDFs, handwritten notes, and reference images, running entirely on a local Small Language Model (Qwen2.5-3B) with LlamaIndex for retrieval, wrapped in a Gradio interface.

**Why it matters:** this is my hands-on RAG and local-inference project — no cloud API dependency, quantized model, real multimodal input (text and images). It is the practical complement to the LLM evaluation work I did professionally at d_model.

**Stack:** Qwen2.5-3B, LlamaIndex, Gradio, local inference

[View repository →](https://github.com/DatosDeCiencia-LAT/flashcard-generator-slm)

---

## Background

- **d_model** — Designed adversarial evaluation protocols for LLMs across three failure modes (hallucination, bias, sycophancy). Recommended without reservation for senior ML roles by the COO.
- **Planet AI Space Group** — Sole architect of three production REST APIs (FastAPI, Docker, IBM Cloud) serving CV models over multispectral and hyperspectral satellite imagery at national scale. Presented results to the Colombian Ministry of Sciences, securing competitive project funding.
- **Fregata Space** — Applied SRCNN-based super-resolution to multi-channel satellite imagery.
- **PhD, Astronomy (in progress)** — Building a LLaVA-style vision-language model connecting NASA/IBM's Surya transformer to an LLM for solar physics.
- **Publications** — RACCEFYN (2024, Scopus/WoS indexed), RMxAC Vol. 60 (2026, two papers). AstroCO 2025 award.

[Full CV →](#)

---

## Datos de Ciencia LAT

I run a Spanish-language YouTube channel translating data science and AI methods into business-relevant use cases, using scientific datasets as teaching material. [Watch on YouTube →](#)

---

## Contact

Open to remote Machine Learning Engineer / Computer Vision / Applied AI roles.

[juan.es.agor@gmail.com](mailto:juan.es.agor@gmail.com) · [LinkedIn](https://www.linkedin.com/in/juanessao)
