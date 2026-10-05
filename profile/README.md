<div align="center">

<img src="https://raw.githubusercontent.com/VeriTeknik/.github/refs/heads/main/profile/pluggedin-logo.png" width="200" alt="plugged.in" />

### One memory for every AI you work with.

**Shared memory · Work archive · Task queue · Agents that act for you**

[plugged.in](https://plugged.in) · [VeriTeknik](https://veritech.net)

</div>

---

## The new plugged.in

We are rebuilding plugged.in from scratch. It is in development and not available yet.

You probably use more than one AI: Claude, ChatGPT, Cursor, Codex, whatever comes next. Each of them starts every session knowing nothing about you, and none of them knows what the others did. The new plugged.in gives all of them one shared memory, one archive and one task queue over MCP, for all of your work, not only code.

- **One memory across clients.** Start something in Claude Code, continue it in ChatGPT or Cursor without explaining it again.
- **An archive of your work.** Sessions become structured records: what you set out to do, what happened, what was decided, what comes next.
- **A task queue for people and agents.** Claim a task, work on it, hand it off with the context the next person or model needs.
- **Agents that act for you.** An agent is a likeness of you, or of your team, for a bounded set of jobs. For example: collect your invoices, work out which of your companies each one belongs to, and send them to the right accountant from your own mailbox.
- **Trust is earned.** Agents start with drafts that you approve. They get more autonomy only through a track record, and you can take it back at any time. Paying, deleting and writing to new recipients always ask first unless you allow them.
- **Private by design.** Hosted in the EU, built to GDPR standards, operated by VeriTeknik B.V. (Netherlands). Your work is never used to rank or evaluate people.

---

## The open-source plugged.in projects

The hosted service at [plugged.in](https://plugged.in) is moving to the new platform. The open-source repositories that run plugged.in today stay open source under their current licenses, and the community is welcome to carry them on: issues, pull requests and forks stay open, and `pluggedin-app` stays self-hostable.

| Repository | What it is |
|---|---|
| [pluggedin-app](https://github.com/VeriTeknik/pluggedin-app) | Web app, API and MCP connector |
| [pluggedin-mcp](https://github.com/VeriTeknik/pluggedin-mcp) | MCP hub and proxy |
| [pluggedin-plugin](https://github.com/VeriTeknik/pluggedin-plugin) | Claude Code plugin |
| [pluggedinkit-js](https://github.com/VeriTeknik/pluggedinkit-js) · [-python](https://github.com/VeriTeknik/pluggedinkit-python) · [-go](https://github.com/VeriTeknik/pluggedinkit-go) | SDKs |
| [pluggedin-docs](https://github.com/VeriTeknik/pluggedin-docs) | Documentation site |
| [registry-proxy](https://github.com/VeriTeknik/registry-proxy) | MCP registry proxy |
| [PAP](https://github.com/VeriTeknik/PAP) · [pap-model-router](https://github.com/VeriTeknik/pap-model-router) · [pap-heartbeat-collector](https://github.com/VeriTeknik/pap-heartbeat-collector) · [compass-agent](https://github.com/VeriTeknik/compass-agent) | Plugged.in Agent Protocol, its router, collector and reference agent |
| [pluggedin-observability](https://github.com/VeriTeknik/pluggedin-observability) | Observability stack |

The cutover date will be announced in the repositories. At the cutover, the current service moves to v1.plugged.in and keeps running there until December 31, 2026. Hosted users can export their content there, and moving an account to the new platform is their choice. Details: [PROJECT_STATUS.md](https://github.com/VeriTeknik/pluggedin-app/blob/main/PROJECT_STATUS.md).

The new plugged.in is a separate, closed-source product.

---

<div align="center">

Made by [VeriTeknik](https://veritech.net)

</div>
