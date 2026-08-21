# Hi 👋, I'm Kaushik

**MS in AI Engineering @ Carnegie Mellon.** Previously Developer Associate at SAP Labs India.

I build production AI systems. Two years shipping RAG pipelines, agentic workflows, and infrastructure at SAP, now at CMU working on RL post-training for LLM agents.

## 🔭 Currently

Post-training LLM agents with SFT and GRPO on Meta and Hugging Face's OpenEnv spec.

Open to **Summer 2027 internships** in AI engineering, RL post-training, and ML infrastructure.

## 🚀 Selected Work

### Long-Horizon RL Benchmark for Clinical Trial Recruitment (2026)

A 180-step agentic RL environment built on the OpenEnv spec, with an 8-action tool interface and a multi-component reward across three difficulty tiers. I trained Qwen3-1.7B in TRL using SFT warmup followed by GRPO on LoRA adapters, and spent most of the project diagnosing policy collapse across five failed runs. Ten anti-collapse interventions raised tool calls per rollout from 3.5 to 11.

The writeup covers what failed as well as what worked, including the finding that the context window ceiling mattered more than any reward shaping.

### Antigravity AutoAccept, VS Code Extension (2026)

Automates AI agent file edits and terminal commands with zero configuration. **9,000+ downloads** on the Open VSX registry.

The IDE has no canonical accept command, so the extension runs five strategies: VS Code Extension API injection, event-driven polling, and a Chrome DevTools Protocol WebSocket fallback that traverses shadow DOM. Safety blocks prevent auto-approval of dangerous commands.

### Production RAG Platform at SAP (2024 to 2026)

A privacy-first retrieval pipeline over **2M+ indexed vectors**, serving 400+ users at sub-2s p95 latency. I fine-tuned DeBERTa-base for German PII entity extraction, and root-caused a ChromaDB performance regression with the upstream maintainers, fixing index cleanup and write-logging bottlenecks.

Presented at SAP's developer conference two years running, selected from **1,000+ submissions** in 2025 for the privacy-preserving chatbot work.

### Agentic AI for Database Operations at SAP (2026)

Co-developed three LangGraph-orchestrated systems for SAP HANA operations and security: closed-loop detect, analyze and remediate agents for system diagnostics, self-healing infrastructure sub-agents, and a multi-agent security pipeline that classifies findings against OWASP and CVSS before generating refactored code.

### Real-time Multimedia File Indexer (2022 to 2023)

A multi-format ingestion pipeline routing 25+ file types through format-specific extractors, including OCR for images embedded in documents and Hindi and English speech-to-text.

**1st Place**, Smart India Hackathon National Grand Finale (Ministry of Education, India). Deployed by Madhya Pradesh Police.

## 📄 Publications

Two IEEE papers on machine learning based intrusion detection for autonomous vehicles, and swarm intelligence for intelligent transportation systems.

## 💻 Tech

**Languages** · Python, Go, TypeScript

**ML and Post-Training** · GRPO, SFT, LoRA, TRL, PyTorch, Hugging Face, OpenEnv, DeBERTa, Qwen3, RAG, LangGraph

**Infrastructure** · FastAPI, React, Docker, Jenkins, ChromaDB, Nginx

**Cloud** · Google Cloud Platform, Microsoft Azure, OpenStack

## 🏆 Recognition

**SAP Early Talent Board 2025.** Selected 1 of 24 globally. Led a three-person team across Germany, India and the Netherlands, and presented to 17+ senior leaders including an Executive Board member.

**Best Outgoing Student**, IT Department, PSG College of Technology. CGPA 9.54/10, ranked 4 of 136.

**1st Place**, Smart India Hackathon National Grand Finale 2022.

**Top 12 of 496 teams**, GE HealthCare Precision Care Hackathon.

**Excellence Award**, Samsung PRISM Research Initiative.

## 🔗 Connect

📧 [kaushik.s.saravanan@gmail.com](mailto:kaushik.s.saravanan@gmail.com) ·
💼 [LinkedIn](https://linkedin.com/in/kaushiksss) ·
🌐 [Portfolio](https://kaushiksaravanan.vercel.app/) ·
📝 [Blog](https://ampersnow.substack.com/)
