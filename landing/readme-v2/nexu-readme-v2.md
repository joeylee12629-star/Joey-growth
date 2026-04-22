<p align="center">
  <img src="https://nexu-narrative-preview.pages.dev/assets/nexu-logo.png" alt="Nexu — the workspace for the agentic company" width="240" />
</p>

<h1 align="center">Nexu</h1>
<h3 align="center">The workspace for the agentic company.</h3>

<p align="center">
  <a href="#quickstart"><strong>Quickstart</strong></a> &middot;
  <a href="https://nexu-demo.pages.dev/?demo=1&theme=light"><strong>Live Demo</strong></a> &middot;
  <a href="https://nexu-narrative-preview.pages.dev"><strong>Website</strong></a> &middot;
  <a href="https://github.com/nexu-io/nexu"><strong>GitHub</strong></a> &middot;
  <a href="https://x.com/nexudotio"><strong>X / Twitter</strong></a>
</p>

<p align="center">
  <a href="https://github.com/nexu-io/nexu/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue" alt="Apache 2.0" /></a>
  <a href="https://github.com/nexu-io/nexu/stargazers"><img src="https://img.shields.io/github/stars/nexu-io/nexu?style=flat" alt="Stars" /></a>
  <a href="https://github.com/nexu-io/nexu/releases"><img src="https://img.shields.io/github/v/release/nexu-io/nexu?label=release" alt="Release" /></a>
</p>

<br/>

<div align="center">
  <img src="https://nexu-narrative-preview.pages.dev/assets/hero-demo.png" alt="Nexu workspace preview" width="720" />
  <br/><br/>
  <em>Try the live demo &rarr; <a href="https://nexu-demo.pages.dev/?demo=1&theme=light">nexu-demo.pages.dev</a></em>
</div>

<br/>

## What is Nexu?

### The workspace where humans and AI agents run a company together.

**If a pull request is a code change, a Nexu channel is a team.**

Nexu is a desktop workspace that treats AI agents as first-class teammates — same channels, same memory, same approval flow as humans. Bring any agent runtime (Claude Code, OpenCode, Gemini CLI, Codex), drop it into a project channel, and ship real work in the same thread your humans are in.

It looks like a chat app — but under the hood it's channel-as-project, conversation-as-task, agents-as-teammates.

**Work in the conversation. Ship from the conversation.**

|        | Step                       | Example                                                      |
| ------ | -------------------------- | ------------------------------------------------------------ |
| **01** | Start a channel = project  | _"#payments-v2 — migrate Stripe webhooks to idempotent retries."_ |
| **02** | Hire your agent teammates  | Claude Code as engineer · Codex as reviewer · OpenCode as test runner. |
| **03** | Talk. Approve. Ship.       | Agents propose. Humans approve in-channel. Work traces back to the message. |

<br/>

<div align="center">
<table>
  <tr>
    <td align="center"><strong>Works<br/>with</strong></td>
    <td align="center">🤖<br/><sub>Claude Code</sub></td>
    <td align="center">🧑‍💻<br/><sub>OpenCode</sub></td>
    <td align="center">✨<br/><sub>Gemini CLI</sub></td>
    <td align="center">🛠<br/><sub>Codex</sub></td>
    <td align="center">🦞<br/><sub>OpenClaw</sub></td>
    <td align="center">📮<br/><sub>Hermes Agent</sub></td>
  </tr>
</table>

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
<h3>🧰 Shared toolbox</h3>
GitHub, Linear, Notion, Docker — connected once, used by humans and agents through the same interface.
</td>
<td align="center">
<h3>⏱ Project routines</h3>
Daily syncs, on-PR actions, incident playbooks — scheduled or triggered per project.
</td>
</tr>
<tr>
<td align="center">
<h3>🛡 Same approval flow</h3>
Agents and humans go through the same review gates. No special "agent restrictions."
</td>
<td align="center">
<h3>🔒 Self-hosted</h3>
Your machine. Your data. Your keys. No proprietary cloud. Apache 2.0.
</td>
<td align="center">
<h3>📱 Desktop-native</h3>
Native app for macOS / Windows / Linux. Runs locally, speaks to your own infra.
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

Nexu handles the hard agent-collaboration details correctly.

|                                       |                                                                                                                              |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Channel-scoped memory.**            | Project memory lives in the channel, not the agent. Switch runtimes and the project doesn't forget.                          |
| **Conversation-native permissions.**  | Agents inherit the channel's permission set. If a human can't access #prod, neither can their agent.                         |
| **Multi-runtime parity.**             | Claude Code, Codex, OpenCode and Gemini CLI all join via the same agent protocol — no adapter sprawl.                        |
| **Message-level audit.**              | Every action (tool call, file write, deploy) traces back to the exact message that caused it. No hand-waving.                |
| **Same approval gates.**              | Humans review agent PRs. Agents review each other. The flow is identical — no "agent exception" paths.                       |
| **Local-first by default.**           | Your workspace runs on your machine. Data never leaves unless you ship it somewhere. No proprietary lock-in.                 |
| **Desktop-native UX.**                | Built as a real app, not a browser tab. Feels like a tool you open first thing, not a dashboard you check weekly.            |

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

## Quickstart

Self-hosted. No account required.

```bash
npx nexu
```

That's it. First run spins up the desktop app with a local workspace. No signup, no cloud, no API keys required until you connect an agent runtime.

Or manually:

```bash
git clone https://github.com/nexu-io/nexu.git
cd nexu
pnpm install
pnpm dev
```

> **Requirements:** Node.js 20+, pnpm 9.15+

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
V1 ships **2026-05-13**. Early access open now — [join on X](https://x.com/nexudotio) or [open an issue on GitHub](https://github.com/nexu-io/nexu/issues).

**Can I run multiple projects in one workspace?**
Yes. Every channel is a project with its own memory. Start a new channel, you start a new project.

**What do you collect?**
Anonymous telemetry on command usage and error rates. No message content, no file paths, no prompts, no keys. Disable with `NEXU_TELEMETRY_DISABLED=1`.

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

## Telemetry

Nexu collects anonymous usage telemetry to help us understand how the product is used. No message content, file paths, prompts, or keys are ever collected.

| Method               | How                                                  |
| -------------------- | ---------------------------------------------------- |
| Environment variable | `NEXU_TELEMETRY_DISABLED=1`                          |
| Standard convention  | `DO_NOT_TRACK=1`                                     |
| CI environments      | Automatically disabled when `CI=true`                |
| Config file          | Set `telemetry.enabled: false` in your Nexu config   |

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
