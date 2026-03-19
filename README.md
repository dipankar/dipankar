# Dipankar Sarkar

**Builder · Systems Architect · OSS Researcher**

I build high-performance infrastructure tools in **Rust** and **Zig**, with a focus on developer tooling, AI agent infrastructure, and blockchain systems. Based in Scotland, I work across three open-source organisations shipping production-grade tools that replace slow incumbents with fast, correct alternatives.

🌐 [dipankar.name](https://dipankar.name) · 📧 [me@dipankar.name](mailto:me@dipankar.name) · 🐦 [@dipankarsarkar](https://twitter.com/dipankarsarkar) · 📚 [Publications](https://scholar.google.com/citations?user=t_ikr2UAAAAJ&hl=en)

---

## Organisations

### 🔬 [Neul Labs](https://github.com/neul-labs) — Agent-Focused AI Infrastructure

Neul Labs is where I concentrate my work on **high-performance tooling for AI agents and LLM-powered applications**. The thesis is simple: the Python-native AI stack is too slow for production agent workloads. These tools provide Rust-accelerated drop-in replacements and novel orchestration primitives for the agentic AI ecosystem.

| Tool | What it does | Lang |
|------|-------------|------|
| [**brat**](https://github.com/neul-labs/brat) | Multi-agent harness for AI coding tools — crash-safe state, parallel execution, one CLI. Orchestrates Claude, Aider, OpenCode, Codex, and others. | Rust |
| [**fast-litellm**](https://github.com/neul-labs/fast-litellm) | Rust-accelerated drop-in replacement for LiteLLM. 3.2× faster connection pooling via PyO3 with zero config. | Rust/Python |
| [**fast-langgraph**](https://github.com/neul-labs/fast-langgraph) | Rust accelerators for LangGraph — up to 700× faster checkpoint operations and 10–50× faster state management. | Rust/Python |
| [**gity**](https://github.com/neul-labs/gity) | Makes large Git repos feel instant. Daemon-based fsmonitor + warm caching turns 8s `git status` into milliseconds. | Rust |
| [**stout**](https://github.com/neul-labs/stout) | Drop-in Homebrew CLI replacement, 10–100× faster. SQLite FTS5 index, parallel downloads, Ed25519 signed updates, CVE auditing. | Rust |
| [**fastworker**](https://github.com/neul-labs/fastworker) | Background workers for Python apps in seconds, without the complexity. | Python |

> **Why this matters for agents:** As AI agents move from demo to production, they need infrastructure that can handle thousands of concurrent LLM calls, checkpoint complex multi-step workflows without losing state, and orchestrate multiple coding engines in parallel. Neul Labs tools are the plumbing that makes this possible — Rust where it counts, Python where it's convenient.

---

### 🧪 [Skelf Research](https://github.com/skelf-research) — Systems Research & Developer Tools

Skelf Research is the broader research org, building tools across systems programming, quantitative finance, AI/ML, and constraint solving.

| Tool | What it does | Lang |
|------|-------------|------|
| [**sigc**](https://github.com/Skelf-Research/sigc) | The Quant's Compiler — from alpha idea to production trading strategy in minutes. | Rust |
| [**numaperf**](https://github.com/Skelf-Research/numaperf) | NUMA-first runtime for latency-critical Rust applications. | Rust |
| [**fastC**](https://github.com/Skelf-Research/fastC) | C, but safe and agent-friendly. | Rust |
| [**polymathy**](https://github.com/Skelf-Research/polymathy) | Rust web service transforming traditional search into an answer engine. | Rust |
| [**zviz**](https://github.com/Skelf-Research/zviz) | Container isolation for code you can't trust but have to run. | Zig |
| [**route-switch**](https://github.com/Skelf-Research/route-switch) | Intelligent LLM routing with automatic prompt optimisation. | Go |
| [**promptel**](https://github.com/Skelf-Research/promptel) | Declarative prompt engineering — write once, run anywhere. | JavaScript |
| [**blogus**](https://github.com/Skelf-Research/blogus) | Extract prompts from your codebase, version them like dependencies, keep everything in sync. | Python |
| [**savanty**](https://github.com/Skelf-Research/savanty) | Natural language to constraint solver — describe optimisation problems in English, get mathematically guaranteed solutions. | Python |
| [**compere**](https://github.com/Skelf-Research/compere) | Intelligent pairwise comparisons — better rankings with fewer votes. | Python |
| [**mullama**](https://github.com/Skelf-Research/mullama) | Drop-in Ollama replacement. All-in-one local LLM toolkit. | Python |
| [**llamafu**](https://github.com/Skelf-Research/llamafu) | Run AI models directly on mobile devices. No cloud, no latency, complete privacy. | Dart |
| [**liath**](https://github.com/Skelf-Research/liath) | A programmable database that speaks Lua. Store data, run queries, build AI workflows. | Lua |

---

### ⛓️ [Cryptuon Research](https://github.com/cryptuon) — Blockchain Infrastructure & Protocols

Research-driven blockchain tooling, from smart contract compilers to cross-chain protocols. Our paper *"Towards Universal Atomic Composability"* was recognised by a16z's crypto startup school.

| Tool | What it does | Lang |
|------|-------------|------|
| [**solscript**](https://github.com/cryptuon/solscript) | Write Solidity, deploy to Solana. Transpiler with full Anchor compatibility — no Rust required. | Rust |
| [**zig-evm**](https://github.com/cryptuon/zig-evm) | Experimental EVM implementation in Zig. | Zig |
| [**stxscript**](https://github.com/cryptuon/stxscript) | StxScript-to-Clarity transpiler for Stacks smart contract development. | Python |
| [**tesseract**](https://github.com/cryptuon/tesseract) | Multi-rollup environments on Ethereum — enabling atomic transactions across rollups. | — |

---

## What I'm Building Towards

The common thread across all three orgs is **making fast, correct infrastructure for the next generation of software** — whether that's AI agents that need sub-millisecond checkpoint recovery, quant strategies that need NUMA-aware execution, or cross-chain transactions that need formal correctness guarantees.

My current focus at **Neul Labs** is on the agent infrastructure layer: the tools that sit between LLM providers and production applications, making agentic workflows fast, observable, and crash-safe.

---

## Background

- **M.S. Computer Science**, Arizona State University · **B.Tech**, IIT Delhi
- Author of *Nginx 1 Web Server Implementation Cookbook* (Packt)
- Running [Neul Labs](https://www.neul.uk) · St Andrews, Scotland

---

*Open to research collaborations, advisory roles, and conversations about high-performance AI infrastructure.*
