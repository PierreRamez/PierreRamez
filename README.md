<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=180&section=header&text=Pierre%20Ramez%20Francis&fontSize=42&fontColor=FFFFFF&fontAlignY=38&desc=Computer%20Engineering%20%E2%80%A2%20Agentic%20AI%20%E2%80%A2%20LLM%20Systems%20%E2%80%A2%20Edge%20Inference&descAlignY=60&descSize=15&animation=fadeIn"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2500&pause=900&color=58A6FF&center=true&vCenter=true&width=600&lines=Agentic+AI+Systems;LLM+Fine-Tuning+%26+Efficient+Inference;AI+for+Cybersecurity+%26+OT%2FICS;Closed-Loop+Active+Learning)](https://github.com/PierreRamez)

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/pierreramez)
&nbsp;
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pierre.ramez10@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=white)](https://github.com/PierreRamez)

<sub>MSA University × University of Greenwich &nbsp;·&nbsp; 6th of October, Egypt &nbsp;·&nbsp; Graduating June 2027</sub>

</div>

<br>

---
<div align="center">
  
### About
</div>

I'm a Computer Engineering student building AI systems that operate under real constraints — constrained hardware, safety-critical environments, and the gap between benchmark performance and production behavior. My current focus is agentic AI: how autonomous LLM-based pipelines are designed, evaluated, and made reliable when the stakes are higher than a demo.

I intern at [ControlPoint](https://control-point.io/about), an OT cybersecurity startup, where I research agentic architectures for industrial threat intelligence. At MSA University I lead the research group at the CSE Outstanding Hub, and I teach C++ programming to secondary school students.

---

<div align="center">

### Research Interests

![Agentic AI](https://img.shields.io/badge/Agentic%20AI%20Systems-70E33B?style=flat-square&logoColor=black)
![LLM Fine-Tuning](https://img.shields.io/badge/LLM%20Fine--Tuning%20%26%20PEFT-63D335?style=flat-square&logoColor=black)
![Edge Inference](https://img.shields.io/badge/Edge%20Inference-56C430?style=flat-square&logoColor=black)
![AI for Cybersecurity](https://img.shields.io/badge/AI%20for%20Cybersecurity-49B42A?style=flat-square&logoColor=black)

</div>

- **Agentic AI systems** — architecture, reliability, and formal evaluation of autonomous LLM-based pipelines
- **LLM fine-tuning under constraints** — PEFT methods (LoRA, QLoRA), closed-loop HITL learning, in-production weight adaptation
- **Edge inference** — principled efficiency–quality tradeoffs, quantization, model selection for resource-constrained deployment
- **AI for cybersecurity** — vulnerability analysis, automated threat intelligence, OT/ICS security

---
<div align="center">
  
### Current Work
</div>

| &nbsp; | Role | Where | Focus |
|--------|------|--------|-------|
| 🔒 | **AI Intern** | [ControlPoint](https://control-point.io/about) *(Feb 2026 – present)* | Agentic architectures for OT/ICS security MVP — task decomposition, tool-use pipelines, competitive platform analysis |
| 🔬 | **Head of Research** | Outstanding Hub, CSE Dept., MSA University *(Nov 2025 – present)* | Research group on automation in AI/ML systems; survey paper in progress |
| 🖥️ | **Programming Instructor** | 6th of October, Egypt/Remote *(Oct 2025 – present)* | C++ fundamentals, secondary school level |

---
<div align="center">
  
### Projects
</div>

<details open>
<summary><b>🔒 Automated OT/ICS Threat Intelligence Pipeline</b></summary>

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5-4285F4?style=flat-square&logo=google&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
[![Repo](https://img.shields.io/badge/→%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/PierreRamez/Automated-Threat-Intelligence-Pipeline)

An end-to-end agentic pipeline for industrial cybersecurity. Polls the National Vulnerability Database for live CVE feeds, applies a two-stage classification architecture (domain-specific keyword prefilter → single-pass LLM inference with strict JSON output contracts), and delivers findings through a real-time analyst-facing Streamlit dashboard. Deployed via GitHub Actions CI/CD. Includes documented tradeoff analysis and known system limitations — the project that preceded my current internship at ControlPoint.

</details>

<br>

<details open>
<summary><b>🤖 Ouro — Closed-Loop Active Learning System</b> &nbsp;<em>(Team Lead)</em></summary>

<br>

![Llama](https://img.shields.io/badge/Llama_3.2_3B-1a1a2e?style=flat-square)
![Unsloth](https://img.shields.io/badge/Unsloth-ff6b35?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA-6c3483?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
[![Repo](https://img.shields.io/badge/→%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/PierreRamez/PersonalChatbot)

A production-grade active learning system built on Llama 3.2 3B. A HITL pipeline captures user correction signals at inference time, triggers LoRA adapter retraining, and hot-swaps weights with zero service interruption — continuous in-production improvement without redeployment. Trained on a 13k-row curated dataset (DailyDialogue + Mental Health corpus), achieving **4.08 perplexity** and **0.88 BERTScore F1** on a held-out evaluation set. Model selection — 3B over 8B — was driven by a formal comparative study: identical evaluation protocol across both variants, with the decision justified through a documented efficiency–quality tradeoff analysis under **4-bit quantization** targeting edge deployment constraints. MLflow experiment tracking and GitHub Actions CI/CD throughout.

</details>

<br>

<details open>
<summary><b>🎵 A2S-Migrator</b></summary>

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Spotify](https://img.shields.io/badge/Spotify_API-1DB954?style=flat-square&logo=spotify&logoColor=white)
![MIT](https://img.shields.io/badge/Open_Source-MIT-3fb950?style=flat-square)
[![Repo](https://img.shields.io/badge/→%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/PierreRamez/A2S-Migrator)

Open-source tool for migrating playlists from Anghami to Spotify. Built because no clean public solution existed. Implements full OAuth 2.0 authentication flow, interactive CLI, and proper virtual environment packaging — solving a real problem for a regional audience underserved by the Spotify ecosystem.

</details>

---
<div align="center">
  
### Technical Stack

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
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**MLOps & Systems**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Tools & Environment**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

</div>

---
<div align="center">
  
### Writing
</div>

**[Key to Understanding Gradient Descent: Algorithm and How It Works](https://www.linkedin.com/posts/cse-innovation-hub-msa_gradient-descent-algorithm-activity-7290795656426749952-l3WJ)**
&nbsp;·&nbsp; *CSE Innovation Hub, MSA University · Feb 2025*

Mathematical derivation of gradient descent through intuitive analogies and step-by-step implementation — partial derivatives of the loss function, learning rate effects on convergence geometry, and Batch/Stochastic/Mini-Batch variants.

---
<div align="center">
  
### Connect

Open to research collaborations in agentic AI, LLM systems, and software engineering for AI.

📧 [pierre.ramez10@gmail.com](mailto:pierre.ramez10@gmail.com) &nbsp;·&nbsp; 💼 [linkedin.com/in/pierreramez](https://linkedin.com/in/pierreramez)
</div>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=100&section=footer"/>
