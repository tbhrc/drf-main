# AGENTS.md — Repository Router

This file is the repository **Router** and cold-start contract. Read it first. Follow only the Fast Link needed for the task; do not preload linked material.

**Core Fast Links:** [Workflow](https://github.com/tbhrc/skills/tree/main/github-agent-workflow) · [Governance](https://github.com/tbhrc/skills/tree/main/governance) · [Terminology](https://github.com/tbhrc/skills/blob/main/governance/policies/agent-operating-system-terminology.md) · [Context Budget](https://github.com/tbhrc/skills/blob/main/governance/policies/agent-operating-system-context-budget.md) · [Issue Template](https://github.com/tbhrc/skills/blob/main/.github/ISSUE_TEMPLATE/durable-work.md) · [Sniper](https://github.com/tbhrc/skills/blob/main/human-ai-operations-map/references/ai-sniper-entry-map.md) · [Multi-Agent Orchestrator](https://github.com/tbhrc/skills/tree/main/github-multi-agent-orchestrator)

<!-- REPOSITORY_FAST_LINKS_START -->
**Repository Fast Links:** [Opportunities](https://github.com/tbhrc/skills/tree/main/drf-opportunity-factory) · [BD](bd/README.md) · [Intelligence](https://github.com/tbhrc/skills/tree/main/automations-drf-intelligence) · [Portfolio](businesses/PORTFOLIO-V3.md) · [CRM](https://github.com/tbhrc/drf-main/issues/157) · [Research](https://github.com/tbhrc/research) · [Issues](https://github.com/tbhrc/drf-main/issues)
<!-- REPOSITORY_FAST_LINKS_END -->

## Route

- **Known owner + bounded task** → use the most-specific repository Fast Link / Skill and execute.
- **Owner or source unclear** → use [Sniper](https://github.com/tbhrc/skills/blob/main/human-ai-operations-map/references/ai-sniper-entry-map.md).
- **Normal authorised durable GitHub work** → Level 0 Direct; load [Workflow](https://github.com/tbhrc/skills/tree/main/github-agent-workflow) only when Hybrid or Controlled may be needed.
- **Private cross-repository GitHub access** → never assume a repository `GITHUB_TOKEN` crosses private repository boundaries; use the relevant proven authorised operator/access mechanism already documented in canonical Skills/capabilities rather than inventing credentials.
- **Multiple agents, specialist delegation or genuine parallel work** → use [Multi-Agent Orchestrator](https://github.com/tbhrc/skills/tree/main/github-multi-agent-orchestrator).
- **Governed boundary** → load only the exact relevant [Governance](https://github.com/tbhrc/skills/tree/main/governance) Policy/SOP.
- **Creating a new durable Issue** → use the canonical [Issue Template](https://github.com/tbhrc/skills/blob/main/.github/ISSUE_TEMPLATE/durable-work.md).
- **Material new/changed founder instruction** → update the controlling Issue first, then continue.

## Rules

- Fast Links are pointers, not preload instructions.
- Reusable HOW belongs in canonical Skills; load only the Skill needed for the task.
- Use one controlling Issue for substantive durable work and recover from Issue + current `main`, not chat reconstruction.
- Founder-facing output: make every mentioned navigable GitHub object clickable when a stable URL is known. For substantive durable work, always state the controlling Issue as a compact clickable `#<number>` label, with repository context when needed to avoid ambiguity.
- Fresh-read targets, preserve unrelated newer work, and keep one active writer per unresolved mutation scope.
- Never commit secrets, credentials, private candidate/client evidence or unnecessary PII.
- Root/security, production/destructive, spend, private-data, legal/compliance and material client-commitment gates remain binding when crossed.
- Verify the requested outcome once, update/close the controlling Issue with DONE or one exact blocker/next action, then stop.

**Issue keeps continuity. `main` keeps progress. KISSS keeps speed.**
