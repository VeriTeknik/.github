<div align="center">
  <img src="https://raw.githubusercontent.com/VeriTeknik/.github/refs/heads/main/profile/Veriteknik-logo.png" width="426" alt="VeriTeknik Logo" />
</div>

<div align="center">

**Knowledge · Memory · Tools — one control plane, every model**

[![GitHub followers](https://img.shields.io/github/followers/veriteknik?style=social)](https://github.com/veriteknik)
[![Website](https://img.shields.io/badge/Website-veritech.net-blue)](https://www.veritech.net/)
[![Twitter](https://img.shields.io/badge/Twitter-@VeriTeknik-1DA1F2?logo=twitter)](https://twitter.com/VeriTeknik)
[![Documentation](https://img.shields.io/badge/Docs-docs.plugged.in-green)](https://docs.plugged.in/)
[![Memory Essay](https://img.shields.io/badge/Essay-Memory%20Architecture-black?logo=medium)](https://medium.com/@cem.karaca/building-digital-consciousness-a-memory-architecture-inspired-by-human-cognition-437412791044)
[![PAP Essay](https://img.shields.io/badge/Essay-Kill%20Switch%20Protocol-red?logo=medium)](https://medium.com/@cem.karaca/pap-the-kill-switch-protocol-turning-ai-agents-from-loose-cannons-into-starfleet-d9aa531c4ca4?source=friends_link&sk=583966241e4e7c8529e459045fc2e176)

</div>

---

## 🎯 What We Do

VeriTeknik builds **plugged.in** — a model-agnostic layer that gives any AI system unified access to your:

- **📚 Knowledge** — Document ingestion, metadata, and retrieval (RAG) so answers cite *your* sources.
- **🧠 Memory** — Durable context that travels across tools and sessions (focus → short-term → long-term).
  - Our memory philosophy: causality-aware, tiered retention, and promotion/TTL policies.
    **Read the essay:** *Building Digital Consciousness: A Memory Architecture Inspired by Human Cognition* →
    https://medium.com/@cem.karaca/building-digital-consciousness-a-memory-architecture-inspired-by-human-cognition-437412791044
- **🔧 Tools** — Universal **MCP** (Model Context Protocol) orchestration: install once, use everywhere.

**Works with** Claude, ChatGPT, Cursor/Cline, VS Code, LM Studio, and more — without vendor lock-in.

---

## 🧭 Principles

- **Standards-first:** MCP • OAuth2/OIDC • JSON-RPC/JSON Schema
- **Governance:** workspaces, permissions, audit trails, export
- **Interoperability:** one tool/knowledge/memory layer across all clients

---

## 🎥 Watch Plugged.in Demo

[![Plugged In Demo](https://img.youtube.com/vi/iQBhMUUHpUQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=iQBhMUUHpUQ)

*Click the thumbnail to see plugged.in in action.*

---

## 🌟 The Plugged.in Ecosystem

### Core Platform

#### [pluggedin-app](https://github.com/veriteknik/pluggedin-app) ![v2.17.0](https://img.shields.io/badge/version-v2.17.0-blue)
*One Platform. All AI Models. Unlimited Possibilities.*

The hub for managing **Knowledge**, **Memory**, and **Tools** across any AI model.

- **Tech:** TypeScript, Next.js 15, PostgreSQL 18, React 19
- **Core Features:** Universal RAG, cross-model memory, MCP orchestration, 6-language i18n (en/tr/zh/hi/ja/nl)
- **License:** MIT ✨
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedin-app?style=social)](https://github.com/veriteknik/pluggedin-app)
[![GitHub forks](https://img.shields.io/github/forks/veriteknik/pluggedin-app?style=social)](https://github.com/veriteknik/pluggedin-app)

#### [pluggedin-mcp-proxy](https://github.com/veriteknik/pluggedin-mcp-proxy) ![v1.11.0](https://img.shields.io/badge/version-v1.11.0-blue)
*One MCP connection. Infinite tool access.*

Unified MCP proxy with streamable HTTP support, OAuth token management, and AI playground.

- **Tech:** TypeScript, Node.js, Express
- **Benefits:** Unified tool management, policy & governance, STDIO/SSE/HTTP support
- **License:** Apache-2.0
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedin-mcp-proxy?style=social)](https://github.com/veriteknik/pluggedin-mcp-proxy)
[![npm](https://img.shields.io/npm/v/@pluggedin/pluggedin-mcp-proxy)](https://www.npmjs.com/package/@pluggedin/pluggedin-mcp-proxy)

#### [plugged_in_v3_server](https://github.com/veriteknik/plugged_in_v3_server) ![v0.1.0](https://img.shields.io/badge/version-v0.1.0-blue)
*AI document management with RAG capabilities.*

FastAPI backend with vector search, real-time streaming chat, and document processing.

- **Tech:** Python 3.11+, FastAPI, Milvus, PostgreSQL, OpenAI GPT-4
- **Features:** PDF/DOCX processing, semantic search, context-aware responses, SSE streaming
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/plugged_in_v3_server?style=social)](https://github.com/veriteknik/plugged_in_v3_server)

---

### Official SDKs

Integrate plugged.in into your apps with official SDKs:

#### [pluggedinkit-js](https://github.com/VeriTeknik/pluggedinkit-js) ![v1.0.1](https://img.shields.io/badge/version-v1.0.1-blue)
JavaScript/TypeScript SDK for Node.js & browser

- **License:** MIT
- **Install:** `npm install pluggedinkit-js`
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedinkit-js?style=social)](https://github.com/veriteknik/pluggedinkit-js)
[![npm](https://img.shields.io/npm/v/pluggedinkit-js)](https://www.npmjs.com/package/pluggedinkit-js)

#### [pluggedinkit-python](https://github.com/VeriTeknik/pluggedinkit-python) ![v1.0.1](https://img.shields.io/badge/version-v1.0.1-blue)
Python SDK with sync/async clients for AI/ML workflows

- **License:** MIT
- **Install:** `pip install pluggedinkit`
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedinkit-python?style=social)](https://github.com/veriteknik/pluggedinkit-python)
[![PyPI](https://img.shields.io/pypi/v/pluggedinkit)](https://pypi.org/project/pluggedinkit/)

#### [pluggedinkit-go](https://github.com/VeriTeknik/pluggedinkit-go) ![Go 1.24+](https://img.shields.io/badge/go-1.24+-00ADD8)
High-performance Go SDK with full type safety

- **Install:** `go get github.com/veriteknik/pluggedinkit-go`
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedinkit-go?style=social)](https://github.com/veriteknik/pluggedinkit-go)

---

### Infrastructure

#### [registry-proxy](https://github.com/VeriTeknik/registry-proxy) ![v1.0.0](https://img.shields.io/badge/version-v1.0.0-blue)
*Enhanced MCP Registry with PostgreSQL backend and rating system.*

- **Tech:** Go (Gin), PostgreSQL, Traefik
- **Features:** Rating system, installation tracking, 1,600+ servers indexed
- **License:** MIT
- **Deployment:** https://registry.plugged.in
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/registry-proxy?style=social)](https://github.com/veriteknik/registry-proxy)

#### [pluggedin-docs](https://github.com/VeriTeknik/pluggedin-docs)
*Comprehensive platform documentation.*

- **Platform:** Mintlify
- **Content:** 60+ pages covering platform, SDKs, API reference, tutorials
- **Live:** https://docs.plugged.in
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedin-docs?style=social)](https://github.com/veriteknik/pluggedin-docs)

---

### 🆕 New: Observability & Protocol

#### [pluggedin-observability](https://github.com/VeriTeknik/pluggedin-observability) 🔥
*Production-grade full-stack observability for the Plugged.in ecosystem.*

Complete monitoring infrastructure with Prometheus, Grafana, Loki, and Traefik.

- **Stack:** Prometheus v2.48.0, Grafana v10.2.2, Loki v2.9.3, Traefik v2.10
- **Features:** Pre-configured dashboards, alert rules, log aggregation, metrics collection
- **Monitors:** pluggedin-app, pluggedin-mcp-proxy, RAG API, registry-proxy, PostgreSQL
- **Deployment:** https://monitoring.plugged.in
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/pluggedin-observability?style=social)](https://github.com/veriteknik/pluggedin-observability)

#### [PAP (Plugged.in Agent Protocol)](https://github.com/VeriTeknik/PAP) ![v1.0](https://img.shields.io/badge/RFC-v1.0%20Stable-success) 🚀
*Comprehensive framework for autonomous agent lifecycle management.*

**"Autonomy without anarchy"** — Agents run independently with Station oversight.

- **Status:** Stable Candidate (RFC-001 v1.0 Complete)
- **Protocol:** Protocol Buffers v3, gRPC/HTTP/2
- **Architecture:** Dual-profile (PAP-CP for control plane, PAP-Hooks for open I/O)
- **Key Innovation:** Zombie-prevention via strict heartbeat/metrics separation (the "kill switch protocol")
- **Security:** mTLS + Ed25519 signatures + OAuth 2.1 + DNS-based identity
- **Interoperability:** Native MCP tool support, A2A peer communication
- **SDKs Planned:** TypeScript, Python, Rust, Go
- **License:** Apache-2.0
[![GitHub Repo stars](https://img.shields.io/github/stars/veriteknik/PAP?style=social)](https://github.com/veriteknik/PAP)

**Read More:**
- **RFC Specification:** [Complete protocol specification](https://github.com/VeriTeknik/PAP) with lifecycle states, security model, and deployment architecture
- **The Kill Switch Protocol:** [Turning AI Agents from Loose Cannons into Starfleet](https://medium.com/@cem.karaca/pap-the-kill-switch-protocol-turning-ai-agents-from-loose-cannons-into-starfleet-d9aa531c4ca4?source=friends_link&sk=583966241e4e7c8529e459045fc2e176) — Deep dive into PAP's design philosophy

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                     Plugged.in Platform                      │
│                   (pluggedin-app v2.17.0)                    │
│         Knowledge · Memory · Tools · Collaboration           │
└─────────────────────┬───────────────────────────────────────┘
                      │
        ┌─────────────┴─────────────┐
        │                           │
┌───────▼─────────┐       ┌─────────▼──────────┐
│  MCP Proxy      │       │   RAG Backend      │
│  (v1.11.0)      │       │   (v0.1.0)         │
│  Port 8081      │       │   FastAPI+Milvus   │
│  STDIO/SSE/HTTP │       │   Vector Search    │
└─────────────────┘       └────────────────────┘
        │                           │
        └─────────────┬─────────────┘
                      │
        ┌─────────────▼─────────────┐
        │   PostgreSQL + Redis      │
        │   Shared Infrastructure   │
        └───────────────────────────┘

External Access:
├─ Official SDKs (JS/Python/Go) → API
├─ MCP Clients → MCP Proxy (port 8081)
└─ Observability → Prometheus + Grafana

Future: PAP Protocol
└─ Station ← PAP Proxy ← Autonomous Agents
```

---

## 📊 By the Numbers

- **11 Active Repositories** across 4 programming languages
- **1,600+ MCP Servers** indexed in registry
- **6 Languages** supported in platform (en, tr, zh, hi, ja, nl)
- **3 Production SDKs** (JavaScript, Python, Go)
- **4 Pre-configured Dashboards** in observability stack
- **v1.0 Protocol Specification** ready for autonomous agents

---

## 📚 Documentation & Resources

- **Documentation:** [docs.plugged.in](https://docs.plugged.in/) — Complete guides, API reference, tutorials
- **Registry:** [registry.plugged.in](https://registry.plugged.in/) — Browse 1,600+ MCP servers
- **Monitoring:** [monitoring.plugged.in](https://monitoring.plugged.in/) — Real-time observability
- **Memory Architecture Essay:** [Building Digital Consciousness](https://medium.com/@cem.karaca/building-digital-consciousness-a-memory-architecture-inspired-by-human-cognition-437412791044)
- **PAP Protocol:**
  - [RFC Specification](https://github.com/VeriTeknik/PAP) — Complete protocol documentation
  - [The Kill Switch Protocol](https://medium.com/@cem.karaca/pap-the-kill-switch-protocol-turning-ai-agents-from-loose-cannons-into-starfleet-d9aa531c4ca4?source=friends_link&sk=583966241e4e7c8529e459045fc2e176) — Design philosophy and vision

---

## 🤝 Contributing

We welcome contributions across the stack:

- **Core Platform:** New features, bug fixes, internationalization (6 languages supported)
- **MCP Integrations:** New server implementations, protocol improvements
- **SDKs:** Language bindings, examples, documentation
- **Observability:** Dashboard improvements, alert rules, instrumentation templates
- **PAP Protocol:** SDK implementations (TypeScript, Python, Rust, Go), testing, documentation

See each repository for specific contribution guidelines.

---

## 🔗 Quick Links

| Resource | URL |
|----------|-----|
| **Main Platform** | https://plugged.in |
| **Documentation** | https://docs.plugged.in |
| **MCP Registry** | https://registry.plugged.in |
| **Monitoring** | https://monitoring.plugged.in |
| **API Endpoint** | https://api.plugged.in |

---

## 📜 License

- **MIT Licensed:** pluggedin-app, pluggedinkit-js, pluggedinkit-python, registry-proxy
- **Apache-2.0:** pluggedin-mcp-proxy, PAP protocol

See individual repositories for detailed license information.

---

<div align="center">
  <em>Building the future of AI data exchanges — one protocol at a time.</em>

  **🚀 New: Full-stack observability + Autonomous agent protocol (PAP v1.0)**
</div>
