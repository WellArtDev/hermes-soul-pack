# Hermes SOUL Pack

> A modular collection of production-oriented `SOUL.md` personas for Hermes, OpenClaw-style agents, and other AI agent workflows.

[![Hermes Agent](https://img.shields.io/badge/Built%20for-Hermes%20Agent-blueviolet)](https://github.com/NousResearch/hermes)
[![AI Agent](https://img.shields.io/badge/AI%20Agent-SOUL.md-blue)](https://github.com/WellArtDev/hermes-soul-pack)
[![Roles](https://img.shields.io/badge/Roles-40-purple)](https://github.com/WellArtDev/hermes-soul-pack/tree/main)
[![Format](https://img.shields.io/badge/Format-Markdown-black)](https://github.com/WellArtDev/hermes-soul-pack)
[![GitHub Stars](https://img.shields.io/github/stars/WellArtDev/hermes-soul-pack?style=flat&logo=github)](https://github.com/WellArtDev/hermes-soul-pack/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/WellArtDev/hermes-soul-pack?style=flat&logo=github)](https://github.com/WellArtDev/hermes-soul-pack/network/members)
[![License](https://img.shields.io/github/license/WellArtDev/hermes-soul-pack)](https://github.com/WellArtDev/hermes-soul-pack/blob/main/LICENSE)
## Overview

**Hermes SOUL Pack** is a modular set of role-specific `SOUL.md` files designed to give an AI agent a clear professional identity, workflow, quality standard, and operating discipline for different types of work.

Built for [Hermes Agent](https://github.com/NousResearch/hermes) by [Nous Research](https://github.com/NousResearch), and compatible with OpenClaw, Claude Code, Cursor, and any tool that reads markdown from the project root.

Instead of putting every capability into one huge system prompt, the pack separates responsibilities into focused roles.

For example:

- Coding tasks can use the **Vibe Coding** or **Full-Stack Engineer** persona.
- Database work can use the **Database Architect** persona.
- Security reviews can use the **Security Engineer** persona.
- Social campaigns can use the **Social Media Strategist** persona.
- Writing tasks can use the **Content Writer** persona.
- Product planning can use the **Product Manager** persona.
- Infrastructure work can use the **DevOps / SRE** persona.

The result is a cleaner and more maintainable AI-agent workflow.

## Not a Standard — a Reference

This pack is **not a framework, library, or product**. It does not install anything, expose an API, or run code.

What it contains is text files: one `SOUL.md` per role, each describing how an agent should work in that discipline. Nothing more.

- **Copy them.** Use a file as the system prompt or context for your agent, in any tool you already use.
- **Edit them.** A SOUL is written to be adapted. Delete what does not fit your stack, team, or product.
- **Combine them.** Use several at once, or take only the quality gates and anti-patterns.
- **Ignore them.** No file here is required by anything. Nothing breaks if you do not follow one.

The SOUL files carry **no credentials, no configuration, no tool bindings, and no environment assumptions**. They describe behavior and methodology only. If your setup needs secrets, tokens, or platform-specific wiring, that belongs in your own project configuration — never inside a SOUL.

---

## Why SOUL.md?

An AI agent can have access to powerful models and tools, but tools alone do not define **how the agent should work**.

A good `SOUL.md` establishes:

- identity
- mission
- behavior
- decision-making principles
- workflow
- quality gates
- output expectations
- domain-specific rules
- common anti-patterns

Think of each SOUL file as a **professional operating profile** for the agent.

The goal is not to create a fictional personality. The goal is to create consistent, useful working behavior.

---

## Included Roles

Roles are grouped by category. Each folder holds one `SOUL.md`.

| Category | # | Role | Primary Use |
|---|---|---|---|
| Orchestration | 00 | [**Hermes Orchestrator**](./orchestration/hermes-orchestrator) | General orchestration and task routing |
| Office | 01 | [**AI Assistant**](./office/ai-assistant) | Personal assistance, planning, organization |
| | 14 | [**Project Manager**](./office/project-manager) | Planning, execution, risks, milestones |
| Engineering | 02 | [**Vibe Coding**](./engineering/vibe-coding) | Rapid software development |
| | 03 | [**Full-Stack Engineer**](./engineering/fullstack-engineer) | End-to-end application development |
| | 04 | [**Database Architect**](./engineering/database-architect) | Schema, migrations, data architecture |
| | 15 | [**DevOps / SRE**](./engineering/devops-sre) | Infrastructure and reliability |
| | 16 | [**QA Engineer**](./engineering/qa-engineer) | Testing and quality assurance |
| | 20 | [**Cloud Cost Engineer (FinOps)**](./engineering/cloud-cost-finops) | Cloud spend analysis, rightsizing, unit economics |
| | 22 | [**Game Developer**](./engineering/game-developer) | Interactive systems, core loops, frame budgets |
| | 23 | [**Mobile App Developer**](./engineering/mobile-app-developer) | Lifecycle, offline-first, low-end devices |
| | 24 | [**Solutions Architect**](./engineering/solutions-architect) | Tradeoffs, failure design, ADRs |
| | 25 | [**Automation / Integration Engineer**](./engineering/automation-integration-engineer) | Reliable, observable, recoverable integrations |
| | 26 | [**Incident Commander**](./engineering/incident-commander) | Coordination and blameless postmortems |
| Security | 05 | [**Security Engineer**](./security/security-engineer) | Defensive security and application audits |
| | 21 | [**Penetration Tester**](./security/penetration-tester) | Authorized offensive testing of running systems |
| Compliance | 19 | [**Privacy & Compliance Officer**](./compliance/privacy-compliance) | UU PDP / GDPR, data mapping, consent, retention |
| Product | 13 | [**Product Manager**](./product/product-manager) | Product requirements and prioritization |
| Design | 06 | [**UI/UX Designer**](./design/ui-ux-designer) | Product design and interface systems |
| | 27 | [**UX Researcher**](./design/ux-researcher) | Behavioral research, evidence over opinion |
| | 28 | [**Accessibility Specialist**](./design/accessibility-specialist) | WCAG, assistive technology, one product for all |
| | 29 | [**Creative Director**](./design/creative-director) | Brand standard, briefs, feedback craft |
| Data | 30 | [**Data Analyst**](./data/data-analyst) | Business questions answered with data |
| | 31 | [**Data Engineer**](./data/data-engineer) | Reliable, observable, idempotent pipelines |
| | 32 | [**Machine Learning Engineer**](./data/machine-learning-engineer) | Models as monitored production systems |
| AI | 33 | [**AI Engineer**](./ai/ai-engineer) | LLM product features: retrieval, tools, guardrails |
| | 34 | [**Prompt Engineer**](./ai/prompt-engineer) | Versioned, measured, eval-driven prompts |
| Marketing | 07 | [**Social Media Strategist**](./marketing/social-media-strategist) | Social strategy and content planning |
| | 09 | [**Digital Marketing**](./marketing/digital-marketing) | Marketing strategy and campaigns |
| | 10 | [**Brand Strategist**](./marketing/brand-strategist) | Brand identity and creative direction |
| | 11 | [**SEO Specialist**](./marketing/seo-specialist) | Technical SEO and search strategy |
| Content | 08 | [**Content Writer**](./content/content-writer) | Copywriting and editorial content |
| | 17 | [**Video Content Creator**](./content/video-content-creator) | Video concepts, scripts, and creative direction |
| | 18 | [**Technical Writer**](./content/technical-writer) | API docs, runbooks, and architecture decision records |
| Research | 12 | [**Research Analyst**](./research/research-analyst) | Research, verification, and synthesis |
| Business | 35 | [**Customer Support Agent**](./business/customer-support-agent) | Resolution and honest escalation |
| | 36 | [**Sales Development Representative**](./business/sales-development-representative) | Qualified conversations, not booked noise |
| | 37 | [**Finance Analyst**](./business/finance-analyst) | Cash, burn, runway, unit economics |
| | 38 | [**Operations Manager**](./business/operations-manager) | Processes that survive a person leaving |
| Education | 39 | [**Technical Mentor**](./education/technical-mentor) | Builds learners who no longer need you |

---

## Repository Structure

```text
hermes-soul-pack/
│
├── README.md
├── LICENSE
│
├── orchestration/
│   └── hermes-orchestrator/SOUL.md
│
├── office/
│   ├── ai-assistant/SOUL.md
│   └── project-manager/SOUL.md
│
├── engineering/
│   ├── vibe-coding/SOUL.md
│   ├── fullstack-engineer/SOUL.md
│   ├── database-architect/SOUL.md
│   ├── devops-sre/SOUL.md
│   ├── qa-engineer/SOUL.md
│   ├── cloud-cost-finops/SOUL.md
│   ├── game-developer/SOUL.md
│   ├── mobile-app-developer/SOUL.md
│   ├── solutions-architect/SOUL.md
│   ├── automation-integration-engineer/SOUL.md
│   └── incident-commander/SOUL.md
│
├── security/
│   ├── security-engineer/SOUL.md
│   └── penetration-tester/SOUL.md
│
├── compliance/
│   └── privacy-compliance/SOUL.md
│
├── product/
│   └── product-manager/SOUL.md
│
├── design/
│   ├── ui-ux-designer/SOUL.md
│   ├── ux-researcher/SOUL.md
│   ├── accessibility-specialist/SOUL.md
│   └── creative-director/SOUL.md
│
├── data/
│   ├── data-analyst/SOUL.md
│   ├── data-engineer/SOUL.md
│   └── machine-learning-engineer/SOUL.md
│
├── ai/
│   ├── ai-engineer/SOUL.md
│   └── prompt-engineer/SOUL.md
│
├── marketing/
│   ├── social-media-strategist/SOUL.md
│   ├── digital-marketing/SOUL.md
│   ├── brand-strategist/SOUL.md
│   └── seo-specialist/SOUL.md
│
├── content/
│   ├── content-writer/SOUL.md
│   ├── video-content-creator/SOUL.md
│   └── technical-writer/SOUL.md
│
├── research/
│   └── research-analyst/SOUL.md
│
├── business/
│   ├── customer-support-agent/SOUL.md
│   ├── sales-development-representative/SOUL.md
│   ├── finance-analyst/SOUL.md
│   └── operations-manager/SOUL.md
│
└── education/
    └── technical-mentor/SOUL.md
```

---

## Design Philosophy

### 1. Modular

Each role has its own `SOUL.md`.

You can use one role independently or combine several roles in a larger workflow.

### 2. Role-focused

Each SOUL is written around a specific professional responsibility rather than trying to make one prompt do everything.

### 3. Execution-oriented

The personas emphasize actual work:

```text
Understand
   ↓
Plan
   ↓
Execute
   ↓
Verify
   ↓
Report
```

### 4. Quality-aware

The roles include domain-specific quality checks instead of simply telling the agent to "be helpful."

### 5. Tool-agnostic

The SOUL files focus on behavior and methodology.

Tool configuration, API credentials, environment variables, model settings, and platform-specific configuration should remain outside the SOUL files.

---

# Usage

## Option 1: Use Hermes as the Main Orchestrator

Start with:

```text
orchestration/hermes-orchestrator/SOUL.md
```

Hermes acts as the general coordinator.

Then select a specialist role based on the task.

Example:

```text
User
  │
  ▼
Hermes
  │
  ├── Coding ──────────────► Vibe Coding
  │
  ├── Database ────────────► Database Architect
  │
  ├── Security ────────────► Security Engineer
  │
  ├── UI/UX ───────────────► UI/UX Designer
  │
  ├── Marketing ───────────► Digital Marketing
  │
  ├── Content ─────────────► Content Writer
  │
  └── Research ────────────► Research Analyst
```

---

## Option 2: Use a Single Specialist

If your workflow already provides the routing layer, you can use only the relevant SOUL.

For example:

```text
SOUL.md
```

can contain the contents of:

```text
engineering/vibe-coding/SOUL.md
```

for a coding-focused agent.

---

## Option 3: Combine Roles

Complex projects can use multiple specialist roles.

For example, launching a SaaS product might involve:

```text
Product Manager
       ↓
UI/UX Designer
       ↓
Full-Stack Engineer
       ↓
Database Architect
       ↓
Security Engineer
       ↓
QA Engineer
       ↓
DevOps / SRE
```

Marketing can then continue with:

```text
Brand Strategist
       ↓
Content Writer
       ↓
Social Media Strategist
       ↓
Digital Marketing
       ↓
SEO Specialist
```

---

# Recommended Workflow

For software projects:

```text
01. Product Manager
02. UI/UX Designer
03. Database Architect
04. Full-Stack Engineer
05. Security Engineer
06. QA Engineer
07. DevOps / SRE
08. Project Manager
```

For content projects:

```text
01. Brand Strategist
02. Digital Marketing
03. Content Writer
04. Social Media Strategist
05. Video Content Creator
06. SEO Specialist
```

For research-heavy projects:

```
01. Research Analyst
02. Product Manager
03. Content Writer
04. Digital Marketing
```

For a product touching personal data (most products):

```
01. Product Manager
02. Privacy & Compliance Officer
03. UI/UX Designer
04. Database Architect
05. Full-Stack Engineer
06. Security Engineer
07. Technical Writer
08. QA Engineer
```

For a product already running in production:

```
01. DevOps / SRE
02. Cloud Cost Engineer (FinOps)
03. Database Architect
04. Technical Writer
05. QA Engineer
```

These are suggested workflows, not mandatory dependencies.

---

# Example: Vibe Coding

When working on an existing codebase, the Vibe Coding SOUL encourages the agent to:

```text
Inspect repository
       ↓
Understand architecture
       ↓
Identify relevant files
       ↓
Plan smallest safe change
       ↓
Implement
       ↓
Typecheck
       ↓
Run tests
       ↓
Review diff
       ↓
Report evidence
```

This is intentionally different from a generic "write some code" prompt.

---

# Example: Content Creation

A content workflow can follow:

```text
Brand
  ↓
Audience
  ↓
Objective
  ↓
Content Pillar
  ↓
Hook
  ↓
Content
  ↓
CTA
  ↓
Platform Adaptation
```

The Social Media and Content Writer roles are designed to work together while keeping their responsibilities distinct.

---

# Quality Principles

All roles follow several shared principles.

## Do Not Invent

The agent should never fabricate:

- research results
- tool results
- files
- URLs
- implementation status
- test results
- business facts
- product specifications

## Verify Before Claiming Completion

A task should not be described as completed merely because an implementation was written.

Where applicable, completion should include verification.

## Separate Facts From Assumptions

When information is uncertain, the agent should distinguish:

```text
FACT
ASSUMPTION
HYPOTHESIS
RECOMMENDATION
```

This is especially important for research, marketing, product strategy, and technical decisions.

## Prefer Small Safe Changes

For existing systems, avoid unnecessary rewrites.

Understand the current implementation first, then make the smallest change that solves the problem.

---

# Customization

The SOUL files are intentionally editable.

You can customize:

- communication style
- coding conventions
- technology stack
- brand voice
- project management methodology
- testing requirements
- security standards
- output format
- company-specific rules
- domain knowledge

For example, a company can create:

```text
your-company/SOUL.md
```

and define its own operating rules.

---

# Recommended Project-Level Structure

For a larger AI-agent setup, you can separate responsibilities like this:

```text
agent/
│
├── SOUL.md
├── AGENTS.md
├── RULES.md
├── TOOLS.md
├── MEMORY.md
│
├── souls/
│   ├── orchestration/
│   ├── engineering/
│   ├── security/
│   └── .../
│
└── projects/
    ├── project-a/
    ├── project-b/
    └── project-c/
```

Keep responsibilities separated:

| File | Purpose |
|---|---|
| `SOUL.md` | Agent identity and behavior |
| `AGENTS.md` | Project/workspace instructions |
| `RULES.md` | Hard operational rules |
| `TOOLS.md` | Tool usage information |
| `MEMORY.md` | Persistent context |
| `souls/*` | Specialist role profiles |

---

# Who Is This For?

This pack can be useful for:

- AI agent builders
- developers
- startup teams
- indie hackers
- product teams
- creative teams
- marketing teams
- automation builders
- AI-assisted development workflows
- Hermes/OpenClaw-style environments

---

# Extending the Pack

New roles can follow this structure:

```md
# SOUL.md — Role Name

## Identity

Who is the agent in this role?

## Mission

What outcome is it responsible for?

## Core Rules

How should it behave?

## Workflow

What process should it follow?

## Quality Gates

How does it verify its work?

## Output

What should the final result look like?

## Anti-Patterns

What should it avoid?
```

Keep new roles focused.

A good SOUL should answer:

> "How should an AI agent work when it is operating as this professional?"

rather than attempting to document the entire software platform.

---

## Roadmap

Roles previously listed as future additions, now implemented:

- ~~Data Analyst~~ → 30
- ~~Data Engineer~~ → 31
- ~~Machine Learning Engineer~~ → 32
- ~~AI Engineer~~ → 33
- ~~Prompt Engineer~~ → 34
- ~~Customer Support Agent~~ → 35
- ~~Sales Development Representative~~ → 36
- ~~Finance Analyst~~ → 37
- ~~Operations Manager~~ → 38
- ~~UX Researcher~~ → 27
- ~~Creative Director~~ → 29
- ~~Game Developer~~ → 22
- ~~Mobile App Developer~~ → 23
- ~~Solutions Architect~~ → 24
- ~~Incident Commander~~ → 26
- ~~Automation / Integration Engineer~~ → 25
- ~~Accessibility Specialist~~ → 28
- ~~Technical Mentor / Tutor~~ → 39

Earlier additions not on the original list:

- ~~Technical Writer~~ → 18 (added for docs that stay true to the code)
- ~~Privacy & Compliance Officer~~ → 19 (added for UU PDP / GDPR relevance)
- ~~Cloud Cost Engineer (FinOps)~~ → 20 (added for production-stage products)
- ~~Penetration Tester~~ → 21 (the Security Engineer role is defensive; offensive testing of running systems is a separate discipline)

---

# Contributing

Contributions are welcome.

When adding a new SOUL:

1. Give it one clear professional responsibility.
2. Avoid overlapping heavily with an existing role.
3. Define a practical workflow.
4. Include quality gates.
5. Avoid fabricated tool assumptions.
6. Keep the instructions readable.
7. Explain the intended use case in the pull request.

---

# Philosophy

The goal of this project is simple:

> **Give AI agents better operating habits, not just bigger prompts.**

A capable model can generate an answer.

A well-designed agent should know:

```text
what to do
why it is doing it
how to do it
how to verify it
when to ask
when to stop
and how to report the result
```

That is what the Hermes SOUL Pack is designed to provide.

---

## License

Hermes SOUL Pack is licensed under the [MIT License](./LICENSE).

---

## Disusun Oleh

**Yukie** — artificial intelligence companion of [WellA](https://github.com/WellArtDev), built on [Hermes Agent](https://github.com/NousResearch/hermes) by Nous Research.

Role catalog, category structure, and every `SOUL.md` in this pack were drafted, reviewed, and committed by Yukie. Community references consulted along the way: [awesome-agent-souls](https://github.com/opena2a-org/awesome-agent-souls) and the [Soul.md specification](https://github.com/rokoss21/soul.md).
