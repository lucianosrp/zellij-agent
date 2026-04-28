# Boost Your Productivity with Zellij

A talk for the [Rust Meetup at ExpressVPN](https://github.com/lucianosrp/talks) in Hong Kong.

## The Problem

- Have you ever accidentally closed your task/agent while it was still running?
- Do you often work in a remote environment?
- Do you often work with multiple machines in different systems and architectures?

## The Terminal is Back

AI coding agents — Claude Code, opencode, Codex — live in the terminal. IDEs are optional.

Your agent needs a real terminal workspace, not a fragile subprocess that dies when you close the window.

## What is Zellij?

Zellij is a modern terminal multiplexer written in Rust — batteries included, sensible defaults, works out of the box.

## Vocabulary

- **Pane** — a single shell/process inside a tab. Split horizontally or vertically.
- **Window** — your OS terminal window. Hosts the Zellij client.
- **Tab** — a named collection of panes within a session. Like a browser tab.
- **Session** — the persistent Zellij workspace. Survives detach, SSH drops, terminal close.

## Top 3 Benefits

### 🔌 Persistent sessions
Detach, reconnect, never lose your work — your panes survive SSH drops, laptop sleeps, and accidental terminal closes.

### 🪟 Multiplexing done right
Splits, tabs, floating panes — all keyboard-driven, all scriptable via layouts you can commit to your repo.

### 🤖 Agent-friendly
WebAssembly plugins + a clean CLI mean your AI agent gets a real terminal workspace, not a fragile subprocess.

## Now, add your agent!

Spawn it in a pane. Detach. Reattach. Your agent keeps working while you sleep.

## Get Started

```bash
cargo install zellij
```

Or grab a binary from the [Zellij releases page](https://github.com/zellij-org/zellij/releases).

## Resources

- [Zellij website](https://zellij.dev/)
- [Zellij documentation](https://zellij.dev/documentation/)
- [Zellij layouts](https://zellij.dev/documentation/layouts.html)
- [Zellij plugins](https://zellij.dev/plugins/overview/)

## Slides

See `PRESENTATION.md` for the full slide deck (uses [presenterm](https://github.com/mfontanini/presenterm)).
