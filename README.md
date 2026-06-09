# AI-Driven Frontend Playbook

**🌐 Language:** **English** · [Українська](./README.ua.md)

> A public playbook on how a frontend engineer integrates AI into a real workflow — from prompting to multi-agent pipelines.
>
> This is not an "awesome list of links". I take each block to practice and demonstrate it on a live project — the [`memory-cards`](https://github.com/smnvsergii/phaser-memory-cards-MFE) game (Phaser 3 + Vite + TypeScript): what I integrated, how it worked, and what came out of it.

## Why this exists

AI tools are quickly becoming the standard, but the value is not in "writing prompts" — it's in the ability to build **reliable, testable, and performant systems with AI components**. My focus is AI as a multiplier of engineering quality, not a replacement for it.

Goals of this repository:
- collect a checklist of AI-driven frontend skills in one place;
- give a working example for each item, referencing the `memory-cards` project;
- record "what worked / what didn't" instead of theory.

## Status legend

| Status | Meaning |
| :----: | ------- |
| ✅ | Implemented and documented with an example |
| 🚧 | In progress |
| ⬜ | Planned |

## Roadmap

### 1. Foundations

| # | Topic | What to master | Example in `memory-cards` | Status |
|---|-------|----------------|----------------------------|:------:|
| 1.1 | Prompt & Context Engineering | Prompt structure, passing context, iterative refinement | [1.1](./examples/1-foundations/1.1-prompt-and-context-engineering.md) | ✅ |
| 1.2 | AI Rules / Custom Instructions | Project rules for the assistant (`.cursorrules`, `AGENTS.md`, steering files) | _link_ | ⬜ |
| 1.3 | Custom skills / commands | Reusable commands and skills for routine tasks | _link_ | ⬜ |

### 2. Daily Workflow

| # | Topic | What to master | Example in `memory-cards` | Status |
|---|-------|----------------|----------------------------|:------:|
| 2.1 | AI Code Review | Reviewing PRs with AI, checklists, catching regressions | _link_ | ⬜ |
| 2.2 | AI Debugging | Locating bugs, reading stack traces, forming and testing hypotheses | _link_ | ⬜ |
| 2.3 | AI Testing | Generating unit/e2e tests, test cases, edge cases | _link_ | ⬜ |

### 3. Tooling & Integration

| # | Topic | What to master | Example in `memory-cards` | Status |
|---|-------|----------------|----------------------------|:------:|
| 3.1 | MCP / tools | Connecting MCP servers, writing custom tools | _link_ | ⬜ |
| 3.2 | Design-to-Code | Figma → components, generating UI from mockups | _link_ | ⬜ |
| 3.3 | Performance with AI | Profiling, finding bottlenecks, optimizing with AI | _link_ | ⬜ |

### 4. Advanced

| # | Topic | What to master | Example in `memory-cards` | Status |
|---|-------|----------------|----------------------------|:------:|
| 4.1 | Multi-agent workflows | Splitting tasks across agents, orchestration | _link_ | ⬜ |
| 4.2 | Agentic pipelines in CI/CD | AI steps in GitHub Actions (review, tests, release notes) | _link_ | ⬜ |
| 4.3 | Open-source AI workflow | Contributions, public rules and templates | _link_ | ⬜ |

## Practice project: `memory-cards`

A "match the pair" game built with **Phaser 3 + Vite + TypeScript**, running both as a standalone app and as a microfrontend inside the Game Hub shell. I run every roadmap block through it and record the result.

Links:
- Project repository: [smnvsergii/phaser-memory-cards-MFE](https://github.com/smnvsergii/phaser-memory-cards-MFE)
- Examples directory in this repo: [`examples/`](./examples) _(in progress)_

## Repository structure

```
ai-driven-frontend/
├── README.md            # this file — roadmap and checklist (EN)
├── README.ua.md         # Ukrainian version
├── examples/            # breakdown of each block, tied to memory-cards
│   ├── 01-prompt-engineering/
│   ├── 02-ai-rules/
│   └── ...
└── notes/               # short notes "what worked / what didn't"
```

## How to read this repository

1. The roadmap above is the table of contents and progress tracker.
2. As I integrate a block into `memory-cards`, I fill the "Example" column with a link and switch the status to ✅.
3. The `examples/` directory holds the breakdown: task → how AI was applied → result → takeaways.

---

_Author: Sergii Semenov — Frontend Engineer (React, TypeScript). I keep this playbook public to demonstrate an AI-driven approach in practice._
