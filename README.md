# Hi, I'm Yang Li 👋

**Platform Engineer by day ☀️ | GenAI/AI-ML Enthusiast by night 🌙**

VP Technical Lead @ Barclays | MBA, MSc

> "Learn to conduct, not play" - orchestrate AI, don't type every line yourself

---

## 🚀 About Me

**By day**, I architect and build enterprise platforms at scale. **By night**, I explore the frontiers of GenAI, building agents, RAG systems, and AI-powered tools that push boundaries.

I believe in the power of **AI augmentation** - one person + AI can replace a 5-person team. My mission: democratize AI development and prove that speed beats perfection.
Personal projects demonstrating GenAI, LLM systems, RAG, agentic AI, and full-stack deployment. All open-source on GitHub: [github.com/ly2xxx](https://github.com/ly2xxx)

## 💡 Core Philosophy: Pragmatic, Real-World AI & Engineering
* **Problem-First, Not Tech-First:** I build tools that solve actual friction points. For example, [netshare](#2-netshare--secure-local-wifi-file-sharing-tool) bridges local network sharing for VR headsets, and [GCO](#4-gco-glasgow-chinese-open--community-golf-league-dashboard) runs live in production serving a local community daily.
* **Aggressive Anti-Over-Engineering:** I value shipping velocity and simple runtime states over unnecessary enterprise complexity (e.g., using lightweight JSON states & Streamlit for [GCO](#4-gco-glasgow-chinese-open--community-golf-league-dashboard) or launching the **QR-Greeting** funnel in 48 hours).
* **AI & "Vibe Coding" as a Velocity Multiplier:** I adapt rapidly to new ecosystems by orchestrating GenAI tools, transitioning from Streamlit to full-stack React/[Next.js](#5-event-market--event-sponsor-marketplace-mvp) ([event-market](#5-event-market--event-sponsor-marketplace-mvp)) in under a week with zero prior framework knowledge.
* **Local-First & Privacy-Focused:** I prioritize privacy and direct connections (like self-hosted models in [local-rag-ollama](#7-local-rag-ollama--chatpdf-running-locally) and local MCP contexts in [md-mcp](#1-md-mcp--mcp-server-for-local-markdown-files)).

---

## 🏆 Flagship Projects

### 0. md-mcp — MCP Server for Local Markdown Files
**GitHub:** https://github.com/ly2xxx/md-mcp
**Live:** https://pypi.org/project/md-mcp/ | Published v1.0.x March 2026
**Live:** https://hub.docker.com/r/ly2xxx/md-mcp | Published v1.0.x June 2026
**Stack:** Python, MCP (Model Context Protocol), LLM tooling, docker with k8s(soon), gh CI, Pytest-BDD

Transforms prompt engineering into context engineering — makes local markdown files instantly available to any LLM as context. Built with the Model Context Protocol, published to PyPI, supports multiple LLM providers.

---
### 1. langgraph_ollama — Local Multi-Agent & RAG System

**GitHub:** https://github.com/ly2xxx/langgraph_ollama
**Stack:** Python, LangGraph, LangChain, SQLite (Checkpointing), FAISS (Vector DB), Ollama (Local LLMs), Streamlit

A local multi-agent system showcasing advanced agentic workflows and RAG retrieval over self-hosted LLMs. Implements a LangGraph `StateGraph` using a supervisor/agent-node pattern, SQLite-backed persistent checkpointing for conversation history, dynamically generated conversation summarization, a dedicated RAG agent powered by FAISS, and multimodal capabilities supporting base64 image inputs.

---
### 2. netshare — Secure Local WiFi File Sharing Tool
**GitHub:** https://github.com/ly2xxx/netshare
**Live:** https://pypi.org/project/netshare/ | Published v1.0.x January 2026
**Live:** https://qr-greeting.streamlit.app/ | Marketing Funnel & Product Demo
**Read:** https://edisonideas.wordpress.com/2025/12/15/how-i-built-marketed-and-launched-a-product-in-48-hours-using-ai-no-team-required/ | 48-Hour Solopreneur/AI Launch Case Study
**Stack:** Python, Flask, Tkinter (GUI), qrcode, HTML/CSS, PowerShell (Firewall utility), Streamlit (Funnel app)

Enables secure, easy folder sharing from host computers (Windows, macOS, Linux) to mobile, tablet, and Quest VR devices over a local WiFi network. Features a graphical folder picker, instant QR code generation for mobile devices, and robust security controls (rate limiting, file extension filtering, and path traversal protection).

**Marketing & Solopreneur Launch:** Spun off a consumer greeting-card product, **QR-Greeting**, built on top of this engine. Hand-launched the product and marketing funnel as a "one-man-company" experimental weekend project with my daughter within 48 hours, leveraging GenAI tools for rapid development, design, and marketing content.

---

### 3. aidev — MCP-Based Development Crew
**GitHub:** https://github.com/ly2xxx/aidev
**Read:** https://edisonideas.wordpress.com/2025/06/28/the-next-level-of-ai-powered-development-building-my-genai-development-crew/
**Stack:** MCP, Claude Code, Gemini CLI, Docker

Orchestrates multiple AI agents (Claude + Gemini) via MCP to act as a development crew — planning, coding, reviewing, containerizing. Accompanied by YouTube walkthrough videos.

---

### 4. GCO (Glasgow Chinese Open) — Community Golf League Dashboard
**GitHub:** https://github.com/ly2xxx/gco
**Live:** https://gco-2026.streamlit.app/ | Streamlit Cloud Deployment
**Stack:** Python, Streamlit, Pandas, Plotly, JSON (State Management), Pytest/BDD, UV

Tracks announcements, handicaps, round scoring, league standings, cup tournaments, and team matchups for the Glasgow Southside Chinese Golf community. This was my first "vibe coded" (fully LLM-assisted) application that moved from concept to production, and it is now actively used daily by the local community.

---

### 5. event-market — Event Sponsor Marketplace MVP
**GitHub:** https://github.com/ly2xxx/event-market
**Live:** https://vercel.com/ly2xxxs-projects/event-market | Deployed on Vercel
**Stack:** React, Next.js, TypeScript, TailwindCSS, PostCSS, Vercel

A sponsor marketplace MVP allowing organizers to list events and sponsors to browse opportunities. This project was my first venture into React and Next.js, developed purely through "vibe coding" (LLM-driven development) without any prior web framework knowledge. It represents a hands-on transition from python/streamlit script-based top-down architectures to component-based stateful web applications.

---

## 🔧 Solid Supporting Projects

### 6. langraph — Multi-Agent Research Workflows
**GitHub:** https://github.com/ly2xxx/langraph
**Stack:** Python, LangGraph, LangChain, OpenAI API, AWS Bedrock, Streamlit, Jupyter Notebooks

An experimental codebase for building stateful, multi-agent workflows using LangGraph and LangChain. Implements agent patterns such as a multi-agent news researcher/analyst system with state machine routing, dynamic tool calling, and human-in-the-loop validation. Deployed with Streamlit and Jupyter interfaces to visualize agent state transitions and graph nodes.

---

### 7. local-rag-ollama — ChatPDF Running Locally
**GitHub:** https://github.com/ly2xxx/local-rag-ollama
**Stack:** LangChain, Ollama, Python

Build your own ChatPDF — fully offline. Upload documents, get grounded answers from local LLM with no data leaving your machine.

---

### 8. HR-toolkit — GenAI for Talent Management
**Live:** https://hrtoolkit.streamlit.app
**GitHub:** https://github.com/ly2xxx/hrtoolkit/
**Stack:** Streamlit, Python, GenAI

Deploys multiple GenAI tools for HR workflows — resume screening, interview prep, job description generation.

---

### 9. Global Treasure Hunt — AI Research Tool
**Live:** https://globaltreasurehunt.streamlit.app
**GitHub:** https://github.com/ly2xxx/treasure/
**Stack:** Streamlit, Python, LLM research pipelines

AI-powered research tool for exploring historical/problem-solving topics — demonstrates ability to build and deploy consumer-facing AI tools.

---

### 10. DevOps-labs — Infrastructure-as-Code & Kubernetes
**GitHub:** https://github.com/ly2xxx/DevOps-labs
**Stack:** PowerShell, Kubernetes, Helm, CRC/OKD, Vault

Hands-on DevOps learning labs — secrets rotation, Kubernetes deployments, infrastructure automation.

---

## 📊 Summary by Skill Area

| Skill                            | Projects                                                     |
| -------------------------------- | ------------------------------------------------------------ |
| **LLM / RAG / Agentic AI** | langgraph_ollama, aidev, md-mcp, langraph, browser-use       |
| **MCP Protocol**           | md-mcp, aidev                                                |
| **Python / PyPI**          | md-mcp, netshare (published packages)                        |
| **Local AI / Ollama**      | langgraph_ollama, local-rag-ollama                           |
| **Deployment / Streamlit** | HR-toolkit, Global Treasure Hunt, qr-greeting, GCO, langraph, langgraph_ollama |
| **Browser Automation**     | browser-use, flight monitoring                               |
| **React / Next.js / Web**  | event-market 

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ly2xxx&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

<p align="center">
  <i>✨ "The best way to predict the future is to build it." ✨</i>
</p>
