<h1 align="center">Hey, I'm Yusuf 👋</h1>

<p align="center">
  <b>AI / ML Engineer</b> · LLM Systems · XGBoost · FastAPI · Next.js · DevOps
</p>

<p align="center">
  <a href="https://linkedin.com/in/yusufbender">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/yusufbender">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <a href="https://instagram.com/bender.code">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Location-Bursa,_Turkey-orange?style=flat-square"/>
</p>

---

## About

Software developer with a background in DevOps and production infrastructure, now focused on AI/ML engineering.

I've spent years building containerized systems, observability stacks, and automation pipelines at T-LAB. My current work is in LLM applications, multi-agent architectures, and ML-powered financial analysis.

My AI journey started early — sentiment analysis with signal processing (FIR/IIR filters) in university, then computer vision with YOLOv5 for production quality control, then RAG systems, and now full multi-agent platforms.

**I learn by building real systems. Every project in my portfolio is production-oriented, not a tutorial clone.**

---

## Featured Projects

### 🧠 BenderEdge — Multi-Agent AI Stock Research Platform

5 specialized AI agents analyze stocks in parallel and vote on a BUY/SELL/HOLD verdict using weighted confidence scoring. Results stream in real-time via SSE.
```
Researcher  →  Live news + LLM analysis
Quant       →  RSI, MACD, Bollinger Bands, SMA, Volume
Sentiment   →  Headline tone scoring (-10 to +10)
BenderQuant →  On-the-fly XGBoost training + backtest
Portfolio   →  Weighted voting + confidence scoring
```

**Stack:** FastAPI · LangChain · Ollama (Qwen2.5:7b) · XGBoost · Next.js · SSE · yfinance · NewsAPI

👉 [github.com/yusufbender/BenderEdge](https://github.com/yusufbender/BenderEdge)

---

### 📈 BenderQuant — XGBoost Financial Classification Model

Buy/no-buy signal system trained on multi-ticker OHLCV data.

- Feature engineering: RSI · MACD · Bollinger Bands · EMA · SMA · Volume normalization · Trend crossover
- Model comparison: XGBoost vs Random Forest vs LightGBM vs CatBoost
- SMOTE oversampling · GridSearch hyperparameter tuning
- Backtest engine with Sharpe ratio, Max Drawdown, CAGR
- Cross-validation + classification report

**Stack:** Python · XGBoost · scikit-learn · pandas · yfinance

👉 [github.com/yusufbender/benderquant](https://github.com/yusufbender/benderquant)

---

### 🔍 BenderQuant Copilot — Offline RAG Architecture

Contextual AI assistant for quantitative research. Indexes financial content from Quantocracy and Quantpedia, answers questions via a local RAG pipeline.

- DeepSeek-R1:8b via Ollama
- Qdrant vector database + bge-m3 embeddings
- FastAPI backend
- Auto-crawling + chunking + embedding pipeline

**Stack:** Python · LangChain · Qdrant · FastAPI · Ollama · Docker

---

### 📡 Telemetry Stack — System Monitoring

End-to-end observability system for production infrastructure.

- Go agent collects system metrics
- FastAPI stores to InfluxDB
- Grafana dashboards for visualization
- Full Docker Compose stack

**Stack:** Go · FastAPI · InfluxDB · Grafana · Docker

👉 [github.com/yusufbender/telemetry-stack](https://github.com/yusufbender/telemetry-stack)

---

### 🔁 Bender Reverse Proxy

Production-grade dynamic reverse proxy with hot-reload.

- Round-robin load balancing
- Route-based authentication
- Rate limiting · Health checks · Path rewrite
- CI/CD with GitHub Actions

**Stack:** Go · Docker · GitHub Actions

👉 [github.com/yusufbender/bender-reverse-proxy](https://github.com/yusufbender/bender-reverse-proxy)

---

## Tech Stack

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-purple?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Observability & Infrastructure**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## Background

Before focusing on AI/ML, I built production systems at **T-LAB**:

- 🐳 Containerized stacks with Docker + Kubernetes
- 📊 Full observability pipelines (Grafana · Zabbix · InfluxDB · Prometheus)
- 📡 Real-time IoT data pipelines with ESP32 + MQTT + TimescaleDB
- 🤖 Computer vision system for production quality control (YOLOv5)
- 🔧 Automation with Python + Bash + GitHub Actions
- 🏭 ERP integration (Odoo XML-RPC + Qt interface)

This infrastructure background gives me a strong foundation for **deploying ML systems in production** — not just building them in notebooks.

---

## AI Journey
```
2020  Sentiment analysis from speech signals (FIR/IIR filters, MATLAB)
2019  License plate recognition with Raspberry Pi + OpenCV
2023  YOLOv5 object detection for production quality control
2023  IoT + real-time data pipelines at scale
2025  XGBoost financial classification (BenderQuant)
2025  Offline RAG architecture with DeepSeek + Qdrant
2026  Multi-agent LLM platform (BenderEdge)
      ↓
      Next: MLOps · Model serving · Geospatial ML (FinchGrid UK)
```

---

## Currently Working On

- 🧠 **BenderEdge** — multi-agent AI stock research platform
- 🗺️ **FinchGrid UK** — geospatial risk scoring with H3, XGBoost, RAG
- 📚 Deepening LLM agent architectures and tool use patterns

---

## What I'm Looking For

Actively looking for **AI Engineer / ML Engineer** roles focused on:

- LLM applications and multi-agent systems
- ML model development and deployment
- Intelligent data pipelines and RAG architectures

Open to **remote and hybrid** opportunities.

📫 Reach me on [LinkedIn](https://linkedin.com/in/yusufbender)

---

<p align="center">
  <i>"I learn by building real systems."</i>
</p>
