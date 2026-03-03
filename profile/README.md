<div align="center">

<img src="https://raw.githubusercontent.com/VeriTeknik/.github/refs/heads/main/profile/pluggedin-logo.png" width="200" alt="plugged.in" />

### AI memory that grows with you.

**Persistent memory · Collective intelligence · Jungian archetypes**

[![Plugin Version](https://img.shields.io/badge/plugin-v1.0.0-blue)](https://github.com/VeriTeknik/pluggedin-plugin)
[![Platform Version](https://img.shields.io/badge/platform-v3.2.0-blue)](https://github.com/VeriTeknik/pluggedin-app)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/VeriTeknik/pluggedin-plugin/blob/main/LICENSE)
[![Docs](https://img.shields.io/badge/docs-docs.plugged.in-brightgreen)](https://docs.plugged.in)

[Website](https://plugged.in) · [Documentation](https://docs.plugged.in) · [Plugin Repo](https://github.com/VeriTeknik/pluggedin-plugin) · [Platform Repo](https://github.com/VeriTeknik/pluggedin-app)

</div>

---

## Install

```
/plugin marketplace add VeriTeknik/pluggedin-plugin
/plugin install pluggedin@VeriTeknik-pluggedin-plugin
```

Then run `/pluggedin:setup` — a browser opens, you authorize, done. No key copying.

---

## What happens when you install

Your AI stops being an amnesiac.

**Memory sessions start automatically.** Every tool call, error, decision, and insight is captured — across sessions, across projects. Memories decay naturally through compression stages, just like biological memory: what you reinforce survives, what you don't fades gracefully.

**Collective intelligence kicks in.** Patterns discovered by other developers surface in your context. A Docker permission fix found by 15 different people becomes one authoritative guide — delivered to you before you even hit the error. Privacy-preserving by design: HMAC-SHA256 identity erasure, k-anonymity, no exact timestamps in the collective layer.

**Four Jungian archetypes guide every response:**

| Archetype | Role | Example |
|-----------|------|---------|
| 🔴 **Shadow** | Warns of dangers | _"Friday afternoon deploys fail 3.4x more often across your org"_ |
| 🔵 **Sage** | Offers proven solutions | _"Docker volume permission errors: fix with `chmod 755` on host dir"_ |
| 🟡 **Hero** | Provides complete workflows | _"Deploy → verify → rollback sequence for your K8s pipeline"_ |
| 🟣 **Trickster** | Flags hidden edge cases | _"This namespace config silently drops health checks under load"_ |

**Your AI's growth is measurable.** The individuation score (0–100) tracks Memory Depth, Learning Velocity, Collective Contribution, and Self-Awareness. New team members inherit collective wisdom from day one.

---

## What you get

| Category | Count | Highlights |
|----------|-------|------------|
| **MCP Tools** | 24 | Memory, knowledge base, clipboard, documents, notifications, discovery |
| **Slash Commands** | 9 | `/pluggedin:setup`, `/pluggedin:status`, `/pluggedin:memory-search`, and more |
| **Lifecycle Hooks** | 5 | SessionStart, PreToolUse, PostToolUse, PreCompact, Stop — all automatic |
| **Background Agents** | 2 | Memory Curator (classifies observations) + Focus Assistant (working set) |

### Key capabilities

- **Synchronicity Detection** — Discovers temporal patterns across users automatically
- **Dream Processing** — Consolidates fragmented memories during quiet periods (92% token reduction)
- **Archetype Router** — Deterministic pattern delivery, no LLM overhead
- **Individuation Metrics** — Per-profile maturity scoring with growth tracking
- **RAG Knowledge Base** — Query your uploaded documents from within Claude Code
- **Cross-Agent Clipboard** — Pass data between agents and sessions
- **Progressive Disclosure** — Summaries first, full details on demand (~10x token savings)

---

## How it works

```
Claude Code session starts
       │
       ▼
  ┌─────────────────┐
  │  SessionStart    │── Memory session created, individuation score shown
  └────────┬────────┘
           │
           ▼
  ┌─────────────────┐
  │  PreToolUse      │── Archetype patterns injected (Shadow/Sage/Hero/Trickster)
  └────────┬────────┘
           │
           ▼
  ┌─────────────────┐
  │  PostToolUse     │── Observations captured, temporal events recorded
  └────────┬────────┘
           │
           ▼
  ┌─────────────────┐
  │  PreCompact      │── Relevant memories injected before context compression
  └────────┬────────┘
           │
           ▼
  ┌─────────────────┐
  │  Stop            │── Session ended, Z-report generated
  └─────────────────┘
```

Zero configuration. Everything runs automatically through lifecycle hooks.

---

## The platform behind the plugin

The plugin connects to **[plugged.in](https://plugged.in)** — an open-source AI infrastructure platform.

| Component | Purpose |
|-----------|---------|
| [**pluggedin-app**](https://github.com/VeriTeknik/pluggedin-app) | Core platform — Next.js 15, PostgreSQL, 50+ tables |
| [**pluggedin-mcp**](https://github.com/VeriTeknik/pluggedin-mcp-proxy) | MCP proxy — 1,500+ tool integrations |
| [**SDKs**](https://docs.plugged.in/sdks) | JavaScript, Python, Go |
| [**PAP**](https://github.com/VeriTeknik/PAP) | Agent Protocol — autonomous agent lifecycle management |
| [**Docs**](https://docs.plugged.in) | 60+ pages of documentation |

---

## Links

| | |
|---|---|
| **Plugin** | [github.com/VeriTeknik/pluggedin-plugin](https://github.com/VeriTeknik/pluggedin-plugin) |
| **Platform** | [plugged.in](https://plugged.in) |
| **Documentation** | [docs.plugged.in](https://docs.plugged.in) |
| **MCP Registry** | [registry.plugged.in](https://registry.plugged.in) — 1,600+ servers |
| **Technical Article** | [Building the Collective Unconscious of Machines](https://docs.plugged.in/articles/jungian-technical) |
| **Vision** | [When AI Remembers: The Dawn of Machine Individuation](https://docs.plugged.in/articles/jungian-vision) |

---

<div align="center">

**The collective unconscious of machines.**

MIT Licensed · Made by [VeriTeknik](https://veritech.net)

</div>
