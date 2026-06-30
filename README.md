# Walid Hassan Tahrim

**Full-Stack Software Engineer | Backend · Cloud · Edge AI · Local LLM Infrastructure**<br>
**Aspiring Cloud & Network Infrastructure Engineer**

I am a Software Engineering graduate (TAMK, May 2026) with a keen interest in the invisible layers of tech: cloud architecture, infrastructure security, networking, and embedded hardware. I like connecting the gap between intelligent software systems and raw, physical hardware — building backend systems, cloud infrastructure, and local AI pipelines that work in the real world, not just in demos.

Currently building out hands-on enterprise-grade topologies, deploying custom Linux homelabs, and automating systems from the ground up. Pursuing AZ-104 (Azure Administrator Associate).

**Portfolio:** [your-portfolio-domain.com] *(live)*&nbsp;&nbsp;·&nbsp;&nbsp;**Email:** tahrimwalid@gmail.com&nbsp;&nbsp;·&nbsp;&nbsp;**LinkedIn:** [walid-hassan-tahrim](https://www.linkedin.com/in/walid-hassan-tahrim)&nbsp;&nbsp;·&nbsp;&nbsp;Tampere, Finland

---

## I am working with...

**Languages & Scripting**

[![My Skills](https://skillicons.dev/icons?i=py,js,ts,java,kotlin,bash,arduino)](https://skillicons.dev)

**Frontend & Infrastructure-as-Code**

[![My Skills](https://skillicons.dev/icons?i=react,nextjs,vercel,terraform)](https://skillicons.dev)

**Systems, Cloud & DevOps**

[![My Skills](https://skillicons.dev/icons?i=linux,docker,git,aws,azure,cloudflare)](https://skillicons.dev)

**AI & Edge (custom badges — not on skillicons)**

![Llama.cpp](https://img.shields.io/badge/Llama.cpp-000000?style=flat-square&logo=meta&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-6C3EFF?style=flat-square&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen-5C3EE8?style=flat-square&logoColor=white)
![4-bit Quantization](https://img.shields.io/badge/4--bit%20Quantization-FF6B35?style=flat-square&logoColor=white)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square&logo=arm&logoColor=white)

---

## The Tech Matrix

**Networking & Cloud Security**
Cisco IOS, Subnetting, Routing Protocols (OSPF, BGP) *(active track)* · Secure Remote Access, VPN Tunneling, Network Hardening

**Systems & Infrastructure**
Linux (Ubuntu, Debian, Server Administration) · Docker, Containerized Microservices · Physical Server Architecture, Custom Homelab Deployment & Hardware Engineering

**Artificial Intelligence & Machine Learning**
Open-source LLM tweaking, prompt engineering, and LLM orchestration (e.g. Kratos) · Retrieval-Augmented Generation (RAG) architectures for localized or deployed data processing · 4-bit quantization, ARM & GPU deployment

**Programming & Automation**
Python, Bash Scripting · Arduino C++ · JavaScript, TypeScript · Java, Kotlin

---

## Featured Projects

### [Kratos](https://github.com/TahrimWalid/kratos) — Offline AI Security Analysis System
*Bachelor's Thesis*

A fully offline, five-stage security pipeline (scan → log parsing → system context → correlation → LLM analysis) running Qwen2.5-Coder 7B via Llama.cpp on ARM hardware. Zero external API calls. 10 correlation rules including sliding-window SSH burst detection and baseline drift detection. Daemon mode cuts repeated query latency from ~2 minutes to 10–20 seconds. Structured output (Observation → Evidence → Risk → Action) forces evidence-backed findings over generic advice.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Llama.cpp](https://img.shields.io/badge/Llama.cpp-000000?style=flat-square&logo=meta&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ARM](https://img.shields.io/badge/ARM-0091BD?style=flat-square&logo=arm&logoColor=white)

---

### [InGen](https://github.com/TahrimWalid/in-gen) — AI-Powered AWS Infrastructure Compiler
**Live:** [in-gen-five.vercel.app](https://in-gen-five.vercel.app)

A visual AWS architecture designer (ReactFlow) that validates against 32 deterministic rules and compiles to production-ready Terraform HCL. Bidirectional sync between diagram and code via Monaco, 800ms debounced, with loop prevention. AI layer runs on self-hosted Qwen3-27B-FP8 via vLLM, scoring 10/10 on complex 12-resource serverless architectures.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-6C3EFF?style=flat-square&logoColor=white)

---

### [Career AI](https://github.com/TahrimWalid/career-ai) — Finnish IT Job Market Analysis Pipeline

A 5-phase ETL pipeline scraping ~2,000 Finnish IT job postings via a reverse-engineered undocumented API, processed with a local LLM into 1,998 structured records (96.7% hydration, 100% extraction success). Mid-project, identified and documented a deduplication strategy that swung a key bias metric from 5% to 82.5% to 4.5% across three technically valid runs — prioritizing honest unmeasurability over false precision.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

---

### Oppipolku — Course Benchmarking Platform for Finnish Universities
*€5,000 funded by the TAMK Foundation · team project · private repo*

Built the backend benchmarking layer: 40+ REST API endpoints across 9 functional categories (market benchmarks, org comparisons, rankings, gap analysis, trend tracking) designed retrieval-first so an LLM grounds every benchmarking claim in live structured data rather than general knowledge. Deployed as a systemd daemon behind Cloudflare Tunnel and Apache on Ubuntu.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)

*(Code available on request)*

---

## Current Focus & Journey

- **Deep-diving into networking:** building advanced virtual network topologies using GNS3/EVE-NG to master routing, switching, and core protocols for the CCNA track
- **Homelab hacking:** re-engineering low-power, small-form-factor server nodes to house multi-drive high-density storage arrays via PCIe expansion lanes
- **DevOps & cloud:** automating local deployments with Bash and Docker to replicate cloud-native environments locally
- **Cloud certification:** pursuing AZ-104, redeploying Career AI's pipeline onto Azure infrastructure as hands-on practice

---

*Tampere, Finland — open to backend, cloud, and data engineering roles.*
