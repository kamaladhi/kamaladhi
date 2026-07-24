<h1 align="center">Hi 👋, I'm Jeevakamal K R</h1>

<h3 align="center">
AI Engineer • Agentic AI • Multimodal AI • PINNs • HPC
</h3>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Poppins&size=24&duration=3000&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=Building+Production+Grade+AI+Systems;Agentic+AI+%7C+RAG+%7C+Voice+AI;Physics+Informed+Machine+Learning;Healthcare+AI+%7C+Edge+AI+%7C+HPC" />
</p>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=kamaladhi&label=Profile+Views&color=0e75b6&style=flat" />
</p>

---

## 🎓 About Me

AI & Data Science undergraduate at **Amrita Vishwa Vidyapeetham** (B.Tech, 2023–2027).

I build systems at the intersection of physics, machine learning, and real-world deployment — from physics-informed neural networks to production healthcare AI. Currently focused on agentic AI systems, multimodal RAG, and deploying cutting-edge models in resource-constrained environments.

---

## 💼 Recent Work

**AI/ML Engineering Intern — UVS Cube Infotech, Madurai**
*Mar 2026 – May 2026 · Completed ✅*

Built and deployed two production AI systems for the **MyBeat** live healthcare platform:

### 🤖 MyBeat Care AI Chatbot
- Hybrid RAG pipeline: **FAISS (dense) + BM25 (sparse) + PubMedBERT reranking** for accurate medical query resolution
- **FHIR R4 / ABDM standards** integration for real-time patient history injection into LLM prompts
- Deterministic severity scoring engine (0–100) with red-flag symptom detection
- **Triple-Gate output safety** — guarantees zero diagnostic statements in all responses

> Stack: FastAPI · FAISS · BM25 · PubMedBERT · Llama-3.1 · Redis · Docker · NGINX · GitHub Actions

### 🎙️ MyBeat Voice Assistant
- End-to-end voice pipeline: **Whisper ASR** → **Llama-3.1 NLU** (Groq) → **pyttsx3 TTS** with Gemini failover
- **Dual-layer NLU** — keyword pattern matching (fast/offline) + Llama-3.1 for complex sentences; supports 8 intents
- **3-Stage Cascade Recommendation Engine** for doctor ranking:
  - Stage 1 (60%) — Content: Distance · Experience · Fee · Language
  - Stage 2 (25%) — Feedback: Ratings · Repeat visits · Booking conversion
  - Stage 3 (15%) — Trust: Verified credentials · Urgent availability · Insurance match
- Voice-to-UI control — returns structured JSON `uiActions` (`NAVIGATE`, `AUTO_FILL`, `HIGHLIGHT_RECOMMENDATION`) for hands-free navigation
- **OpenWakeWord** (ONNX) for always-on "Hey MyBeat" hands-free activation
- Secured all endpoints with **JWT Bearer Token (HS256)** authentication

> Stack: FastAPI · Whisper · Llama-3.1 · OpenWakeWord · pyttsx3 · PyJWT · Docker · NGINX · GitHub Actions CI/CD · IIS Reverse Proxy

---

## 🔬 Research Interests

- Agentic AI Systems
- Multimodal RAG
- Physics-Informed Neural Networks (PINNs)
- Healthcare AI & Medical LLMs
- Voice AI & Speech Processing
- Federated Learning
- Edge AI Deployment
- High Performance Computing (HPC)

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:92FE9D&height=120&section=header&text=Tech%20Stack&fontSize=40"/>

## 🛠 Tech Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,fastapi,flask,react,docker,redis,mysql,postgresql,neo4j,git,github,linux,cpp,java,matlab" />
</p>

**ML / AI:** PyTorch · PINNs · Federated Learning · LSTMs · Attention · YOLOv8 · LoRA / QLoRA · RAG · LLMs  
**Agentic AI:** LangChain · LangGraph · GraphRAG · Groq API · Autonomous Agents  
**Computer Vision:** MediaPipe · BLIP · EfficientNet · Dual-Stream Fusion  
**Voice AI:** OpenWakeWord · Whisper · pyttsx3  
**HPC:** CUDA · OpenMP · C++ · Parallel & Heterogeneous Computing  
**Full Stack:** Python · React · FastAPI · Flask · REST APIs · MySQL · Neo4j · HTML5 · CSS3  
**Hardware / IoT:** Raspberry Pi · Arduino · Blynk IoT  
**MLOps:** MLflow · Weights & Biases · Docker · NGINX · Redis · Git · GitHub Actions  
**Languages:** Python · C++ · JavaScript · Java (basics) · MATLAB · Scala (basics)

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=92FE9D:00C9FF,100:00A8FF&height=120&section=middle"/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%">

### 🧠 ResearchOS
Agentic GraphRAG platform that turns ArXiv papers into a Neo4j knowledge graph, queried by autonomous LangGraph agents for hallucination-free, citation-backed answers.

**Tech:** FastAPI, Neo4j, LangGraph, Docker  
[📂 GitHub](https://github.com/kamaladhi/ResearchOS)

</td>
<td width="50%">

### 🎭 AVIS — Dual-Stream Emotion Recognition & Captioning
Fuses EfficientNet + MediaPipe dual-stream emotion recognition with BLIP and a LangGraph agentic layer for empathetic, context-aware image captioning.

**Tech:** PyTorch, YOLOv8, BLIP, LangGraph  
[📂 GitHub](https://github.com/kamaladhi/AVIS-Dual-Stream-Emotion-Recognition-and-Contextual-Image-Captioning)

</td>
</tr>
<tr>
<td width="50%">

### 🎥 Snake Rescue Robot
Bio-inspired robot with real-time human detection using YOLOv8. **Best Paper Award** at SISCON 2025.

**Tech:** YOLOv8, RPi, Arduino  
[📂 View Project](https://drive.google.com/drive/folders/1D8UcViLYWYyXmVHtDe3Z2YbI5SOueiB9?usp=drive_link)

</td>
<td width="50%">

### ⚡ EV Range Prediction (PINN)
Physics-constrained LSTM for real-world EV range estimation. **<5% RMSE**, W&B tracked.

**Tech:** PyTorch, SUMO, MLflow  
[📂 GitHub](https://github.com/kamaladhi/EV-Range-prediction-using-PINNS-under-real-traffic-condition)

</td>
</tr>
<tr>
<td width="50%">

### 🛰️ HPC Satellite Benchmark
Serial vs OpenMP vs CUDA performance analysis on 405k satellite images.

**Tech:** C++, CUDA, OpenMP  
[📂 GitHub](https://github.com/kamaladhi/Heterogeneous-Satellite-Imaging-Benchmark)

</td>
<td width="50%">

### 🔍 FedRetinaNet
Federated object detection for power infrastructure defect detection. **mAP@50: 0.91**.

**Tech:** Python, RetinaNet, Federated Learning  
[📂 GitHub](https://github.com/kamaladhi/FedRetinaNet-Insulator-Defect-Detection)

</td>
</tr>
<tr>
<td width="50%">

### 🇮🇳 Tamil NLP (LLaMA)
LLaMA 3.1 8B fine-tuned for Tamil↔English translation using Unsloth.

**Tech:** Unsloth, LoRA, 4-bit Quantization  
[📂 GitHub](https://github.com/kamaladhi/eng2tam-unsloth-transformer)

</td>
<td width="50%">

### 🏙️ Urban Microgrid Digital Twin
Predictive cyber-physical resilience framework with CNN-BiLSTM.

**Tech:** CNN-BiLSTM, FastAPI, Digital Twins  
[📂 GitHub](https://github.com/kamaladhi/A-Predictive-Cyber-Physical-Digital-Twin-for-Urban-Microgrid-Resilience.)

</td>
</tr>
</table>

---
## 📊 GitHub Analytics

<p align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=kamaladhi&show_icons=true&theme=tokyonight&hide_border=true"/>

<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=kamaladhi&theme=tokyonight&hide_border=true"/>
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kamaladhi&layout=compact&theme=tokyonight&hide_border=true"/>
</p>

---

## 🏆 Achievements & Highlights

🏆 **Best Paper Award** — SISCON 2025  
📄 **3 Research Publications** in IEEE & AIP journals  
🚀 **Production Healthcare AI Systems** deployed to live platform  
🎓 **B.Tech AI & Data Science** — Amrita Vishwa Vidyapeetham  

---

## 📚 Publications

- [**Bio-Inspired Snake Robot for Real-Time Victim Detection in Disaster Environments**](https://ieeexplore.ieee.org/document/11409077) — Mar 2026
- [**Emotion-Aware Image Captioning using Deep Learning** (Co-Author)](https://ieeexplore.ieee.org/document/11410892) — Mar 2026
- [**Solar Powered Agricultural Robot for Irrigation** (Co-Author)](https://pubs.aip.org/aip/acp/article-abstract/3385/1/030009/3380740/Solar-powered-agricultural-robot-for-irrigation) — Feb 2026

---

## 🏅 Certifications

- **Physics-Informed Neural Networks** — Udemy (May 2025)
- **Google AI Essentials** (Jul 2024)
- **Foundations of Cybersecurity** — Google (Mar 2024)

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=00C9FF:92FE9D,100:00A8FF&height=120&section=footer"/>

## 🤝 Connect With Me

<p align="center">
<a href="https://linkedin.com/in/jeevakamal-k-r-248435280" target="_blank">
<img src="https://skillicons.dev/icons?i=linkedin" alt="LinkedIn"/>
</a>

<a href="mailto:jeevakamal2005@gmail.com">
<img src="https://skillicons.dev/icons?i=gmail" alt="Email"/>
</a>

<a href="https://github.com/kamaladhi">
<img src="https://skillicons.dev/icons?i=github" alt="GitHub"/>
</a>
</p>

<p align="center">
<i>💡 Always open to collaborations on AI systems, research, and production deployments.</i>
</p>

---

<p align="center">
<img src="https://readme-jokes.vercel.app/api" alt="Jokes Card"/>
</p>
