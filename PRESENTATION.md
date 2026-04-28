---
title: "Boost your productivity with Zellij"
sub_title: For yourself and your agent
author: Luciano Scarpulla
options:
  incremental_lists: true
  implicit_slide_ends: true
  list_item_newlines: 2
theme: 
#name: gruvbox-dark
  name: light
---

Agenda
===

1. The problem
2. The terminal is back!
3. What is Zellij?
4. Demo time
5. Now, add your agent!
6. Q&A

⚠️ AI slop disclaimer ⚠️
===
<!-- jump_to_middle -->

The following slides may or may not contain AI generated images...
I did this presentation in few days so I took shortcuts to explain whats in my mind....

<!-- alignment: center -->
<!-- new_lines: 10 -->
 ⚠️ AI slop disclaimer ⚠️

The problem
===

![image:width:80%](./static/5.png)
 - Have you ever accidentally closed your task/agent while it was still running?
 - Do you often work in a remote environment ? 
 - Do you often work with multiple machines in different systems and architectures? 


Zellij is here
===

![image:width:100%](./static/6.png)
_not actual logo_

What is Zellij
===

![image:width:100%](./static/7.png)

Vocabulary
===

- **Pane** — a single shell/process inside a tab. Split horizontally or vertically.
- **Window** — your OS terminal window. Hosts the zellij client.
- **Tab** — a named collection of panes within a session. Like a browser tab.
- **Session** — the persistent zellij workspace. Survives detach, SSH drops, terminal close.

Top 3 benefits
===

<!-- column_layout: [1, 1, 1] -->

<!-- column: 0 -->

## 🔌 Persistent sessions

Detach, reconnect, never lose your work — your panes survive SSH drops, laptop sleeps, and accidental terminal closes.

<!-- column: 1 -->

## 🪟 Multiplexing done right

Splits, tabs, floating panes — all keyboard-driven, all scriptable via layouts you can commit to your repo.

<!-- column: 2 -->

## 🤖 Agent-friendly

WebAssembly plugins + a clean CLI mean your AI agent gets a real terminal workspace, not a fragile subprocess.

<!-- reset_layout -->

Demo time
===

<!-- jump_to_middle -->
<!-- alignment: center -->

# 🎬 Demo time

_(switch to live terminal)_

The terminal is back
===

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

## TUIs are back, baby

AI coding tools like **Claude Code**, **opencode**, and **Codex** live in the terminal.

IDEs are optional now.

<!-- column: 1 -->

## Why does this matter?

Your agent needs a real terminal — not a fragile subprocess that dies when you close the window.

<!-- reset_layout -->

Now, add your agent!
===

<!-- jump_to_middle -->
<!-- alignment: center -->

# 🤖 Now, add your agent!

Spawn it in a pane. Detach. Reattach.
Your agent keeps working while you sleep.

Wrapping up
===

<!-- jump_to_middle -->
<!-- alignment: center -->

# Stop losing work. Start scripting your terminal.

Zellij gives **you** a persistent, keyboard-driven workspace —
and gives your **agent** a real place to live.

**Try it:** `cargo install zellij` — or grab a binary from the releases page.

Questions?
