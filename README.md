<h1 align="center">Aryan Kulkarni</h1>

<p align="center">
  <b>Software Engineer · ML Systems · C++ & PyTorch</b><br>
  B.Tech Computer Engineering @ Vidyalankar Institute of Technology, Mumbai · CGPA 9.93/10
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/aryan-kulkarni-a24a182b9/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:aryankulkarni1104@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://portfolio-frontend-latest-qwmg.onrender.com"><img src="https://img.shields.io/badge/Portfolio-111111?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
</p>

---

### About

I'm a final-year Computer Engineering student who likes building things from first principles: an autograd engine in C++, a transformer language model built using a 4GB Laptop GPU, and a production-style MLOps pipeline with automated testing and rollback. Before that, I spent 18 months as a Software Engineer shipping backend systems and LLM-powered products to paying users.

I'm interested in **ML systems, high-performance C++, and GPU computing**, and I'm looking for **Software Engineering / ML Engineering roles (2027 graduate)**.

---

### Experience

**Software Engineer — Vest-Fundora Private Limited** · Mumbai · *Mar 2025 – Sep 2026*

- Built secure RESTful APIs and PostgreSQL data models (schema design, optimized SQL) across authentication, profile, verification, onboarding and internal operations workflows.
- Built **Fundora-OS**, an internal operations platform used daily by the team, combining founder and investor databases with pipeline management, task tracking and lightweight CRM features.
- Developed the **Pitch Deck Analyzer** and **AI Fundraising Coach**, integrating LLM workflows and data pipelines for automated pitch feedback used by **20+ paid users**; shipped all six Fundora Labs AI tools to production.

---

### Featured Projects

#### [TinyGPT](https://github.com/AryanKulkarni11042005/TinyGPT) — Transformer Language Model from Scratch
`Python` `PyTorch` `CUDA (bf16)`

- **12.31M-parameter** decoder-only transformer (6 layers, 6 heads, 384-dim, 256-token context) with pre-norm LayerNorm, residual connections and weight tying.
- Reached **validation loss 1.58 (perplexity ~4.9)** on TinyStories, down from a bigram baseline of 3.99.
- Retrained a byte-level BPE tokenizer (vocab 4096) over **485.8M tokens**; trained with AdamW, cosine decay, gradient clipping and bf16 autocast at **~23.6k tokens/s** on a 4 GB laptop GPU.
- Ran ablations across attention, feed-forward, residual and LayerNorm variants to measure each component's effect.

#### [Micrograd in C++](https://github.com/AryanKulkarni11042005/micrograd-in-cpp) — Autograd Engine & Neural Network
`C++20`

- Scalar reverse-mode automatic differentiation engine built on a dynamic computation graph of `shared_ptr`-managed nodes, each carrying its local gradient rule as a `std::function` closure.
- Overloaded arithmetic operators (mixed scalar/node operands, plus `pow`, `exp`, `tanh`), with backpropagation via topological sort and gradient accumulation.
- Reusable `Neuron`, `Layer` and `MLP` components; trained a 3-4-4-1 network end to end with MSE loss and gradient descent.

#### [Energy Demand Forecasting](https://github.com/AryanKulkarni11042005/Energy-Demand-Forecasting-Scalable-ML) — Scalable MLOps
`Python` `LightGBM` `Apache Airflow` `FastAPI`

- End-to-end pipeline forecasting next-day electricity demand for **52 US balancing authorities**.
- LightGBM models reach **4.60% SMAPE** and **R² 0.9969** on an unseen test period.
- **78 automated tests** across an Airflow retraining pipeline (ingestion, data quality, features, training, evaluation), with model promotion gated on validation metrics and **automatic rollback** on regression; predictions served via FastAPI.

#### [Linear Regression in C++](https://github.com/AryanKulkarni11042005/Linear-Regression-in-CPP)
`C++`

- Linear regression with gradient descent optimization, implemented from scratch.

---

### Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">
</p>

**ML & Data**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA">
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" alt="Airflow">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
</p>

**Backend, Cloud & Databases**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins">
</p>

**Systems, Testing & Tools**
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white" alt="JUnit">
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" alt="Selenium">
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman">
</p>

---

### Currently

- Learning CUDA and GPU kernel programming for ML workloads
- Sharpening DSA and systems fundamentals (OS, networks, distributed systems)
- Looking for open-source projects in ML systems and C++ to contribute to

---

<p align="center">
  <i>Open to 2027 Software Engineering and ML Engineering roles. Feel free to reach out.</i>
</p>
