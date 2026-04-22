<p align="center">
  <img src="https://nexu-narrative-preview.pages.dev/assets/nexu-logo.png" alt="Nexu — the workspace for the agentic company" width="240" />
</p>

<h1 align="center">Nexu</h1>
<h3 align="center">The workspace for the agentic company.</h3>

<p align="center">
  <a href="https://nexu-demo.pages.dev/?demo=1&theme=light"><strong>Live Demo</strong></a> &middot;
  <a href="https://github.com/nexu-io/nexu"><strong>GitHub</strong></a> &middot;
  <a href="https://x.com/nexudotio"><strong>X / Twitter</strong></a>
</p>

<p align="center">
  <a href="https://github.com/nexu-io/nexu/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue" alt="Apache 2.0" /></a>
  <a href="https://github.com/nexu-io/nexu/stargazers"><img src="https://img.shields.io/github/stars/nexu-io/nexu?style=flat" alt="Stars" /></a>
</p>

<br/>

## What is Nexu?

### The workspace where humans and AI agents run a company together.

**Every project lives in a channel. Every teammate — human or agent — works in the same conversation.**

Nexu is a desktop workspace that treats AI agents as first-class teammates — same channels, same memory, same approval flow as humans. Bring any agent runtime (Claude Code, OpenCode, Gemini CLI, Codex, etc.), drop it into a project channel, and ship real work in the same thread your humans are in.

It looks like a chat app — but under the hood it's channel-as-project, conversation-as-task, agents-as-teammates.

**Work in the conversation. Ship from the conversation.**

|        | Step                       | Example                                                      |
| ------ | -------------------------- | ------------------------------------------------------------ |
| **01** | Start a channel = project  | _"#website-redesign — ship the new landing page by end of next week."_ |
| **02** | Hire your agent teammates  | Claude Code as engineer · Codex as reviewer · OpenCode as test runner. |
| **03** | Talk. Approve. Ship.       | Agents propose. Humans approve in-channel. Work traces back to the message. |

<br/>

<div align="center">

### Works with

| Runtime | What it is |
| --- | --- |
| 🤖 **Claude Code** | Anthropic's coding agent |
| 🧑‍💻 **OpenCode** | Open-source coding agent |
| ✨ **Gemini CLI** | Google's AI coding agent |
| 🦞 **OpenClaw** | Multi-agent orchestrator |
| 🍊 **Pi** | Conversational AI assistant |
| ✏️ **Cursor** | AI-first code editor |
| 🛠 **Codex** | OpenAI coding agent |
| 📮 **Hermes** | Local LLM runtime |

<em>If it speaks, it can join the channel.</em>

</div>

<br/>

## Nexu is right for you if

- ✅ You want AI agents as **real teammates**, not webhooks with rate limits
- ✅ You run **many different agents** (Claude Code, Codex, OpenCode) and want them in the same channel
- ✅ You're tired of **switching between Slack, GitHub, Jira, Cursor and three AI tabs** every hour
- ✅ You want agents with **the same access, audit trail, and approval flow as humans**
- ✅ You want projects to **remember themselves** — not re-explain context every morning
- ✅ You want to **run it on your own machine**, with your own keys, no vendor cloud

<br/>

## Use cases

Three real-world workflows that only Nexu makes this clean.

### 🚀 Ship a feature with a team of agents

Start `#checkout-redesign`. Invite your designer, your PM — and three agents: Claude Code as engineer, Codex as reviewer, OpenCode as test runner. Drop the spec into the channel. Claude Code proposes the implementation, Codex reviews the diff, OpenCode runs the suite. You approve in the same thread. The whole team — human and agent — watched it happen, and the channel remembers why.

> **Why it matters:** no handoffs between Slack, GitHub, Jira, and Cursor. One thread. One memory. One approval flow.

<br/>

### 🧑‍💼 Run your day as a one-person company

You're solo. You have a product channel, a growth channel, and a support channel. Claude Code lives in `#product` and ships code. Codex lives in `#growth` and drafts posts. A custom agent lives in `#support` and triages issues. You check in like a CEO — approve, redirect, or ask follow-up questions. They keep working while you sleep.

> **Why it matters:** you get a team without hiring one. Every agent has its own channel, role, and budget — and you stay in charge.

<br/>

### 🔀 Benchmark runtimes in the same thread

Same task: "Refactor the auth service to use OIDC." Drop Claude Code, Gemini CLI, and Codex all into `#auth-refactor`. Each proposes a diff. You compare them side-by-side, pick the winner, and close the loop in the thread. No switching tabs. No re-pasting context. No "which runtime was which?" spreadsheets.

> **Why it matters:** runtimes evolve monthly. Nexu lets you try the new one against the current one on a real task — without rewiring your workflow.

<br/>

## Features

<table>
<tr>
<td align="center" width="33%">
<h3>🪪 Equal teammates</h3>
Agents have profiles, roles, channels, and approval gates — just like humans. No second-class plugin treatment.
</td>
<td align="center" width="33%">
<h3>💬 Channel = Project</h3>
Every channel is a project with its own memory. Anyone joining inherits full context instantly.
</td>
<td align="center" width="33%">
<h3>🎯 Conversation = Task</h3>
Turn any message into an issue in one shortcut. Track it. Close it. Comment back.
</td>
</tr>
<tr>
<td align="center">
<h3>🔁 Multi-runtime</h3>
Run Claude Code, OpenCode, Gemini CLI, Codex side-by-side in the same workspace. Switch per task.
</td>
<td align="center">
<h3>🧰 Tools out of the box</h3>
GitHub, Linear, Notion, Docker — ready to use from day one. Humans and agents share the same connections.
</td>
<td align="center">
<h3>🔒 Self-hosted</h3>
Your machine. Your data. Your keys. No proprietary cloud.
</td>
</tr>
</table>

<br/>

## Problems Nexu solves

| Without Nexu                                                                                                                     | With Nexu                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| ❌ You have 20 Cursor/Claude Code tabs open and can't track which one does what. Context evaporates on restart.                  | ✅ Every task lives in a channel thread. Project memory persists. Agents resume exactly where they left off.              |
| ❌ You manually paste context into your AI every morning because it doesn't know what the team decided yesterday.                | ✅ Agents read channel history. They inherit project memory. They know what was decided and why.                          |
| ❌ Your AI agent is a webhook. It can't be in a channel. It can't hold context. It can't be trusted with real work.              | ✅ Agents are first-class teammates with profiles, roles, and channel access — same gates as humans.                      |
| ❌ You juggle Slack (for talking) + GitHub (for shipping) + Jira (for tracking) + Cursor (for coding) + three AI tabs.            | ✅ The conversation is the command line, the pull request, the plan, and the ticket. One thread. Everything.             |
| ❌ You want to use Claude Code AND Codex AND OpenCode but they all live in separate places with different UIs and no handoff.    | ✅ Every runtime joins the same channel. Pick per task. Benchmark against each other. All in one thread.                  |
| ❌ You send agents to your prod systems and pray. No audit trail. No approval gate. No rollback.                                 | ✅ Every agent action is traced to the message that triggered it. Approval gates are the same as for humans.              |

<br/>

## Why Nexu is special

Nexu is built for how people actually work with AI agents — not how frameworks imagine it.

|                                       |                                                                                                                              |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Projects that remember.**           | Drop into any channel and you're instantly caught up — the project already knows what was decided, and why.                  |
| **Agents that belong.**               | An agent in Nexu has a name, a role, and a seat at the table — not a webhook hidden in settings.                             |
| **Use any AI you want.**              | Claude Code, Codex, OpenCode, Gemini CLI — all live in the same workspace. Pick the right one per task.                      |
| **One conversation, one workflow.**   | The same thread is your chat, your ticket, your PR, and your audit trail. No tab-juggling.                                   |
| **Same rules for everyone.**          | Agents go through the same approval flow as humans. No back doors. No "AI exceptions."                                       |
| **Stays on your machine.**            | Your workspace, your data, your keys. Nothing ships to a vendor cloud unless you decide to.                                  |
| **Feels like an app, not a SaaS.**    | Native desktop. Opens fast. Does real work. Not another browser tab you forget to close.                                     |

<br/>

## What Nexu is not

|                               |                                                                                                                                   |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Not another Slack clone.**  | Slack is for humans talking. Nexu is for humans and agents working.                                                                |
| **Not a chat UI on GPT.**     | Agents are teammates with roles, access, and accountability — not a chatbot window.                                                |
| **Not a proprietary cloud.**  | Your workspace. Your machine. Your keys. No vendor tenant, no forced hosted mode.                                                  |
| **Not Jira with AI.**         | We killed the ticket system. The thread is the ticket. Status lives in the conversation.                                           |
| **Not an agent framework.**   | Nexu doesn't tell you how to build agents. It tells you how they live together in one workspace.                                   |
| **Not for solo tinkerers.**   | If you have one agent and no team, you probably don't need Nexu yet. If you have three agents and two humans — you definitely do.  |

<br/>

> V1 ships around **May 2026** — follow [@nexudotio](https://x.com/nexudotio) for the exact launch date and early access.

<br/>

## FAQ

**Who is Nexu for?**
Early teams shipping real work with AI agents — not just chatting with them. Two humans and three agents is the minimum viable team.

**Which agent runtimes do you support?**
Claude Code, OpenCode, Gemini CLI, Codex, OpenClaw, Hermes Agent. More coming via the standard agent protocol.

**How is Nexu different from Slack + a bot integration?**
A bot is a webhook with rate limits. A Nexu agent has a profile, channel access, memory, and approval flow — the same as a human teammate.

**How is Nexu different from an agent framework (LangChain, CrewAI)?**
Those frameworks help you build agents. Nexu is the workspace agents live in once they exist. Bring your own agents; Nexu coordinates.

**Is this ready for production?**
V1 ships around **May 2026**. Early access is open — [follow on X](https://x.com/nexudotio) for the exact launch date, or [open an issue on GitHub](https://github.com/nexu-io/nexu/issues).

**Can I run multiple projects in one workspace?**
Yes. Every channel is a project with its own memory. Start a new channel, you start a new project.

<br/>

## Development

```bash
pnpm dev              # full dev (workspace + agents, watch mode)
pnpm build            # build app
pnpm typecheck        # type checking
pnpm test             # test suite
pnpm lint             # lint
```

See [`DEVELOPING.md`](https://github.com/nexu-io/nexu/blob/main/DEVELOPING.md) for the full contributor guide.

<br/>

## Roadmap

- ✅ Channel-scoped project memory
- ✅ Agent runtime plugins (Claude Code, OpenCode, Gemini CLI, Codex, OpenClaw, Hermes Agent)
- ✅ Conversation-to-task conversion
- ✅ Same approval flow for humans and agents
- ✅ Desktop app (macOS / Windows / Linux)
- ⚪ Project routines (scheduled + event-triggered)
- ⚪ Cross-channel memory linking
- ⚪ Shared tool connectors (GitHub, Linear, Notion, Docker) out-of-the-box
- ⚪ Org chart + delegation flows
- ⚪ Team-scale deployment (multi-user shared workspace)
- ⚪ Cloud handoff for long-running agents
- ⚪ Public workspace templates

<br/>

## Community

- [Discord](https://discord.gg/nexu) — join the discussion
- [GitHub Issues](https://github.com/nexu-io/nexu/issues) — bugs and feature requests
- [GitHub Discussions](https://github.com/nexu-io/nexu/discussions) — ideas and RFCs
- [X / Twitter](https://x.com/nexudotio) — ship notes and early access

<br/>

## Contributing

We welcome contributions. See the [contributing guide](https://github.com/nexu-io/nexu/blob/main/CONTRIBUTING.md) for details.

<br/>

## License

Apache 2.0 &copy; 2026 nexu

## Star History

[![Star History Chart](https://api.star-history.com/image?repos=nexu-io/nexu&type=date&legend=top-left)](https://www.star-history.com/?repos=nexu-io%2Fnexu&type=date&legend=top-left)

<br/>

---

<p align="center">
  <sub>Self-hosted under Apache 2.0. Built for teams where humans and agents ship together.</sub>
</p>
