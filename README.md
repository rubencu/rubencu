## Hi, I'm Ruben 👋

Sr SDE at Amazon, based in New York City. Outside of work I contribute to open source
AI agent runtimes and agent workflow tooling.

### 🦞 OpenClaw

[![merged PRs](https://img.shields.io/github/issues-search?query=repo%3Aopenclaw%2Fopenclaw%20is%3Apr%20author%3Arubencu%20is%3Amerged&label=my%20merged%20PRs&color=6f42c1)](
https://github.com/openclaw/openclaw/pulls?q=is%3Apr+author%3Arubencu+is%3Amerged)
[![stars](https://img.shields.io/github/stars/openclaw/openclaw?label=openclaw%20%E2%98%85&color=555)](https://github.com/openclaw/openclaw)

[openclaw/openclaw](https://github.com/openclaw/openclaw) is one of the largest open
source agent runtimes. My merged work there spans the gateway, agent runtime, memory
core, the Codex / OpenAI / xAI extensions, and the Telegram, WhatsApp and Feishu
channels — enough to put me in the top 100 of its contributor list.

Work I'd point at:

- [**Send fresh finals for stale previews**](https://github.com/openclaw/openclaw/pull/72038)
  — a long Telegram reply kept its preview's start timestamp, so you couldn't tell how
  long the task had actually taken. Later
  [ported into Nous Research's hermes-agent](https://github.com/NousResearch/hermes-agent/pull/16261)
  by its maintainer.
- [**Sanitize tool XML and hide configured error text**](https://github.com/openclaw/openclaw/pull/71830)
  — internal tool markup and error strings were leaking into user-facing messages.
  15 source files; closed a reported bug.
- [**Fence stale reply delivery after abort**](https://github.com/openclaw/openclaw/pull/68100)
  — aborted turns could still deliver their replies, out of order.
- [**Preserve memory prompt registration**](https://github.com/openclaw/openclaw/pull/92350)
  — agents silently lost their memory prompt mid-session.
- [**Clear deselected model fallbacks**](https://github.com/openclaw/openclaw/pull/71596)
  — models you had explicitly deselected were still being used as fallbacks.

### Also upstream

- **[strands-agents/agent-sop](https://github.com/strands-agents/agent-sop)** — top-5
  contributor to AWS Strands' SOP workflow framework
- **[openclaw/clawsweeper](https://github.com/openclaw/clawsweeper)** —
  [suppressed changelog-only findings](https://github.com/openclaw/clawsweeper/pull/57)
  in the bot that triages every OpenClaw PR and issue.

### Tools I build

- **[openclaw-pr-workflow](https://github.com/rubencu/openclaw-pr-workflow)** — the
  workflow behind those merges, published as a Codex skill: verify before changing,
  keep the diff focused, bring real behavior proof, never lean on maintainer-only
  tooling.
- **[sopilot](https://github.com/rubencu/sopilot)** — the agent-sop problem from the
  runtime side. It runs workflow-oriented Agent Skills under SOP control, so the
  workflow keeps ownership of step order, checkpoints, and artifacts instead of losing
  the thread when the conversation drifts.

### Elsewhere

🐦 [@rubencu](https://x.com/rubencu) · 💼 [LinkedIn](https://www.linkedin.com/in/rubencu/)
