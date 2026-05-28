# Hi, I'm Jeevakamal K R 👋

AI & Data Science undergraduate at Amrita Vishwa Vidyapeetham (B.Tech, 2023–2027).
I build systems at the intersection of physics, machine learning, and real-world deployment — from
physics-informed neural networks to production healthcare AI.

🏆 Best Paper Award — SISCON Conference, Dec 2025

---

## 💼 Experience

**AI/ML Engineering Intern — UVS Cube Infotech, Madurai**
*Mar 2026 – May 2026 · Completed ✅*

Built and deployed two production AI systems for the **MyBeat** live healthcare platform:

---

### 🤖 MyBeat Care AI Chatbot
- Built a **hybrid RAG pipeline** — FAISS (dense) + BM25 (sparse) + PubMedBERT reranking for accurate medical query resolution
- Integrated **FHIR R4 / ABDM** standards for real-time patient history injection into LLM prompts
- Engineered a **deterministic severity scoring engine (0–100)** with red-flag symptom detection
- Implemented **Triple-Gate output safety** — guarantees zero diagnostic statements in all responses

> Stack: FastAPI · FAISS · BM25 · PubMedBERT · Llama-3.1 · Redis · Docker · NGINX · GitHub Actions

---

### 🎙️ MyBeat Voice Assistant
- Built end-to-end voice pipeline: **Whisper ASR** → **Llama-3.1 NLU** (Groq) → **pyttsx3 TTS** with Gemini failover
- **Dual-layer NLU** — keyword pattern matching (fast/offline) + Llama-3.1 for complex sentences; supports 8 intents (`BOOKING`, `RECOMMENDATION`, `LAB_BOOKING`, `MANUAL_HANDOFF` etc.)
- Built a **3-Stage Cascade Recommendation Engine** for doctor ranking:
  - Stage 1 (60%) — Content: Distance · Experience · Fee · Language
  - Stage 2 (25%) — Feedback: Ratings · Repeat visits · Booking conversion
  - Stage 3 (15%) — Trust: Verified credentials · Urgent availability · Insurance match
- Implemented **voice-to-UI control** — returns structured JSON `uiActions` (`NAVIGATE`, `AUTO_FILL`, `HIGHLIGHT_RECOMMENDATION`) for hands-free app navigation
- **OpenWakeWord** (ONNX) for always-on "Hey MyBeat" hands-free activation
- Secured all endpoints with **JWT Bearer Token (HS256)** authentication

> Stack: FastAPI · Whisper · Llama-3.1 · OpenWakeWord · pyttsx3 · PyJWT · Docker · NGINX · GitHub Actions CI/CD · IIS Reverse Proxy

---

## 🔬 What I've been building

- Physics-Informed Neural Networks (PINNs) for EV range prediction under real traffic
- Federated learning pipelines for power infrastructure defect detection
- Edge ML deployment on Raspberry Pi and NVIDIA Jetson
- Tamil NLP — fine-tuning LLaMA 3.1 with LoRA for low-resource translation

---

## 🛠️ Skills

**ML / AI:** PyTorch · PINNs · Federated Learning · LSTMs · Attention · YOLOv8 · LoRA / QLoRA · RAG · LLMs  
**Voice AI:** OpenWakeWord · Whisper · pyttsx3  
**HPC:** CUDA · OpenMP · C++ · Parallel & Heterogeneous Computing  
**Full Stack:** Python · React · FastAPI · Flask · REST APIs · MySQL · HTML5 · CSS3  
**Hardware / IoT:** Raspberry Pi · Arduino · Blynk IoT  
**MLOps:** MLflow · Weights & Biases · Docker · NGINX · Redis · Git · GitHub Actions  
**Languages:** Python · C++ · JavaScript · Java (basics) · MATLAB · Scala (basics)

---

## 📌 Featured Projects

| Project | Description | Tech |
|--------|-------------|------|
| [Snake Rescue Robot 🎥](https://drive.google.com/drive/folders/1D8UcViLYWYyXmVHtDe3Z2YbI5SOueiB9?usp=drive_link) | YOLOv8 human detection on servo robot — Best Paper Award | YOLOv8, RPi, Arduino |
| [EV Range Prediction (PINN)](https://github.com/kamaladhi/EV-Range-prediction-using-PINNS-under-real-traffic-condition) | Physics-constrained LSTM, <5% RMSE, W&B tracked | PyTorch, SUMO, MLflow |
| [HPC Satellite Benchmark](https://github.com/kamaladhi/Heterogeneous-Satellite-Imaging-Benchmark) | Serial vs OpenMP vs CUDA on 405k satellite images | C++, CUDA, OpenMP |
| [FedRetinaNet](https://github.com/kamaladhi/FedRetinaNet-Insulator-Defect-Detection) | Federated object detection, mAP@50 of 0.91 | Python, RetinaNet |
| [Tamil NLP (LLaMA)](https://github.com/kamaladhi/eng2tam-unsloth-transformer) | LLaMA 3.1 8B fine-tuned for Tamil↔English translation | Unsloth, LoRA, 4-bit |
| [Urban Microgrid Digital Twin](https://github.com/kamaladhi/A-Predictive-Cyber-Physical-Digital-Twin-for-Urban-Microgrid-Resilience.) | Predictive cyber-physical resilience framework | CNN-BiLSTM, FastAPI |

---

## 📄 Publications

- [**Bio-Inspired Snake Robot for Real-Time Victim Detection in Disaster Environments**](https://ieeexplore.ieee.org/document/11409077) — Mar 2026
- [**Emotion-Aware Image Captioning using Deep Learning** (Co-Author)](https://ieeexplore.ieee.org/document/11410892) — Mar 2026
- [**Solar Powered Agricultural Robot for Irrigation** (Co-Author)](https://pubs.aip.org/aip/acp/article-abstract/3385/1/030009/3380740/Solar-powered-agricultural-robot-for-irrigation) — Feb 2026

---

## 🏅 Certifications

- Physics-Informed Neural Networks — Udemy (May 2025)
- Google AI Essentials (Jul 2024)
- Foundations of Cybersecurity — Google (Mar 2024)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://linkedin.com/in/jeevakamal-k-r-248435280)
[![Email](https://img.shields.io/badge/Email-jeevakamal2005@gmail.com-red?style=flat&logo=gmail)](mailto:jeevakamal2005@gmail.com)
[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=kamaladhi&show_icons=true&hide_border=true&theme=dark)](https://github.com/kamaladhi)
