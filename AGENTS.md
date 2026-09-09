# AGENTS.md — Repository Router

**Structural class:** G — programme / revenue / research owner. See [org pre-structure](https://github.com/tbhrc/org/blob/main/700-architecture/organisation-pre-structure.md).

<!-- ROUTER_SHARED_LIFECYCLE_START -->
**Issue Gate:** Every substantive or durable work unit requires a master controlling Issue; create new substantive Issues from the canonical [Durable Work template](https://github.com/tbhrc/skills/blob/main/.github/ISSUE_TEMPLATE/durable-work.md).

**FolderDesk Lifecycle / Lever:** For substantive ideas/work originating in conversation, use the canonical [Lifecycle Lever](https://github.com/tbhrc/skills/blob/main/github-agent-workflow/scripts/lifecycle_set.py) owned by the [Lifecycle of FolderDesk](https://github.com/tbhrc/skills/blob/main/docs/lifecycle/folderdesk-lifecycle.md): search/reuse first; create exactly once at the truthful initial `idea` or `discussion` stage with priority in the same mutation; later choose the semantic stage through the Lever/native adapter rather than reconstructing label mechanics; lifecycle metadata is evidence/navigation, never runtime permission.

**Close Gate:** Before closing any Issue, read and reconcile its current body; every required `## Checklist` and `## Acceptance Criteria` item must be `[x]`, otherwise keep the Issue open.
<!-- ROUTER_SHARED_LIFECYCLE_END -->
Read this first. Follow only the link needed for the task; do not preload documentation.

**Core Fast Links:** [Workflow](https://github.com/tbhrc/skills/tree/main/github-agent-workflow) · [LIB1 Librarian](https://github.com/tbhrc/skills/tree/main/ecosystem-librarian) · [Document Strategy](https://github.com/tbhrc/skills/blob/main/governance/strategies/strategy-cold-start-context-reduction.md) · [Founder Output](https://github.com/tbhrc/skills/blob/main/github-agent-workflow/SKILL.md#founder-facing-output) · [Anti-Friction Security](https://github.com/tbhrc/skills/blob/main/governance/policies/real-boundary-security-and-friction.md) · [Sniper](https://github.com/tbhrc/skills/blob/main/human-ai-operations-map/references/ai-sniper-entry-map.md) · [Multi-Agent Orchestrator](https://github.com/tbhrc/skills/tree/main/github-multi-agent-orchestrator)

**Repository Fast Links:** [Opportunities](https://github.com/tbhrc/skills/tree/main/drf-opportunity-factory) · [BD](bd/README.md) · [Intelligence](https://github.com/tbhrc/skills/tree/main/automations-drf-intelligence) · [Portfolio](businesses/PORTFOLIO-V3.md) · [Vendor CRM selection](https://github.com/tbhrc/drf-main/issues/157) · [Research](https://github.com/tbhrc/research) · [Issues](https://github.com/tbhrc/drf-main/issues) · [Universal DB](https://github.com/tbhrc/db) · [DB Migration #5](https://github.com/tbhrc/db/issues/5) · [Central Marketing](https://github.com/tbhrc/marketing) · [Central Sales](https://github.com/tbhrc/sales)

## Route

- **Known owner + bounded task** → execute with the most-specific Skill/tool.
- **Owner unclear** → use Sniper once, then execute.
- **Prior cross-session/cross-agent context could materially change the work, you are about to ask the user to repeat material context, or established internal structure/ownership/policy/process is requested but its canonical source/path is unknown** → use [Hindsight Memory](https://github.com/tbhrc/skills/tree/main/hindsight-shared-memory-operator) for focused recall/canon discovery when available; for unknown canon, **search existing GitHub canon first** (Hindsight semantic discovery or direct GitHub search), then fetch/read current owner truth. **Do not reconstruct established canon from local fragments before this search.** Skip for self-contained, current-file-only or direct current-state work where the owner/path is already known.
- **Any task that will create, file, move, rename or supersede a durable document/output** → run [LIB1](https://github.com/tbhrc/skills/tree/main/ecosystem-librarian) first for canonical placement, semantic vocabulary and material inbound/outbound Fast Links; then hand execution to the owning Skill/workflow. LIB1 is not an approval gate.
- **Ordinary authorised work** → Level 0 Direct.
- **Department boundary** → DRF owns opportunity discovery, underwriting, ranking, benchmarking and proof. Marketing execution routes to `tbhrc/marketing`; sales pursuit/conversion routes to `tbhrc/sales`; neutral person/organisation/endpoints/shared relationship data route to [`tbhrc/db`](https://github.com/tbhrc/db). CRM/BD are domain views/workflows over DB rather than competing identity databases.
- **Creating/updating/reviewing a Skill** → use [Skill Builder](https://github.com/tbhrc/skills/tree/main/github-skill-builder) after LIB1 resolves placement/identity; it owns Skill lifecycle and loads Document Strategy/Policies conditionally.
- **Creating/materially restructuring non-Skill agent-consumed operational documentation** → after LIB1 resolves placement/semantics/links, use Workflow + [Document Strategy](https://github.com/tbhrc/skills/blob/main/governance/strategies/strategy-cold-start-context-reduction.md) only for substantive document architecture.
- **Genuine specialist/parallel need** → Multi-Agent Orchestrator only when one direct stream is insufficient.
- **Actual consequential boundary** → load only the exact relevant policy/control.

## Rules

- **DB before a new contact silo.** A prospect, client contact, candidate or partner may be the same real entity. Reuse the DB identity and keep DRF opportunity/underwriting state in DRF rather than creating another identity root.
- **Issue-backed by default.** A master controlling Issue backs every substantive or durable unit of work. Reuse the existing master controlling Issue when it materially helps continuity; create additional Issues only when continuation, handoff, audit/founder visibility, cross-agent work or material chat-only decisions make it useful, and link every such Issue back to the master controlling Issue. If no controlling Issue exists anywhere org-wide for the work, create a new master controlling Issue before proceeding. Do not open or update an Issue for `go`/`continue`/`retry`/`next`, or before every mutation when nothing material changed — continuation against an existing Issue needs no new Issue and no ceremony update. Metadata is never runtime permission, and issue-less substantive work is not permitted.
- **Founder scan speed.** Follow the [Workflow founder-facing output convention](https://github.com/tbhrc/skills/blob/main/github-agent-workflow/SKILL.md#founder-facing-output): keep status concise, and render material existing GitHub repositories, Issues, PRs, Skills, canonical files/documents and navigable folders as descriptive clickable links when stable URLs exist; use raw/code paths only for proposed/nonexistent paths, literal commands/identifiers, or when the raw path itself is under discussion.
- **Friction masquerading as security is prohibited.** Use purpose-fit authority sufficient for the intended function; do not narrow access or add credential/approval layers without a concrete current boundary.
- **Security and compliance controls must earn their place.** Do not narrow repository scope, permissions, runtime reach or tool access merely because “least privilege”, isolation, hardening, or a generic security/compliance convention suggests it. First prove the concrete current threat, obligation or boundary, the material gap in existing controls, and that the proposed restriction is the smallest effective control. Where that proof exists, implement the control; where it does not, retain authenticated purpose-fit authority sufficient for the intended function.
- Human approval is reserved for genuine consequential boundaries: root/super-admin authority changes, destructive/irreversible actions, spend, legal/compliance commitments, private-data disclosure or material external/client commitments.
- Reusable HOW belongs in canonical Skills; load only what the task needs.
- Preserve unrelated newer work and avoid concurrent mutation collisions where they are real.
- Never expose secrets or unnecessary private/client data.
- Verify the requested outcome once, record continuity only when useful, then stop.

**`main` keeps progress. Universal DB keeps identity neutral. DRF owns opportunity judgement. KISSS keeps speed.**
