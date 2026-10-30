# Premium UI/UX Agent System

### Elevating AI-generated interfaces to production-grade design.

A framework-agnostic design intelligence and quality engineering system for AI coding agents. Built to move beyond generic AI-generated layouts and establish a consistent standard for sophisticated, accessible, responsive, and production-ready interfaces.

<p align="center">
  <strong>Premium Visuals · Sophisticated Motion · Clean Architecture · Production Quality</strong>
</p>

<p align="center">
  <a href="https://github.com/JBCyberLogics/premium-ui-ux-agent-system">
    <img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository">
  </a>
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge" alt="Version 1.0.0">
  <img src="https://img.shields.io/badge/Platform-Linux%20%7C%20Windows-lightgrey?style=for-the-badge" alt="Linux and Windows">
  <img src="https://img.shields.io/badge/AI%20Agents-Codex%20%7C%20OpenCode%20%7C%20Claude%20%7C%20Gemini-purple?style=for-the-badge" alt="AI Agent Compatibility">
</p>

---

## Overview

AI coding agents have made software development faster, but speed does not always translate into exceptional design.

Generic layouts, repetitive components, inconsistent spacing, unnecessary animations, and weak visual hierarchy remain common problems in AI-generated interfaces.

**Premium UI/UX Agent System** addresses this challenge through a structured set of design principles, implementation standards, workflows, and quality evaluation criteria.

It equips AI coding agents with a more deliberate approach to interface development: understand the project, establish a creative direction, implement with precision, inspect the result, and continuously refine the experience.

The system is designed to work across different frameworks, programming languages, and software-development environments.

## Core Philosophy

> Design with intention. Build with precision. Deliver with quality.

The system establishes four foundational standards:

| Standard | Objective |
|---|---|
| Premium Visuals | Sophisticated composition, typography, spacing, imagery, and hierarchy. |
| Sophisticated Motion | Purposeful animations, transitions, and meaningful interactions. |
| Clean Architecture | Maintainable components, reusable patterns, and sound implementation. |
| Production Quality | Responsive, accessible, performant, and thoroughly validated interfaces. |

## Key Capabilities

### Design Intelligence
- Establishes a deliberate visual direction before implementation.
- Encourages reference research and creative exploration.
- Avoids repetitive, generic interface patterns.
- Promotes thoughtful composition and information hierarchy.

### Design System Engineering
- Encourages consistent design tokens and reusable components.
- Establishes typography, spacing, colour, and component standards.
- Promotes consistency across application pages and features.

### Motion and Interaction
- Applies purposeful transitions and micro-interactions.
- Encourages sophisticated animation without unnecessary visual distractions.
- Considers performance and accessibility in motion decisions.

### Responsive and Accessible Design
- Addresses desktop, tablet, and mobile experiences.
- Establishes practical accessibility expectations.
- Encourages keyboard accessibility and appropriate interaction feedback.

### Technical Implementation
- Respects existing project architecture and working functionality.
- Encourages maintainable and scalable implementation.
- Considers performance, library selection, and implementation quality.
- Prohibits fabricated real-world application data.

### Visual Quality Assurance
- Requires visual inspection whenever suitable tools are available.
- Uses structured auditing and acceptance criteria.
- Evaluates completed implementations against a weighted quality framework.

---

## Quality Evaluation Framework

A structured 100-point scoring system evaluates the quality of completed work.

| Evaluation Area | Weight |
|---|---:|
| Visual Design and Composition | 20 |
| UX and Usability | 20 |
| Design System and Consistency | 15 |
| Responsive Design | 10 |
| Motion and Interactions | 10 |
| Accessibility | 10 |
| Technical Quality and Performance | 10 |
| Originality and Creative Direction | 5 |
| **TOTAL** | **100** |

Critical quality failures can override the numerical score.

The evaluation is intended to encourage measurable improvements rather than subjective claims of good design.

---

# Installation

The system is designed for global installation, making the skill available across projects without copying its instructions into every repository.

**Repository URL:**

```text
https://github.com/JBCyberLogics/premium-ui-ux-agent-system
```

### Requirements

- Git installed.
- A supported AI coding agent.
- Internet connection.

## Linux Installation

### Option 1 — Codex and OpenCode

Open your terminal and execute:

```bash
mkdir -p ~/.agents/skills

git clone https://github.com/JBCyberLogics/premium-ui-ux-agent-system.git \
~/.agents/skills/premium-ui-ux
```

This installs the skill in the shared Agent Skills directory.

### Option 2 — OpenCode Dedicated Directory

```bash
mkdir -p ~/.config/opencode/skills

git clone https://github.com/JBCyberLogics/premium-ui-ux-agent-system.git \
~/.config/opencode/skills/premium-ui-ux
```

### Option 3 — Claude Code

```bash
mkdir -p ~/.claude/skills

git clone https://github.com/JBCyberLogics/premium-ui-ux-agent-system.git \
~/.claude/skills/premium-ui-ux
```

## Windows Installation

Open **PowerShell**.

### Option 1 — Codex and OpenCode

```powershell
New-Item -ItemType Directory -Force "$HOME\.agents\skills"

git clone https://github.com/JBCyberLogics/premium-ui-ux-agent-system.git "$HOME\.agents\skills\premium-ui-ux"
```

### Option 2 — OpenCode Dedicated Directory

```powershell
New-Item -ItemType Directory -Force "$HOME\.config\opencode\skills"

git clone https://github.com/JBCyberLogics/premium-ui-ux-agent-system.git "$HOME\.config\opencode\skills\premium-ui-ux"
```

### Option 3 — Claude Code

```powershell
New-Item -ItemType Directory -Force "$HOME\.claude\skills"

git clone https://github.com/JBCyberLogics/premium-ui-ux-agent-system.git "$HOME\.claude\skills\premium-ui-ux"
```

## Verify Installation

Check that the installed directory contains:

```text
premium-ui-ux/
├── SKILL.md
├── PREMIUM_UI_UX.md
├── README.md
├── governance/
├── evaluation/
├── technical-guidance/
├── workflows/
└── maintenance/
```

Restart your coding agent after installation.

## Activating the Skill

Once installed, instruct your AI coding agent:

```text
Use the premium-ui-ux skill.

Read SKILL.md and follow PREMIUM_UI_UX.md as
the authoritative design specification.

Apply the complete design, implementation,
and quality evaluation standards to this project.
```

The skill can also be selected automatically when relevant, depending on the agent's discovery and activation mechanism.

---

## Updating the Skill

To retrieve the latest repository changes:

**Linux**

```bash
cd ~/.agents/skills/premium-ui-ux
git pull
```

**Windows PowerShell**

```powershell
Set-Location "$HOME\.agents\skills\premium-ui-ux"
git pull
```

If you installed the skill in a different directory, navigate to that directory instead.

---

## Repository Architecture

The system is organized into specialized documents to keep instructions structured, maintainable, and easy for agents to reference.

```text
premium-ui-ux-agent-system/
│
├── README.md
├── SKILL.md
├── PREMIUM_UI_UX.md
│
├── governance/
│   ├── DESIGN_DECISION_PROTOCOL.md
│   ├── QUALITY_ACCEPTANCE_CRITERIA.md
│   └── AGENT_AUTONOMY_AND_APPROVALS.md
│
├── evaluation/
│   ├── UI_UX_QUALITY_SCORING.md
│   ├── VISUAL_AUDIT_CHECKLIST.md
│   └── DELIVERY_REPORT_TEMPLATE.md
│
├── technical-guidance/
│   ├── ANIMATION_AND_MOTION_GUIDELINES.md
│   ├── TECHNOLOGY_AND_LIBRARY_SELECTION.md
│   ├── RESPONSIVE_AND_ACCESSIBILITY_STANDARDS.md
│   └── PERFORMANCE_AND_IMPLEMENTATION_STANDARDS.md
│
├── workflows/
│   ├── PROJECT_DISCOVERY_AND_DESIGN_WORKFLOW.md
│   ├── EXISTING_PROJECT_AUDIT.md
│   └── REFERENCE_RESEARCH_WORKFLOW.md
│
└── maintenance/
    ├── LIBRARY_REVIEW_AND_MAINTENANCE.md
    ├── CHANGELOG.md
    └── VERSIONING_POLICY.md
```

## Design and Engineering Principles

The system follows these principles across supported development workflows:

1. **Understand before implementing** — inspect project requirements, architecture, and existing functionality.
2. **Design with intention** — establish a coherent visual direction instead of relying on generic templates.
3. **Prioritize user experience** — visual sophistication must never compromise usability.
4. **Maintain consistency** — use coherent design systems and reusable patterns.
5. **Animate purposefully** — motion should improve interaction, feedback, or visual communication.
6. **Preserve functionality** — avoid breaking existing features or introducing unnecessary architectural changes.
7. **Use honest data** — never fabricate real users, products, transactions, analytics, or application records.
8. **Validate everything** — inspect the actual interface and address visual, responsive, and technical defects.
9. **Deliver production-quality work** — prioritize accessibility, performance, and maintainability.

## Supported Agents

The framework is designed to support:

- OpenCode
- OpenAI Codex
- Claude Code
- Gemini CLI
- Other compatible AI coding agents through manual integration.

Agent discovery, installation directories, and automatic activation vary between environments.

---

## Contributing

Contributions and improvements are welcome.

To contribute:

1. Fork this repository.
2. Create a feature branch.
3. Implement your changes.
4. Validate documentation and internal links.
5. Submit a pull request explaining your contribution.

Contributions should preserve the framework's core philosophy while improving its clarity, compatibility, practicality, or technical depth.

## Roadmap

Potential future improvements:

- Expanded AI coding agent compatibility.
- More advanced visual quality verification.
- Improved design-system engineering guidance.
- Expanded animation and interaction standards.
- Additional evaluation methods.
- Continuous refinement of technology and library recommendations.

## License

Distributed under the MIT License. See [LICENSE](./LICENSE) for details.

---

## Project

**Developed and maintained by [JBCyberLogics](https://github.com/JBCyberLogics/).**

If this project helps improve your AI-assisted development workflow, consider giving the repository a star and sharing it with other developers.

<p align="center">
  <strong>Premium UI/UX Agent System</strong><br>
  <em>Raising the standard of AI-driven interface development.</em>
</p>
