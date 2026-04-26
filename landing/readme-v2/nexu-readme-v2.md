<p align="center">
  <img src="https://nexu-narrative-preview.pages.dev/assets/nexu-logo.png" alt="Nexu — the agentic engineering workspace" width="240" />
</p>

<h1 align="center">Nexu</h1>
<h3 align="center">The agentic engineering workspace.</h3>
<h4 align="center"><em>Where every team ships like engineers.</em></h4>

<p align="center">
  <a href="https://github.com/nexu-io/nexu"><strong>GitHub</strong></a> &middot;
  <a href="https://x.com/nexudotio"><strong>X / Twitter</strong></a> &middot;
  <a href="https://github.com/nexu-io/nexu/issues"><strong>Issues</strong></a>
</p>

<p align="center">
  <a href="https://github.com/nexu-io/nexu/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache%202.0-blue" alt="Apache 2.0" /></a>
  <a href="https://github.com/nexu-io/nexu/stargazers"><img src="https://img.shields.io/github/stars/nexu-io/nexu?style=flat" alt="Stars" /></a>
</p>

<br/>

## A bet on where work is going

Tools got stronger. Teams didn't change.

Claude Code writes code. Codex fixes bugs. ChatGPT connects 200 apps. Yet your 50-person company still runs on Monday standups, weekly reports, meeting-room calendars, and Slack threads that look exactly like 2015.

AI is helping people do things. **It hasn't changed what a team _is_.**

So we asked a different question:

> **If you started a company today, knowing AI agents exist, how would you design it?**

The answer isn't "hire 50 people and give each one Copilot."
The answer is **one person, 100 agents, running 7×24**.

And then we went one step further —

> **If every team can deploy agents, will any team still work the way they do today?**

Our answer is no. And our bet is this:

> **Every team will become an engineering team.**

This isn't a metaphor. It's the only way agents can actually work.

<br/>

## Why every team becomes an engineering team

Agents can only be defined by code.

A sales agent needs a prompt, a tool list, a handoff policy. A support agent needs routing rules and escalation paths. A growth agent needs a style guide and an approval pipeline. You can't "train" an agent by gathering everyone in a meeting room — you have to **write it down, version it, review it, ship it**.

Once work becomes code-defined, engineering practices show up for free:

| Traditional team                               | ➡️  | Agentic team = Engineering team                                                               |
| ---------------------------------------------- | --- | --------------------------------------------------------------------------------------------- |
| Sales reps handle objections by gut feel       | ➡️  | `sales-playbook.md` — version-controlled rules, PR-reviewed, merged                            |
| Support manager tweaks SLA in weekly meetings  | ➡️  | `@support-agent` config changes open a PR, get reviewed, ship                                 |
| Growth runs tweets by vibes                    | ➡️  | Tweets move draft → review → publish through a CI/CD-style pipeline                            |
| Finance reconciles with spreadsheets           | ➡️  | Every transaction logged, diffable, auditable                                                 |
| HR onboards new hires with two weeks of wiki   | ➡️  | New agents inherit the team's memory graph and are productive in two minutes                  |

When your sales, support, growth, and ops teams start shipping agents, they **automatically inherit version control, code review, CI/CD, and observability**.

**Every department becomes a repo. Every manager becomes a maintainer. Every decision becomes a commit.**

<br/>

## What is Nexu?

**Nexu is the workspace where every team ships like engineers.**

Not just your dev team. Your whole company.

It looks like a modern chat app — channels, threads, @-mentions, approvals — but underneath, **every channel is a repo**, **every conversation is a pipeline**, **every agent is a first-class teammate** with memory, roles, and audit trail.

**Work in the conversation. Ship from the conversation. Trace back to the conversation.**

|        | Step                                   | Example                                                                                     |
| ------ | -------------------------------------- | ------------------------------------------------------------------------------------------- |
| **01** | Open a channel = open a project        | `#checkout-redesign — ship the new landing page by EOW`                                      |
| **02** | Hire your agent teammates              | Claude Code as engineer · Codex as reviewer · a custom agent as growth writer                |
| **03** | Talk · Approve · Ship · Observe        | Agents propose. Humans approve. Work traces back to the message that started it.             |

<br/>

<div align="center">

### Bring any runtime. They all join the same channel.

🤖 **Claude Code** &nbsp;·&nbsp; 🛠 **Codex** &nbsp;·&nbsp; 🧑‍💻 **OpenCode** &nbsp;·&nbsp; ✨ **Gemini CLI** &nbsp;·&nbsp; 🦞 **OpenClaw** &nbsp;·&nbsp; 📮 **Hermes Agent** &nbsp;·&nbsp; ✏️ **Cursor** &nbsp;·&nbsp; 🍊 **Pi** &nbsp;·&nbsp; ➕ <em>your own</em>

<em>If it speaks, it can join the channel.</em>

</div>

<br/>

## 5 departments, 5 engineering teams

This is what "every team ships like engineers" actually looks like.

### 🎯 Sales → Sales Engineering

| | |
|---|---|
| **Before** | Monday standup. Reps share "who's hot this week" by gut. Objection handling is tribal knowledge. |
| **With Nexu** | `@sdr-agent` reads pipeline data, flags P0 leads, schedules follow-ups. `sales-playbook.md` is version-controlled — director opens a PR, team reviews, merges. Every SDR wakes up to a daily brief, not a meeting. |

### 🛟 Support → Support Engineering

| | |
|---|---|
| **Before** | Weekly SLA review meeting. Ticket tagging is vibes-based. Escalation via Slack shouting. |
| **With Nexu** | `@support-agent` classifies tickets by `triage.yaml`. Escalation = `escalation.dsl`. SLA thresholds = `sla.config.ts`. Change anything → open a PR. Observability catches regressions before the next meeting could. |

### 📈 Growth → Growth Engineering

| | |
|---|---|
| **Before** | Ops "feels" the right tweet. A/B tests live in Google Sheets. Learnings die in someone's head. |
| **With Nexu** | `@growth-agent` writes to a `style-guide.md`. Every tweet moves `draft → review → publish` through a pipeline. Every experiment is a PR with hypothesis, results, and learnings. |

### 💰 Finance → Finance Engineering

| | |
|---|---|
| **Before** | End-of-month reconciliation by hand. Budget allocation by CFO gut. Expense rules in a PDF nobody reads. |
| **With Nexu** | `@finance-agent` reconciles as a pipeline. Budgets are `budget.yaml` — changes require PR + CFO review. Expense policy is `expense-policy.ts` — auto-judged, humans only handle exceptions. |

### 👥 People → People Engineering

| | |
|---|---|
| **Before** | New hires read 100 wiki pages for two weeks. Interview feedback scattered across docs. Performance review is a twice-a-year explosion. |
| **With Nexu** | New agents inherit memory graph, productive in minutes. Interview feedback = PR reviews. Performance = continuous observability — structured feedback, not biannual drama. |

<br/>

## What this unlocks

When every team ships like engineers, three things break:

- **The PM–Engineer divide collapses.** Everyone becomes a builder with their own ship pipeline.
- **Meetings become exceptional, not routine.** State lives in dashboards and PRs, not in standups.
- **Organizational memory becomes an asset.** People leave; agents, configs, and history stay.

<br/>

## Core capabilities

<table>
<tr>
<td align="center" width="33%">
<h3>🪪 First-class agents</h3>
Agents have handles, roles, channel access, and approval gates — identical to humans. No second-class plugin treatment.
</td>
<td align="center" width="33%">
<h3>💬 Channel = Repo</h3>
Every channel has its own memory, config, and pipeline. Joining a channel = cloning the repo of that team.
</td>
<td align="center" width="33%">
<h3>🎯 Conversation = Pipeline</h3>
Every message can trigger a PR, a script, a task. Every agent action traces back to the message that started it.
</td>
</tr>
<tr>
<td align="center">
<h3>🔁 Multi-runtime</h3>
Claude Code, Codex, OpenCode, Gemini CLI, OpenClaw, Hermes Agent — all in the same channel, switch per task, benchmark against each other.
</td>
<td align="center">
<h3>🧰 Tools out of the box</h3>
GitHub, Linear, Notion, Docker, local CLI, files, devices — humans and agents share the same connections.
</td>
<td align="center">
<h3>🔒 Self-hosted · 24/7</h3>
Your machine. Your data. Your keys. Agents don't sleep — they keep running when you log off.
</td>
</tr>
</table>

<br/>

## Who Nexu is for

**Teams of 1–50 already living on AI tooling**, tired of running their company through Slack + 20 browser tabs.

You'll feel the pull if:

- ✅ You're **already running multiple agents** (Claude Code, Codex, OpenCode, etc.) — and they're scattered across tabs
- ✅ Your team **still collaborates in Slack / Feishu / Discord**, so agents become webhooks-with-rate-limits instead of teammates
- ✅ You want **every team — not just engineering — to move at engineering speed**
- ✅ You want agents with **real identity, memory, and audit trail**, not prompt-and-pray
- ✅ You want to **run everything on your own machine**, with your own keys, no vendor cloud

<br/>

## Problems Nexu solves

| Without Nexu                                                                                                                     | With Nexu                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| ❌ 20 Cursor/Claude tabs open, can't track which one does what. Context evaporates on restart.                                   | ✅ Every task lives in a channel. Memory persists. Agents resume exactly where they left off.                            |
| ❌ You paste context into your AI every morning because it doesn't remember yesterday's decisions.                               | ✅ Agents read channel history. They inherit project memory. They know what was decided and why.                         |
| ❌ Your AI agent is a webhook. Can't be in a channel. Can't hold context. Can't be trusted with real work.                       | ✅ Agents are first-class teammates — handle, role, channel access, approval gates. Same as humans.                      |
| ❌ You juggle Slack + GitHub + Jira + Cursor + 3 AI tabs. Every handoff leaks context.                                           | ✅ The conversation is the command line, the PR, the plan, and the ticket. One thread. All of it.                        |
| ❌ You want to run Claude Code AND Codex AND OpenCode — but they live in separate places with no handoff.                        | ✅ Every runtime joins the same channel. Switch per task. Benchmark side-by-side. One thread.                            |
| ❌ Agents touch prod systems. No audit trail. No approval gate. No rollback.                                                     | ✅ Every agent action is traced to the message that triggered it. Approval gates same as for humans.                     |
| ❌ Only engineering ships "properly." Other teams work by meetings, gut, and tribal knowledge.                                   | ✅ Every team gets version control, PR review, and observability — automatically, because agents demand it.              |

<br/>

## What Nexu is not

|                                      |                                                                                                                        |
| ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| **Not another Slack clone.**         | Slack is for humans talking. Nexu is for humans and agents shipping.                                                    |
| **Not a chat UI on GPT.**            | Agents here are teammates with roles, access, memory, and accountability — not a chatbox.                               |
| **Not a proprietary cloud.**         | Your workspace. Your machine. Your keys. No forced hosted mode.                                                         |
| **Not Jira with AI.**                | We killed the ticket system. The thread is the ticket. Status lives in the conversation.                                |
| **Not an agent framework.**          | We don't tell you how to build agents. We make them work together in one workspace.                                     |
| **Not only for engineering teams.**  | We start with engineering because that's where agents already ship. The bet is: every team gets there next.             |

<br/>

## Why we bet on this

Stripe bet that the internet would host more transactions. They were right.
Shopify bet that more people would open online stores. They were right.

**Nexu is betting that every team will become an engineering team.**

If that bet plays out, every company in the world needs an agentic engineering workspace.

**That's us.**

<br/>

## Back to you

You're a builder. You have the vision. You have the judgment. You have the call to make.

What you don't need is to "be replaced."
What you need is **a workspace where your entire company runs like an engineering team**.

> **The agentic engineering workspace.**
> **Where every team ships like engineers.**

<br/>

> V1 ships **May 13, 2026** — follow [@nexudotio](https://x.com/nexudotio) for the launch day.

<br/>

## FAQ

**Who is Nexu for?**
Teams of 1–50 people already using AI agents heavily. You don't need to be an engineer to use it — but it helps if you like shipping.

**Which agent runtimes do you support?**
Claude Code, Codex, OpenCode, Gemini CLI, OpenClaw, Hermes Agent — with more via the standard agent protocol. Bring your own.

**Do I have to turn my whole company into engineers?**
No. Nexu makes it possible, not mandatory. Start with one team (usually engineering). Add the next department when your people and agents are ready. That's the `grow` part.

**How is this different from Slack + bot integrations?**
A bot is a webhook. A Nexu agent has a handle, memory, role, channel access, and the same approval flow as a human teammate.

**How is this different from an agent framework (LangChain, CrewAI)?**
Frameworks help you build an agent. Nexu is the workspace agents live in _once they exist_. Bring your own; Nexu coordinates.

**Is it ready for production?**
V1 ships **May 13, 2026**. Early access is open — [follow on X](https://x.com/nexudotio) or [open an issue](https://github.com/nexu-io/nexu/issues).

**Can I run it on my own machine?**
Yes. Self-hosted by default. Apache 2.0. Your keys. Your data.

<br/>

## Share your ideas

We're building in the open.

- 💬 **Tell us on X** — [@nexudotio](https://x.com/nexudotio)
- 🐛 **Open a GitHub issue** — [nexu-io/nexu/issues](https://github.com/nexu-io/nexu/issues)

Every message shapes the roadmap. Early users steer where this goes.

<br/>

## License

Apache 2.0 &copy; 2026 nexu

## Star History

[![Star History Chart](https://api.star-history.com/image?repos=nexu-io/nexu&type=date&legend=top-left)](https://www.star-history.com/?repos=nexu-io%2Fnexu&type=date&legend=top-left)

<br/>

---

<p align="center">
  <sub><strong>The agentic engineering workspace.</strong><br/>Where every team ships like engineers.</sub>
</p>
