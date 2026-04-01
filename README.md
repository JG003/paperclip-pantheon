# The Paperclip Pantheon

**A complete AI workforce framework for running a company with 21 specialized agents, a 5-member strategic council, and a CEO — all named from Greek mythology because the names encode the jobs.**

Built by Josh Galt at [Anabasis Intelligence](https://anabasisintelligence.com) — a creative AI implementation firm helping businesses operationalize AI workforces.

<!-- Add your banner image: ![Paperclip Pantheon](banner.png) -->

---

## What This Is

An open-source, production-ready template system for deploying a full AI agent workforce to run a company. Not a concept deck. Not a blog post. The actual files you hand to your AI CEO, who then builds out the entire team.

**The system includes:**

- **1 CEO agent** (Ponos) who manages the entire organization
- **21 specialized operatives** across 6 divisions — research, engineering, marketing, operations, revenue, and support
- **5 council advisors** for strategic decision-making — adapted from [Karpathy's LLM Council](https://x.com/karpathy) methodology
- **SOUL files** (identity, mission, responsibilities, voice) and **HEARTBEAT files** (cadence, checklists, escalation protocols) for every agent
- **3 framework documents** — the Pantheon (mythology + org structure), the Council of 5 (decision framework), and the Hiring Plan (sequenced rollout)

Every agent is named from Greek mythology using **nominative determinism** — the name encodes the function. Athena researches. Hermes communicates. Charon ships things. When you hear the name, you know the job.

---

## Why Greek Mythology

This isn't decoration. It's a mnemonic architecture.

A new team member (human or AI) hearing "Athena is working on the research brief" immediately has a mental model of what Athena does and how she thinks — before reading a single line of her configuration. The mythology provides instant intuition about each agent's personality, priorities, and approach.

The family relationships encode organizational dependencies: Mnemosyne (memory) is the mother of Calliope (content) and Erato (creative direction) — because all creative output depends on institutional memory. Apollo (sales) is the father of Asclepius (support) — because every promise sales makes becomes support's responsibility.

---

## The Roster

### CEO
| Agent | Role |
|-------|------|
| **Ponos** | Chief Executive Officer + Council Chairman |

### 21 Operatives

| # | Agent | Role | Division |
|---|-------|------|----------|
| 1 | **Athena** | Scientific / Domain Researcher | Strategy & Intelligence |
| 2 | **Argos** | Realtime News Monitor | Strategy & Intelligence |
| 3 | **Prometheus** | R&D Experiment Runner | Strategy & Intelligence |
| 4 | **Mnemosyne** | Knowledge Manager & CRM | Strategy & Intelligence |
| 5 | **Daedalus** | Modern Web Engineer | Build & Ship |
| 6 | **Hephaestus** | WordPress Engineer | Build & Ship |
| 7 | **Iris** | Designer | Build & Ship |
| 8 | **Calliope** | Content Creator | Market & Brand |
| 9 | **Hermes** | Social Media Marketer | Market & Brand |
| 10 | **Erato** | Creative Director | Market & Brand |
| 11 | **Aether** | PR & Earned Media | Market & Brand |
| 12 | **Hestia** | Community & Customer Success | Market & Brand |
| 13 | **Demeter** | Production Controller | Operations |
| 14 | **Charon** | Logistics & Supply Chain | Operations |
| 15 | **Persephone** | Product Development | Operations |
| 16 | **Chrysus** | Sales Channel Expert | Revenue & Deals |
| 17 | **Apollo** | B2B Sales Agent | Revenue & Deals |
| 18 | **Themis** | Legal & Compliance | Revenue & Deals |
| 19 | **Tyche** | Financial Controller | Revenue & Deals |
| 20 | **Terpsichore** | Events & Live Experiences | Experience & Support |
| 21 | **Asclepius** | Customer Support & QA | Experience & Support |

### Council of 5

| Agent | Role | Tension |
|-------|------|---------|
| **Momus** | The Contrarian | ← Downside vs. Upside → |
| **Eos** | The Expansionist | ← Downside vs. Upside → |
| **Metis** | First Principles Thinker | ← Rethink vs. Act → |
| **Nike** | The Executor | ← Rethink vs. Act → |
| **Proteus** | The Outsider | Keeps everyone honest |

---

## How It Works

### Step 1: Give Ponos his SOUL
Create a company-specific SOUL and HEARTBEAT file for Ponos (the CEO) with your company's context — products, channels, customers, competitors, priorities.

### Step 2: Hand Ponos the templates
Give him the three framework documents and the 54 agent template files from this repo. He reads them and produces company-specific versions based on his deep understanding of the business.

### Step 3: Ponos builds the team
He decides which agents to activate (not every company needs all 21), customizes their SOUL and HEARTBEAT files, and hires them in sequence — revenue first, memory early, events last.

### Step 4: The company runs
Agents operate on heartbeat cadences (every 2–6 hours depending on role). The Council of 5 convenes for high-stakes decisions. Ponos manages everything and reports to the board.

**Most companies can stand up the full system in an afternoon.**

---

## Repo Structure

```
paperclip-pantheon/
├── README.md
├── LICENSE
├── framework/
│   ├── pantheon.md              ← Mythology, org structure, activation guide
│   ├── council-of-5.md          ← Strategic decision framework
│   └── hiring-plan.md           ← Org chart, hiring sequence, daily loop
├── agents/
│   ├── operatives/              ← 22 SOUL + HEARTBEAT files (Ponos + 21 agents)
│   │   ├── ponos-SOUL.md
│   │   ├── ponos-HEARTBEAT.md
│   │   ├── athena-SOUL.md
│   │   ├── athena-HEARTBEAT.md
│   │   └── ... (44 files total)
│   └── council/                 ← 10 SOUL + HEARTBEAT files (5 advisors)
│       ├── momus-SOUL.md
│       ├── momus-HEARTBEAT.md
│       └── ... (10 files total)
```

---

## Not Every Company Needs All 21

The framework includes an **Activation Guide** with three tiers:

**Always Active** (every company): Ponos, Argos, Calliope, Hermes, Iris, Tyche, Mnemosyne

**Usually Active** (most companies): Athena, Apollo, Daedalus, Hephaestus, Themis, Hestia, Asclepius

**Conditional** (activate per need): Prometheus, Demeter, Chrysus, Persephone, Charon, Aether, Erato, Terpsichore

A solo founder might run 7 agents. A product company with physical goods might run all 21. The Council of 5 is always the same everywhere — thinking styles don't change, only context does.

---

## Inspired By

- [Andrej Karpathy](https://x.com/karpathy) — LLM Council methodology and the idea that multiple AI perspectives produce better decisions than a single model
- [Gary Tan](https://x.com/garrytan) — gstack engineering workflow that powers the Build & Ship division
- [Anthropic's Claude](https://claude.ai) — the model powering the agents
- Greek mythology — for encoding organizational logic into memorable, intuitive names since approximately 800 BC

---

## Built With

This system is designed for use with:
- **[Claude](https://claude.ai)** by Anthropic (Opus 4.6 / Sonnet 4.6) as the underlying model
- **[Cowork](https://claude.ai)** by Anthropic for agent management
- **[Claude Code](https://docs.claude.com)** for engineering agents (Daedalus, Hephaestus)
- Compatible with any LLM platform that supports system prompts and tool use

---

## License

MIT — use it, fork it, adapt it, build your own Olympus.

---

## About

Built by **[Anabasis Intelligence](https://anabasisintelligence.com)** — we help traditional businesses and entrepreneurs operationalize AI workforces. If you want us to deploy this for your company instead of doing it yourself, [get in touch](https://anabasisintelligence.com).

**Also available in Spanish** for the Latin American market. (Coming soon — or [contact us](https://anabasisintelligence.com) if you want it now.)

---

*The Greeks built their mythology to encode how the world works. We use it to encode how a company works. The names aren't branding. They're architecture.*
