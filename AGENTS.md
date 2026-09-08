# AGENTS.md — Repository Router

Read this first. Follow only the link needed for the task; do not preload documentation.

**Core Fast Links:** [Workflow](https://github.com/tbhrc/skills/tree/main/github-agent-workflow) · [LIB1 Librarian](https://github.com/tbhrc/skills/tree/main/ecosystem-librarian) · [Document Strategy](https://github.com/tbhrc/skills/blob/main/governance/strategies/strategy-cold-start-context-reduction.md) · [Founder Output](https://github.com/tbhrc/skills/blob/main/github-agent-workflow/SKILL.md#founder-facing-output) · [Anti-Friction Security](https://github.com/tbhrc/skills/blob/main/governance/policies/real-boundary-security-and-friction.md) · [Sniper](https://github.com/tbhrc/skills/blob/main/human-ai-operations-map/references/ai-sniper-entry-map.md) · [Multi-Agent Orchestrator](https://github.com/tbhrc/skills/tree/main/github-multi-agent-orchestrator)

**Repository Fast Links:** [Opportunities](https://github.com/tbhrc/skills/tree/main/drf-opportunity-factory) · [BD](bd/README.md) · [Intelligence](https://github.com/tbhrc/skills/tree/main/automations-drf-intelligence) · [Portfolio](businesses/PORTFOLIO-V3.md) · [CRM](https://github.com/tbhrc/drf-main/issues/157) · [Research](https://github.com/tbhrc/research) · [Issues](https://github.com/tbhrc/drf-main/issues) · [Universal DB migration](https://github.com/tbhrc/crm/issues/5) · [Central Marketing](https://github.com/tbhrc/marketing) · [Central Sales](https://github.com/tbhrc/sales)

## Route

- **Known owner + bounded task** → execute with the most-specific Skill/tool.
- **Owner unclear** → use Sniper once, then execute.
- **Any task that will create, file, move, rename or supersede a durable document/output** → run [LIB1](https://github.com/tbhrc/skills/tree/main/ecosystem-librarian) first for canonical placement, semantic vocabulary and material inbound/outbound Fast Links; then hand execution to the owning Skill/workflow. LIB1 is not an approval gate.
- **Ordinary authorised work** → Level 0 Direct.
- **Department boundary** → DRF owns opportunity discovery, underwriting, ranking, benchmarking and proof. Marketing execution routes to `tbhrc/marketing`; sales pursuit/conversion routes to `tbhrc/sales`; neutral person/organisation/endpoints/shared relationship data route to the universal DB foundation (current live path `tbhrc/crm`, approved rename to `tbhrc/db` under `crm#5`). CRM/BD are domain views/workflows over DB rather than competing identity databases.
- **Creating/updating/reviewing a Skill** → use [Skill Builder](https://github.com/tbhrc/skills/tree/main/github-skill-builder) after LIB1 resolves placement/identity; it owns Skill lifecycle and loads Document Strategy/Policies conditionally.
- **Creating/materially restructuring non-Skill agent-consumed operational documentation** → after LIB1 resolves placement/semantics/links, use Workflow + [Document Strategy](https://github.com/tbhrc/skills/blob/main/governance/strategies/strategy-cold-start-context-reduction.md) only for substantive document architecture.
- **Genuine specialist/parallel need** → Multi-Agent Orchestrator only when one direct stream is insufficient.
- **Actual consequential boundary** → load only the exact relevant policy/control.

## Rules

- **DB before a new contact silo.** A prospect, client contact, candidate or partner may be the same real entity. Reuse the DB identity and keep DRF opportunity/underwriting state in DRF rather than creating another identity root.
- **Work first.** Do not create/update/check an Issue, label, comment, approval, plan, benchmark, proof workflow or documentation merely to unlock execution.
- Issues are optional continuity/evidence records, never runtime permission.
- **Founder scan speed.** Follow the [Workflow founder-facing output convention](https://github.com/tbhrc/skills/blob/main/github-agent-workflow/SKILL.md#founder-facing-output): concise `🟢 GREEN` / `🟠 AMBER` / `🔴 RED` status, `✅` for confirmed completed items, evidence-backed percentages only, and a clickable `Issue: #N` footer when applicable.
- **Friction masquerading as security is prohibited.** Use purpose-fit authority sufficient for the intended function; do not narrow access or add credential/approval layers without a concrete current boundary.
- Human approval is reserved for genuine consequential boundaries: root/super-admin authority changes, destructive/irreversible actions, spend, legal/compliance commitments, private-data disclosure or material external/client commitments.
- Reusable HOW belongs in canonical Skills; load only what the task needs.
- Preserve unrelated newer work and avoid concurrent mutation collisions where they are real.
- Never expose secrets or unnecessary private/client data.
- Verify the requested outcome once, record continuity only when useful, then stop.

**`main` keeps progress. Universal DB keeps identity neutral. DRF owns opportunity judgement. KISSS keeps speed.**