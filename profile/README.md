<h1>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/traceroost/core/main/media/brand/wordmark-on-dark.svg">
    <img src="https://raw.githubusercontent.com/traceroost/core/main/media/brand/wordmark.svg" alt="TraceRoost" height="40">
  </picture>
</h1>

**Local-first monitoring and observability for AI coding agents.** See what's actually happening
inside each run of Claude Code, Codex, GitHub Copilot, OpenCode and Cursor CLI — on your own
machine. Nothing is uploaded unless you link it to TraceRoost Cloud.

![TraceRoost dashboard showing traces, live run monitoring and agent analytics](https://static.traceroost.com/demo.a83a52c7ce2b.gif)

## What it does

- **Collects traces two ways.** A built-in OpenTelemetry receiver streams spans from Claude Code,
  Codex and Copilot in real time, and each agent's local log files (including OpenCode's SQLite
  database) backfill history with zero setup.
- **Catches agents that are stuck.** Sixteen named signals — repeated tool calls, oscillating
  edits, recurring errors, runaway scope, unverified test runs and more — each with a correction
  prompt you can paste straight into the session.
- **Tells you what to fix in your instructions file.** The Advisor reads across traces and
  suggests concrete additions to CLAUDE.md, AGENTS.md or Copilot instructions.
- **Shows what it cost and what survived.** Token usage, estimated cost, plan-limit windows, and
  whether each trace's file changes were merged, committed or left uncommitted.

## Get started

Requires Node.js 24+:

```bash
npx traceroost@latest service install
```

Or with Homebrew (macOS or Linux):

```bash
brew install traceroost/tap/traceroost
traceroost service install
```

Then open <http://localhost:3000>. TraceRoost also runs as a
[VS Code extension](https://marketplace.visualstudio.com/items?itemName=agentlens.agentlens-dashboard),
a [desktop app](https://github.com/traceroost/core/releases/latest) and a Docker image — see
[Ways to Run](https://github.com/traceroost/core#ways-to-run).

## Repositories

| Repository | What's in it |
| --- | --- |
| [**core**](https://github.com/traceroost/core) | The local collector, dashboard, CLI, MCP server, VS Code extension and desktop app. MIT, apart from the TraceRoost Cloud connector (BSL 1.1). |
| [**homebrew-tap**](https://github.com/traceroost/homebrew-tap) | The Homebrew formula, published automatically by each core release. |

## Links

[Website](https://traceroost.com) ·
[Documentation](https://docs.traceroost.com) ·
[Report a bug](https://github.com/traceroost/core/issues/new/choose) ·
[Contributing](https://github.com/traceroost/core/blob/main/CONTRIBUTING.md) ·
[Security](https://github.com/traceroost/.github/blob/main/SECURITY.md)

<sub>Formerly AgentLens. TraceRoost is an independent project and is not affiliated with
Anthropic, OpenAI, GitHub, Microsoft, Anysphere or the OpenCode project.</sub>
