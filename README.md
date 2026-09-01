<h1 align="center">Serhii Leniv</h1>

<p align="center"><strong>I design systems and ship the tools I want to exist.</strong></p>

<p align="center"><sub>Software engineer · AI tooling, CLIs and agent infrastructure · Ukraine</sub></p>

<p align="center">
  <a href="https://quillfile.com/"><img src="https://img.shields.io/badge/site-quillfile.com-172B35?style=flat-square" alt="site"></a>
  <a href="mailto:leniv.tech@gmail.com"><img src="https://img.shields.io/badge/email-leniv.tech-172B35?style=flat-square" alt="email"></a>
</p>

---

Most of what I build sits underneath other people's work: a proxy that picks the model,
a scheduler that admits when it failed, a status line that renders in three milliseconds.
Small surface, load-bearing, and cheap to throw away if it stops earning its place.

## What I build

| | What it is | Stack |
|---|---|---|
| **[claude-router](https://github.com/serhiileniv/claude-router)** | Drop-in proxy that routes every Claude request to the cheapest model that can handle it. 35% saved on agentic coding traffic, measured by replaying 200 real turns — not estimated. | TypeScript, strict |
| **[agent-master](https://github.com/serhiileniv/agent-master)** | Desktop workspace for running a team of coding agents in parallel, each isolated in its own git worktree. | Electron, React, TypeScript |
| **[every](https://github.com/serhiileniv/every)** | Schedule anything on your machine in one human phrase, and get a straight answer to *"did it run?"* — launchd, systemd and Task Scheduler behind one interface. Zero dependencies. | Ruby |
| **[aerin](https://github.com/serhiileniv/aerin)** | A coding agent you can actually read: sub-agents, undo that covers bash, hooks, MCP — inside a CI-enforced budget of under 10k lines. | TypeScript |
| **[ctxline](https://github.com/serhiileniv/ctxline)** | Model and context pressure in your Claude Code status line. One 330KB static binary, ~3ms a render, pure stdin → stdout. | Rust |
| **[twostones](https://github.com/serhiileniv/twostones)** | Agent tooling worth keeping — every entry dated with when I last checked it, and against which model. | Astro, Cloudflare Pages |
| **[skills](https://github.com/serhiileniv/skills)** | Agent skills I actually use. `own-this` turns a shipped PR into a study guide that ends with the questions a reviewer will ask. | Markdown, HTML |

## How I work

I'm an AI-native engineer, and I mean that as a description of method rather than a slogan.
I own the architecture — the boundaries, the failure modes, the trade-off I picked and the one
I passed on — and I drive models hard to build against it. The interesting part of the job
moved to deciding what should exist and why; I'd rather spend my judgment there.

Currently going deeper on distributed systems design, and on the layer under the API —
how transformers actually spend their compute.

<p align="center"><sub>Open to interesting problems · <a href="mailto:leniv.tech@gmail.com">leniv.tech@gmail.com</a></sub></p>
