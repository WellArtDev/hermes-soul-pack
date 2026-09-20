# Hermes SOUL Pack

> A modular collection of production-oriented `SOUL.md` personas for Hermes, OpenClaw-style agents, and other AI agent workflows.

[![AI Agent](https://img.shields.io/badge/AI%20Agent-SOUL.md-blue)](https://github.com/WellArtDev/hermes-soul-pack)
[![Roles](https://img.shields.io/badge/Roles-18-purple)](https://github.com/WellArtDev/hermes-soul-pack/tree/main)
[![Format](https://img.shields.io/badge/Format-Markdown-black)](https://github.com/WellArtDev/hermes-soul-pack)
[![GitHub Stars](https://img.shields.io/github/stars/WellArtDev/hermes-soul-pack?style=flat&logo=github)](https://github.com/WellArtDev/hermes-soul-pack/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/WellArtDev/hermes-soul-pack?style=flat&logo=github)](https://github.com/WellArtDev/hermes-soul-pack/network/members)

## Overview

**Hermes SOUL Pack** is a modular set of role-specific `SOUL.md` files designed to give an AI agent a clear professional identity, workflow, quality standard, and operating discipline for different types of work.

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

| # | Role | Primary Use |
|---|---|---|
| 00 | **Hermes Orchestrator** | General orchestration and task routing |
| 01 | **AI Assistant** | Personal assistance, planning, organization |
| 02 | **Vibe Coding** | Rapid software development |
| 03 | **Full-Stack Engineer** | End-to-end application development |
| 04 | **Database Architect** | Schema, migrations, data architecture |
| 05 | **Security Engineer** | Defensive security and application audits |
| 06 | **UI/UX Designer** | Product design and interface systems |
| 07 | **Social Media Strategist** | Social strategy and content planning |
| 08 | **Content Writer** | Copywriting and editorial content |
| 09 | **Digital Marketing** | Marketing strategy and campaigns |
| 10 | **Brand Strategist** | Brand identity and creative direction |
| 11 | **SEO Specialist** | Technical SEO and search strategy |
| 12 | **Research Analyst** | Research, verification, and synthesis |
| 13 | **Product Manager** | Product requirements and prioritization |
| 14 | **Project Manager** | Planning, execution, risks, milestones |
| 15 | **DevOps / SRE** | Infrastructure and reliability |
| 16 | **QA Engineer** | Testing and quality assurance |
| 17 | **Video Content Creator** | Video concepts, scripts, and creative direction |

---

## Repository Structure

```text
hermes-soul-pack/
│
├── README.md
│
├── 00-HERMES/
│   └── SOUL.md
│
├── 01-AI-ASSISTANT/
│   └── SOUL.md
│
├── 02-VIBE-CODING/
│   └── SOUL.md
│
├── 03-FULLSTACK-ENGINEER/
│   └── SOUL.md
│
├── 04-DATABASE-ARCHITECT/
│   └── SOUL.md
│
├── 05-SECURITY-ENGINEER/
│   └── SOUL.md
│
├── 06-UI-UX-DESIGNER/
│   └── SOUL.md
│
├── 07-SOCIAL-MEDIA/
│   └── SOUL.md
│
├── 08-CONTENT-WRITER/
│   └── SOUL.md
│
├── 09-DIGITAL-MARKETING/
│   └── SOUL.md
│
├── 10-BRANDING/
│   └── SOUL.md
│
├── 11-SEO/
│   └── SOUL.md
│
├── 12-RESEARCHER/
│   └── SOUL.md
│
├── 13-PRODUCT-MANAGER/
│   └── SOUL.md
│
├── 14-PROJECT-MANAGER/
│   └── SOUL.md
│
├── 15-DEVOPS-SRE/
│   └── SOUL.md
│
├── 16-QA-ENGINEER/
│   └── SOUL.md
│
└── 17-VIDEO-CONTENT/
    └── SOUL.md
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
00-HERMES/SOUL.md
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
02-VIBE-CODING/SOUL.md
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

```text
01. Research Analyst
02. Product Manager
03. Content Writer
04. Digital Marketing
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
18-COMPANY-SPECIFIC/
└── SOUL.md
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
│   ├── 00-HERMES/
│   ├── 01-AI-ASSISTANT/
│   ├── 02-VIBE-CODING/
│   ├── ...
│   └── 17-VIDEO-CONTENT/
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

# Roadmap

Potential future additions:

- [ ] Legal / Compliance Researcher
- [ ] Data Analyst
- [ ] Data Engineer
- [ ] Machine Learning Engineer
- [ ] AI Engineer
- [ ] Prompt Engineer
- [ ] Customer Support Agent
- [ ] Sales Development Representative
- [ ] Finance Analyst
- [ ] Operations Manager
- [ ] UX Researcher
- [ ] Creative Director
- [ ] Game Developer
- [ ] Mobile App Developer
- [ ] Technical Writer
- [ ] Solutions Architect

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
Do not add a license file unless you have explicitly selected the license for this project.
