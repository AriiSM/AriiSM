<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                                  HERO                                   -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24,30&height=240&section=header&text=AriiSM&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Human-Centered%20AI%20Developer&descSize=20&descAlignY=60&animation=fadeIn" width="100%" alt="header" />

<a href="https://github.com/AriiSM">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=8A7CFF&center=true&vCenter=true&width=620&lines=Building+AI+that+understands+people.;NLP+%E2%80%A2+LLMs+%E2%80%A2+Multimodal+Speech;Document+AI+%E2%80%A2+Clinical+NLP+%E2%80%A2+Health-Tech." alt="typing" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=AriiSM&style=for-the-badge&color=8A7CFF&label=PROFILE+VIEWS" alt="profile views" />
<img src="https://img.shields.io/github/followers/AriiSM?style=for-the-badge&color=8A7CFF&labelColor=1a1a2e&logo=github" alt="followers" />
<img src="https://img.shields.io/badge/Focus-Human--Centered%20AI-8A7CFF?style=for-the-badge&labelColor=1a1a2e" alt="focus" />

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />

</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                                  ABOUT                                  -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## 🧠 &nbsp; Human-Centered AI Developer

I'm a **Computer Science graduate** passionate about building **AI that understands and connects with people**.
My work blends **machine learning, cognition, and design thinking** to create systems that are not only intelligent — but considerate.

<p align="center">
  <img src="https://img.shields.io/badge/Human--Centered%20AI-8A7CFF?style=for-the-badge&labelColor=1a1a2e" alt="t1" />
  <img src="https://img.shields.io/badge/Emotion%20%26%20Behavior-22d3ee?style=for-the-badge&labelColor=1a1a2e" alt="t2" />
  <img src="https://img.shields.io/badge/Adaptive%20Experiences-f59e0b?style=for-the-badge&labelColor=1a1a2e" alt="t3" />
  <img src="https://img.shields.io/badge/Health--Tech-10b981?style=for-the-badge&labelColor=1a1a2e" alt="t4" />
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />
</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                              ACHIEVEMENTS                               -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## 🏆 &nbsp; Achievements

<p>
  <img src="https://img.shields.io/badge/%F0%9F%A5%87%20%201ST%20PLACE%20%E2%80%94%20PoliHack%20v17%20%C2%B7%20AppDev-FFD700?style=for-the-badge&labelColor=1a1a2e" alt="poli" />
</p>

> **Gene Explorer** &nbsp;·&nbsp; [`AriiSM/PoliHack_V17`](https://github.com/AriiSM/PoliHack_V17)
> Drug-repurposing platform powered by **BioGPT** and interactive **3D molecular graphs**.

<p>
  <img src="https://img.shields.io/badge/%F0%9F%A5%88%20%202ND%20PLACE%20%E2%80%94%20Hermes%20Cybersecurity%20Hackathon-C0C0C0?style=for-the-badge&labelColor=1a1a2e" alt="hermes" />
</p>

> **Trust Issues** &nbsp;·&nbsp; [`AriiSM/Hermes-Hackthon-2024`](https://github.com/AriiSM/Hermes-Hackthon-2024)
> A gamified phishing-awareness experience inspired by *"Papers, Please."*

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />
</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                            FEATURED PROJECTS                            -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## 💡 &nbsp; Featured Projects

### 🪶 &nbsp; Papyr &nbsp; <sub><img src="https://img.shields.io/badge/private-9aa0a6?style=flat-square&labelColor=1a1a2e" /></sub>

Django app that **automates the generation of Romanian legal documents**.
Users pick a template, snap a photo of an **ID card** or **company registration certificate**, and the OCR engine autofills the form.
Outputs clean **`.docx` + `.pdf`** in one click, with a built-in **CNP decoder** that derives birthday and sex from the personal-ID number.
Powered by **Docling** for OCR, **docxtpl** for templating, and a custom admin UI for authoring new templates without touching any code.

<a href="https://github.com/AriiSM"><img src="https://skillicons.dev/icons?i=django,python,bootstrap&theme=dark" alt="papyr-stack" /></a>

---

### 🩺 &nbsp; SPR 2026 — Mammography Report Classification &nbsp; <sub><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&labelColor=1a1a2e&logo=kaggle&logoColor=white" /></sub>

Kaggle entry for the **Sociedade Paulista de Radiologia 2026** challenge, predicting the **BI-RADS category (0–6)** of free-text Brazilian-Portuguese mammography reports.
The task is brutal: **87% benign**, malignant classes <0.3%, and macro-F1 evaluation makes the rare suspicious classes drive almost all of the variance.
My strongest system is a **multi-encoder fusion** of three frozen Portuguese BERTs, *BERTimbau-Contrastive*, *BioBERTpt*, and *Albertina-PT-BR*, combined through a small MLP head.
Result: **val macro-F1 0.7961 raw → 0.8188** with per-class threshold tuning, best-or-tied on every rare class.

<a href="https://github.com/AriiSM/SPR-2026-Mammography-Report-Classification"><img src="https://skillicons.dev/icons?i=python,pytorch,sklearn&theme=dark" alt="spr-stack" /></a>

---

### 🌶️ &nbsp; SoulSpice

A **personalized conversational AI assistant** designed to learn *your* preferences instead of giving everyone the same default answer.
It combines **LLM fine-tuning** for tone & domain alignment with **RAG** over a per-user memory store, so context, opinions, and prior interactions all carry forward.
The result: replies that feel tailored — recommendations, suggestions, and small-talk weighted by what you've already told it.
Built on top of LangChain, open-source LLMs, and a transparent embedding-and-retrieval pipeline.

<a href="https://github.com/AriiSM/SoulSpice"><img src="https://skillicons.dev/icons?i=python,pytorch&theme=dark" alt="soulspice-stack" /></a>

---

### ⚡ &nbsp; SpeedCatch

A lightweight **similarity-search engine** built directly on top of **FAISS**, fast, in-process, no external service required.
Designed to be **transparent**: every step of the embedding + indexing pipeline is exposed and tweakable, so it's always clear how a result was ranked.
A handy building block for retrieval, deduplication, or recommendation prototypes that don't need the weight of a full vector-DB stack.
Pure Python, easy to drop into any project as a starting point for retrieval experiments.

<a href="https://github.com/AriiSM/SpeedCatch"><img src="https://skillicons.dev/icons?i=python,sklearn&theme=dark" alt="speedcatch-stack" /></a>

---

### ✋ &nbsp; Hand Gestures Recognition

**Real-time hand-gesture detection** powered by a custom CNN trained from scratch, built for **accessibility** and **intuitive interaction** without any specialised hardware.
Runs on a regular webcam, classifies gestures live, and emits events that any downstream app can react to (volume, navigation, sign-language prototyping, etc.).
Tuned to stay **lightweight** so the whole loop remains smooth on modest machines.
A small project with a clear goal: make it possible to control a computer without ever touching it.

<a href="https://github.com/AriiSM/Hand-Gesture-Recognition"><img src="https://skillicons.dev/icons?i=python,tensorflow,opencv&theme=dark" alt="hand-stack" /></a>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />
</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                            WORK IN PROGRESS                             -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## 🔬 &nbsp; Work in Progress

### 👄 &nbsp; LipReadSense &nbsp; <sub><img src="https://img.shields.io/badge/Master's%20Thesis-8A7CFF?style=flat-square&labelColor=1a1a2e" /> &nbsp; <img src="https://img.shields.io/badge/private-9aa0a6?style=flat-square&labelColor=1a1a2e" /></sub>

A deep-learning **lip-reading system** that decodes spoken language **purely from visual lip movements**, no audio input at all.
Motivation: enable speech understanding in noisy environments, support hearing-impaired users, and serve as a research foundation for **low-resource languages** that mainstream VSR ignores.
Built around **spatio-temporal transformers**, trained on the Romanian VSR dataset produced by the pipeline below.
The end-goal of my **Master's thesis**: a working visual-speech model for Romanian, where no public lip-reading model currently exists.

<a href="https://github.com/AriiSM"><img src="https://skillicons.dev/icons?i=python,pytorch,opencv&theme=dark" alt="lip-stack" /></a>

---

### 🎬 &nbsp; Sentence-Level Visual Speech Recognition in Romanian &nbsp; <sub><img src="https://img.shields.io/badge/Dataset%20Pipeline-22d3ee?style=flat-square&labelColor=1a1a2e" /> &nbsp; <img src="https://img.shields.io/badge/private-9aa0a6?style=flat-square&labelColor=1a1a2e" /></sub>

An automated pipeline that turns **Romanian & Moldovan YouTube videos** into a **training-ready, sentence-level VSR dataset**, closing the gap that *no publicly available Romanian lip-reading dataset exists*.
Outputs an **LRS-compatible** dataset with mouth-ROI clips, Romanian transcriptions, and **speaker-disjoint** train/val/test splits.
Comes with a live **Flask dashboard** for picking sources, watching per-stage progress, and browsing every generated sample inline.

<a href="https://github.com/AriiSM"><img src="https://skillicons.dev/icons?i=python,pytorch,flask,opencv&theme=dark" alt="vsr-stack" /></a>

---

### 🧬 &nbsp; NeuroMote &nbsp; <sub><img src="https://img.shields.io/badge/Bachelor's%20Thesis-8A7CFF?style=flat-square&labelColor=1a1a2e" /></sub>

My **Bachelor's thesis project**, a **multimodal emotion-recognition** system that interprets emotional state from **audio + video** signals together.
Fuses **tone of voice** (prosody, pitch, energy) with **facial-expression** features at multiple levels of the network, rather than relying on either signal alone.
Aimed at affective-computing applications: empathic interfaces, accessibility tools, and mental-health prototypes.
The premise: emotion is rarely just a face or just a voice, getting it right needs both, fused well.

<a href="https://github.com/AriiSM/NeuroMote"><img src="https://skillicons.dev/icons?i=python,pytorch,opencv&theme=dark" alt="neuromote-stack" /></a>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />
</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                                AI TOOLBOX                               -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## ⚙️ &nbsp; AI Toolbox

<p align="center">
  <a href="https://github.com/AriiSM">
    <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,fastapi,docker&perline=8&theme=dark" alt="ai-skills" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Transformers-8A7CFF?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-10A37F?style=for-the-badge&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/Docling-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white" />
  <img src="https://img.shields.io/badge/MediaPipe-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/ElasticSearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
</p>

> Skilled in **NLP**, **LLM fine-tuning**, **multimodal learning**, **retrieval systems**, and **AI deployment pipelines**.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />
</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                            OTHER TECH SKILLS                            -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## 🧩 &nbsp; Other Technical Skills

<p align="center">
  <a href="https://github.com/AriiSM">
    <img src="https://skillicons.dev/icons?i=django,react,ts,nodejs,java,postgres,mongodb,postman,git,github&perline=10&theme=dark" alt="other-skills" />
  </a>
</p>

> Experienced in **OOP design**, **RESTful architectures**, **scalable APIs**, and **modular system design**.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=12,20,24,30&height=2&width=100%" width="100%" alt="line" />
</div>

<!-- ──────────────────────────────────────────────────────────────────────── -->
<!--                              LANGUAGES                                  -->
<!-- ──────────────────────────────────────────────────────────────────────── -->

## 🎨 &nbsp; Languages I Reach For

<p align="center">
  <a href="https://github.com/AriiSM">
    <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AriiSM&layout=donut&hide_border=true&langs_count=8&title_color=8A7CFF&text_color=e5e7eb&bg_color=0d1117" alt="top languages" />
  </a>
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24,30&height=120&section=footer" width="100%" alt="footer" />
</div>
