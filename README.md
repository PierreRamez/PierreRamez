<div align="center">

<h1>Pierre Ramez Francis</h1>

<p><em>Computer Engineering &nbsp;·&nbsp; Agentic AI Systems &nbsp;·&nbsp; LLM Fine-Tuning &nbsp;·&nbsp; Edge Inference</em></p>

<p>
  <a href="https://linkedin.com/in/pierreramez">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:pierre.ramez10@gmail.com">
    <img src="https://img.shields.io/badge/Email-pierre.ramez10%40gmail.com-1a1a2e?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/PierreRamez">
    <img src="https://img.shields.io/badge/GitHub-PierreRamez-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

<sub>MSA University × University of Greenwich &nbsp;·&nbsp; 6th of October, Egypt &nbsp;·&nbsp; Graduating June 2027</sub>

</div>

<br>

---

## About

I'm a Computer Engineering student building AI systems that operate under real constraints — constrained hardware, safety-critical environments, and the gap between benchmark performance and production behavior. My current focus is agentic AI: how autonomous LLM-based pipelines are designed, evaluated, and made reliable when the stakes are higher than a demo.

I intern at [ControlPoint](https://control-point.io/about), an OT cybersecurity startup, where I research agentic architectures for industrial threat intelligence. At MSA University I lead the research group at the CSE Outstanding Hub, and I teach C++ programming to secondary school students.

---

## Research Interests

- **Agentic AI systems** — architecture, reliability, and formal evaluation of autonomous LLM-based pipelines
- **LLM fine-tuning under constraints** — PEFT methods (LoRA, QLoRA), closed-loop HITL learning, in-production adaptation
- **Edge inference** — principled efficiency–quality tradeoffs, 4-bit quantization, model selection for constrained deployment
- **AI for cybersecurity** — vulnerability analysis, automated threat intelligence, OT/ICS security

---

## Current Work

| Role | Where | Focus |
|------|--------|-------|
| AI Intern | ControlPoint *(Feb 2026 – present)* | Agentic architectures for OT/ICS security MVP — task decomposition, tool-use pipelines, competitive platform analysis |
| Head of Research | Outstanding Hub, CSE Dept., MSA University *(Nov 2025 – present)* | Research group on automation in AI/ML systems; survey paper in progress |
| Programming Instructor | 6th of October, Egypt *(Oct 2025 – present)* | C++ fundamentals, secondary school level |

---

## Projects

### [Automated OT/ICS Threat Intelligence Pipeline](https://github.com/PierreRamez/Automated-Threat-Intelligence-Pipeline)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5-4285F4?style=flat-square&logo=google&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)

An end-to-end agentic pipeline for industrial cybersecurity. Polls the National Vulnerability Database for live CVE feeds, applies a two-stage classification architecture (domain-specific keyword prefilter → single-pass LLM inference with strict JSON output contracts), and delivers findings through a real-time analyst-facing Streamlit dashboard. Deployed via GitHub Actions CI/CD. Includes documented tradeoff analysis and known system limitations — the project that preceded my current internship at ControlPoint.

---

### [Ouro — Closed-Loop Active Learning System](https://github.com/PierreRamez/PersonalChatbot)

![Llama](https://img.shields.io/badge/Llama_3.2_3B-1a1a2e?style=flat-square)
![Unsloth](https://img.shields.io/badge/Unsloth-ff6b35?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA-6c3483?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

*(Team Lead)*

A production-grade active learning system on Llama 3.2. A HITL pipeline captures user correction signals at inference time, triggers LoRA adapter retraining, and hot-swaps weights with zero service interruption — continuous in-production improvement without redeployment. Trained on a 13k-row curated dataset (DailyDialogue + Mental Health corpus), achieving **4.08 perplexity** and **0.88 BERTScore F1** on a held-out evaluation set. The 3B model was selected over 8B through a formal comparative study: identical evaluation protocol across both variants, with model choice justified by a documented efficiency–quality tradeoff analysis under **4-bit quantization** targeting edge deployment constraints. MLflow experiment tracking, GitHub Actions CI/CD, FastAPI backend throughout.

---

### [A2S-Migrator](https://github.com/PierreRamez/A2S-Migrator)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Spotify API](https://img.shields.io/badge/Spotify_API-1DB954?style=flat-square&logo=spotify&logoColor=white)
![Open Source](https://img.shields.io/badge/Open_Source-MIT-brightgreen?style=flat-square)

Open-source tool for migrating playlists from Anghami to Spotify. Built because no clean public solution existed. Implements full OAuth 2.0 authentication flow, interactive CLI, fuzzy playlist matching, and proper virtual environment packaging. Solves a real problem for a regional audience underserved by the Spotify ecosystem.

---

## Technical Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Machine Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)

**MLOps & Systems**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## Writing

**[Key to Understanding Gradient Descent: Algorithm and How It Works](https://www.linkedin.com/posts/cse-innovation-hub-msa_gradient-descent-algorithm-activity-7290795656426749952-l3WJ)**  
*CSE Innovation Hub, MSA University · Feb 2025*

Mathematical derivation of gradient descent through intuitive analogies and step-by-step implementation — partial derivatives of the loss function, learning rate effects on convergence geometry, and Batch/Stochastic/Mini-Batch variants.

---

## Connect

Open to research collaborations in agentic AI, LLM systems, and software engineering for AI.

📧 [pierre.ramez10@gmail.com](mailto:pierre.ramez10@gmail.com) &nbsp;·&nbsp; 💼 [linkedin.com/in/pierreramez](https://linkedin.com/in/pierreramez)
