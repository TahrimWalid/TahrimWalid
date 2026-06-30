# Walid Hassan Tahrim

**Full-Stack Software Engineer | Backend · Cloud · Edge AI · Local LLM Infrastructure**

**Aspiring Cloud & Network Infrastructure Engineer**

I am a Software Engineering graduate (TAMK, May 2026) with a keen interest in the invisible layers of tech: cloud architecture, infrastructure security, networking, and embedded hardware. I like connecting the gap between intelligent software systems and raw, physical hardware — building backend systems, cloud infrastructure, and local AI pipelines that work in the real world, not just in demos.

Currently building out hands-on enterprise-grade topologies, deploying custom Linux homelabs, and automating systems from the ground up. Pursuing AZ-104 (Azure Administrator Associate).

**Portfolio:** [your-portfolio-domain.com] *(live)*
**Contact:** tahrimwalid@gmail.com · [LinkedIn](https://www.linkedin.com/in/walid-hassan-tahrim) · Tampere, Finland

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
`Python` `Qwen2.5-Coder 7B` `Llama.cpp` `ARM` `Linux`

### [InGen](https://github.com/TahrimWalid/in-gen) — AI-Powered AWS Infrastructure Compiler
A visual AWS architecture designer (ReactFlow) that validates against 32 deterministic rules and compiles to production-ready Terraform HCL. Bidirectional sync between diagram and code via Monaco, 800ms debounced, with loop prevention. AI layer runs on self-hosted Qwen3-27B-FP8 via vLLM, scoring 10/10 on complex 12-resource serverless architectures.
`Next.js` `React` `ReactFlow` `Terraform` `Qwen3-27B-FP8` `vLLM`
**Live:** [in-gen-five.vercel.app](https://in-gen-five.vercel.app)

### [Career AI](https://github.com/TahrimWalid/career-ai) — Finnish IT Job Market Analysis Pipeline
A 5-phase ETL pipeline scraping ~2,000 Finnish IT job postings via a reverse-engineered API, processed with a local LLM into 1,998 structured records (96.7% hydration, 100% extraction success). Mid-project, identified and documented a deduplication strategy that swung a key bias metric from 5% to 82.5% to 4.5% across three technically valid runs — prioritizing honest unmeasurability over false precision.
`Python` `SQLite` `Ollama` `Qwen 2.5 3B` `Pydantic`

### Oppipolku — Course Benchmarking Platform for Finnish Universities
*€5,000 funded by the TAMK Foundation · team project*
Built the backend benchmarking layer: 40+ REST API endpoints across 9 categories (market benchmarks, org comparisons, rankings, gap analysis, trend tracking) giving an LLM grounded, traceable data to reason from instead of general knowledge. Deployed as a systemd daemon behind Cloudflare Tunnel and Apache on Ubuntu.
`Python` `REST APIs` `Linux` `Cloudflare Tunnel` `Apache` `systemd`
*(Private repo — code available on request)*

---

## Current Focus & Journey

- **Deep-diving into networking:** building advanced virtual network topologies using GNS3/EVE-NG to master routing, switching, and core protocols for the CCNA track
- **Homelab hacking:** re-engineering low-power, small-form-factor server nodes to house multi-drive high-density storage arrays via PCIe expansion lanes
- **DevOps & cloud:** automating local deployments with Bash and Docker to replicate cloud-native environments locally
- **Cloud certification:** pursuing AZ-104, redeploying Career AI's pipeline onto Azure infrastructure as hands-on practice

---

*Tampere, Finland — open to backend, cloud, and data engineering roles.*
