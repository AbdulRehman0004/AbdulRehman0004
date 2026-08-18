<!-- ╔══════════════════════════════ HEADER BANNER ══════════════════════════════╗ -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:2EC5FF&height=200&section=header&text=Abdul%20Rehman&fontColor=FFFFFF&fontSize=54&fontAlignY=38&desc=AI%20Agents%20%C2%B7%20LLM%20Automation%20%C2%B7%20Edge%20AI%20%C2%B7%20Computer%20Vision&descSize=18&descAlignY=60&descColor=C9D1D9&animation=fadeIn" alt="Abdul Rehman — AI Agents · LLM Automation · Edge AI · Computer Vision"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3200&pause=900&color=2EC5FF&center=true&vCenter=true&width=680&height=42&lines=I+build+AI+agents+and+automations+that+run+in+production;Structured+outputs+%C2%B7+evals+%C2%B7+fallbacks+%C2%B7+human+approval;Research+%E2%86%92+Production+%E2%86%92+the+Edge" alt="Typing SVG"/>

<br/>

### 🎓 AI Engineer @ AidAll Inc. · South Korea

[![Google Scholar](https://img.shields.io/badge/Scholar-92_Citations-1F6FEB?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=Ey1L1DAAAAAJ)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-rehman-204ba41ab/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbdulRehman0004)
[![Profile Views](https://komarev.com/ghpvc/?username=AbdulRehman0004&label=Profile%20Views&color=1F6FEB&style=for-the-badge)](https://github.com/AbdulRehman0004)

</div>

<!-- ╠══════════════════════════════ ABOUT ══════════════════════════════╣ -->

## 🚀 What I Do

I build AI systems that **ship** — agents and LLM automations with the guardrails a business can actually run on (schema-validated outputs, retries and fallbacks, eval harnesses, human approval gates), and models compiled down to hardware. Four areas:

<div align="center">

<table align="center">
<tr>
<td width="25%" align="center">🤖<br/><b>AI Agents</b><br/><sub>LangGraph · MCP · RAG · tool use</sub></td>
<td width="25%" align="center">⚙️<br/><b>LLM Automation</b><br/><sub>n8n · structured outputs · evals</sub></td>
<td width="25%" align="center">⚡<br/><b>Edge AI</b><br/><sub>Hailo-8 · ONNX · INT8</sub></td>
<td width="25%" align="center">👁️<br/><b>Computer Vision</b><br/><sub>ViT · Medical · Detection</sub></td>
</tr>
</table>

</div>

> *Most demos die at the prompt. I care about the part after the prompt — the schema, the retry, the eval, the approval gate, the run log, the thing that actually runs in front of a user.*

<!-- ╠══════════════════════════════ FEATURED WORK ══════════════════════════════╣ -->

## 🔥 Featured Work

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ [Shopify Product Content Engine](https://github.com/AbdulRehman0004/shopify-ai-content-engine)
An n8n pipeline that turns a bare product into a review-ready marketing kit (SEO, product page, blog, Google + Meta ads, social, email, hero image). **Structured Outputs**, idempotency gate, dry-run, per-product dead-letter, human approval — plus an **eval harness** (length caps, banned words, invented-fact detection, LLM judge) that gates CI and an **MCP server** so any agent can validate drafts and trigger runs.

`n8n` · `OpenAI` · `MCP` · `Evals` · `Python`

</td>
<td width="50%" valign="top">

### 🏢 [Agency OS — n8n automation system](https://github.com/AbdulRehman0004/agency-os-n8n)
Nine guard-railed workflows running a marketing agency over **Asana, Slack, Google Workspace, Airtable, HubSpot**: onboarding, status digests, creative review with Slack buttons, email triage, weekly reporting, bottleneck detection, meeting → tasks. Every AI call is schema-validated with one retry and a deterministic fallback; AI drafts, humans approve; CI enforces the conventions.

`n8n` · `gpt-4o` · `Airtable` · `Slack` · `HubSpot`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [RAG & Intelligent Agents](https://github.com/AbdulRehman0004/AI-Applications)
A **LangGraph** ReAct agent with multi-modal tools (documents, spreadsheets, audio, web, sandboxed code) and a **LlamaIndex + ChromaDB** RAG app, both with Streamlit UIs and Docker. Retrieval → reasoning → action, packaged to run.

`LangGraph` · `RAG` · `ChromaDB` · `Docker`

</td>
<td width="50%" valign="top">

### ⚡ [Edge AI — Hailo YOLOv8 → `.hef`](https://github.com/AbdulRehman0004/Efficient-AI-Deployment)
A reproducible cookbook that compiles a **custom Ultralytics YOLOv8** model into a deployable **Hailo-8** pipeline — ONNX parsing, calibration + fused NMS, and `.hef` compilation. Solves the gap the Hailo Model Zoo leaves open for custom detection heads.

`ONNX` · `Hailo DFC` · `INT8` · `NMS`

</td>
</tr>
</table>

<sub>Also: [Computer Vision & Medical AI research](https://github.com/AbdulRehman0004/AI-Research) backed by peer-reviewed publications · [GPT built from scratch](https://github.com/AbdulRehman0004/NLP/tree/main/Build_your_GPT).</sub>

<!-- ╠══════════════════════════════ CURRENTLY BUILDING ══════════════════════════════╣ -->

## 🎯 Currently Building

```yaml
Project:   edge-llm-bench  —  small-LLM inference benchmark suite for the edge
Devices:   Raspberry Pi 5 (ARM CPU)  ·  Jetson Orin Nano (GPU)  ·  x86 (baseline)
Runtimes:  llama.cpp  ·  TensorRT Edge-LLM (Jetson)  ·  a C++/CMake harness on llama.h
Metrics:   decode tok/s  ·  joules per token  ·  perf/watt  ·  WikiText-2 perplexity
Method:    predict from memory-bandwidth ceiling → measure → explain the gap
Goal:      a rigorous, reproducible answer to "which small LLM, on which edge device, at what energy cost?"
Status:    In active development 🚧  ·  building depth over breadth
```

<div align="center">
<sub>🔬 Research-grade methodology (power logging, variance, quant-vs-quality Pareto) meets production engineering (Docker, CI, JSON-schema results, C++ inference layer).</sub>
</div>

<!-- ╠══════════════════════════════ TECH STACK ══════════════════════════════╣ -->

## 🛠️ Tech Stack

<div align="center">

**Core**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**LLM & Agents**<br/>
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Edge & Deploy**<br/>
![Hailo-8](https://img.shields.io/badge/Hailo--8-00A9E0?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

<!-- ╠══════════════════════════════ GITHUB ACTIVITY ══════════════════════════════╣ -->

## 📊 GitHub Activity

<div align="center">

<img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=AbdulRehman0004&theme=tokyonight&hide_border=true&background=0D1117&ring=2EC5FF&fire=2EC5FF&currStreakLabel=2EC5FF&sideLabels=C9D1D9&dates=8B949E" alt="GitHub Streak"/>

</div>

<!--
  NOTE: github-readme-stats (stats + top-langs cards) is intentionally omitted.
  The public instance (github-readme-stats.vercel.app) is currently paused by
  its owner (503 DEPLOYMENT_PAUSED) — a known recurring 2025-2026 outage — so
  those cards would render as broken images. To add them back reliably, self-host
  your own instance on Vercel and swap the URL host. See:
  https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own-vercel-instance
-->

<div align="center">

[![Top Repos](https://img.shields.io/badge/Explore-My_Repositories-1F6FEB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbdulRehman0004?tab=repositories)

</div>

<!-- ╠══════════════════════════════ RESEARCH ══════════════════════════════╣ -->

## 📚 Research

<div align="center">

[![Citations](https://img.shields.io/badge/Google_Scholar-92_Citations-1F6FEB?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=Ey1L1DAAAAAJ)

**Deep Learning · Computer Vision · Medical AI · NLP**
[**View publications →**](https://scholar.google.com/citations?hl=en&user=Ey1L1DAAAAAJ)

</div>

<!-- ╠══════════════════════════════ CONNECT ══════════════════════════════╣ -->

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdul-rehman-204ba41ab/)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-1F6FEB?style=for-the-badge&logo=google-scholar&logoColor=white)](https://scholar.google.com/citations?hl=en&user=Ey1L1DAAAAAJ)
[![GitHub](https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AbdulRehman0004)

</div>

<!-- ╠══════════════════════════════ SIGNATURE ══════════════════════════════╣ -->

<br/>

<div align="center">

<!-- AR monogram signature -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1F6FEB,100:2EC5FF&height=52&width=120&text=AR&fontColor=FFFFFF&fontSize=30&fontAlignY=52" alt="AR"/>

*“From prompt to production — the part after the demo is the part that matters.”*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2EC5FF,50:1F6FEB,100:0D1117&height=100&section=footer" alt="footer"/>

</div>
