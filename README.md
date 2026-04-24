# codebrief

> Run one command. See your codebase clearly.

A CLI tool that gives instant clarity on your codebase — architecture, flows, risks, and what actually matters.

Built by the founder of [North](https://northapp.in) — a personal intelligence system for founders.

## What it does

Run `codebrief audit` on any codebase and get:

- System overview
- Core user flows
- Risks & complexity
- Structure scores
- Moat vs commodity
- What to fix next

A clean HTML report opens automatically in your browser.

## Install

```bash
npm install -g codebrief
```

## Usage

```bash
export OPENAI_API_KEY=your_key
cd your-project
codebrief audit
```

## Why

Developers see files. Not systems.

No tool gives you a systems-level view of what you're building — until now. Run one command, get clarity.


## Contributing

This is v0.1 — rough but real. Built by a solo founder who needed it.

A lot can be improved. If you want to contribute, here's what's missing:

**Easy wins**
- Add support for Python, Go, Rust files
- Add a `.codebriefconfig` file so you don't need to export the API key every time
- Export report as PDF or JSON

**Medium effort**
- Smarter file selection — pick files by importance, not just name
- Remove the 15 file limit for larger codebases
- Support for Claude, Gemini, or local models (Ollama)

**Bigger ideas**
- Audit history — compare today vs last week
- CI/CD integration — run audit on every PR
- Multi-language prompt support

**How to contribute**
1. Fork the repo
2. Make your change
3. Open a PR with a short description of what you fixed

No gatekeeping. If it makes codebrief more useful, it's welcome.

## Roadmap

codebrief is just getting started. Here's where it's going:

**v0.1 — current**
- Codebase audit with AI
- System overview, flows, risks, scores
- Moat vs commodity
- HTML report auto-opens in browser

**v0.2 — coming soon**
- `codebrief map` — visual system diagram of your architecture
- `codebrief scale` — identify what breaks at 10x users
- skills.md support — customize how codebrief thinks about your stack

**v1.0 — the vision**
- `codebrief decide` — tell you what to build next based on your system
- CI/CD integration — audit on every PR
- Support for Python, Go, Rust
- No API key needed for basic mode

The goal is simple: every founder deserves a CTO-level view of what they're building.

## License
MIT


