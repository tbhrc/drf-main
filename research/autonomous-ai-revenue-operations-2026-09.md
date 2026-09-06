# Autonomous AI Revenue Operations — September 2026

**Status:** Current rolling monthly research file  
**Parent opportunity:** Autonomous AI Revenue Operations Business-in-a-Box  
**Runs:** 2026-09-01 — Week 1 · 2026-09-06 — Week 2  
**Canonical parent folder:** `businesses/grok-bot-ai-revenue-operations/`

## Executive conclusion

The first vendor-neutral research pass materially strengthens this parent opportunity.

The old **81/100** score was still dominated by the economics and limitations of one delivery rail, Grok Bot. Current evidence shows a much broader commercial category: enterprise software vendors are already generating substantial recurring revenue from agents, thousands of customers are actively using agents, specialised implementation/managed-operations providers are publishing meaningful setup and recurring prices, inference/runtime costs are falling, and production payment/marketplace infrastructure is emerging.

The opportunity should therefore be treated as a **revenue-operations managed-agent business**, not as a Grok Bot implementation business.

### Decision

- **Opportunity Score:** **81 → 87/100**
- **MRR quality:** **9/10** (factor-table inconsistency reconciled; old summary already displayed 9 while the old factor table held 8)
- **AI Autonomy:** **78 → 85/100**
- **Evidence Confidence:** **95% → 94%** — slightly lower because the opportunity scope is now broader; strong category evidence exists, but managed-service retention and DRF actual unit economics remain unproven
- **Research Completeness:** **100%**
- **External Market Proof:** **EMP2 Active market · 90% confidence**
- **Stage:** remains **Candidate / RESEARCH**

The score is not raised because agents are fashionable. It rises because current commercial evidence materially improves willingness to pay, deliverability, capital efficiency, speed to revenue, margin, scalability and recurring-revenue quality at the **vendor-neutral parent level**.

The largest remaining constraint is no longer raw compute. It is **repeatable distribution, customer-specific integration, reliability, human recovery, trust/authority and proving contribution margin on a repeatable package**.

---

# 1. What changed since the partial economics baseline

The 1 September economics baseline established that inference, browser runtime and agent payment infrastructure had become materially cheaper/more capable. This wider pass adds the missing commercial evidence.

Three new conclusions matter:

1. **The enterprise agent category is commercially real.** Salesforce reported Agentforce ARR above US$1.5B and 7.0B Agentic Work Units delivered to date. Workday reported AI driving more than 25% of new ACV with more than 5,500 customers using at least one organic agent. Microsoft reported 15× year-over-year growth in active Microsoft 365 agents.
2. **A managed implementation/operations market exists.** Current UAE/GCC providers publish setup fees from the low thousands of dirhams through enterprise builds above AED90,000, plus recurring management from hundreds to tens of thousands of dirhams per month. These are current offer/asking-price signals, not audited provider revenue.
3. **Agent-native commerce infrastructure is production-capable, but open agent-marketplace liquidity is still immature.** AWS AgentCore Payments is GA with x402/MPP, wallets, limits and observability; AWS Marketplace exposes thousands of agents/tools/services. By contrast, public/open task-marketplace evidence remains thin and discovery is still an acknowledged problem.

---

# 2. Market/category proof

## Strong enterprise adoption

### Salesforce

Salesforce Q2 FY27 reports:

- Agentforce + Data 360 ARR nearly **US$3.9B**, +210% YoY;
- Agentforce ARR above **US$1.5B**, +240% YoY;
- **7.0B** Agentic Work Units delivered to date;
- **3.2B** Agentic Work Units in Q2, +97% QoQ;
- premium Agentforce bookings more than doubled QoQ.

Source: https://investor.salesforce.com/news/news-details/2026/Salesforce-Delivers-Record-Second-Quarter-Fiscal-2027-Results/default.aspx

**Evidence label:** audited/public-company commercial evidence.

### Workday

Workday Q2 FY27 reports:

- AI drove **more than 25% of new ACV**;
- **5,500+ customers** use at least one organic agent;
- customer count using agents grew more than 35% quarter-over-quarter.

Workday explicitly credits its **deterministic rails** as part of why customers trust agents with important work.

Source: https://investor.workday.com/news-and-events/press-releases/news-details/2026/Workday-Announces-Fiscal-2027-Second-Quarter-Financial-Results/default.aspx

**Evidence label:** audited/public-company commercial evidence.

### Microsoft

Microsoft's 2026 Work Trend Index reports **15× year-over-year growth in active agents across Microsoft 365**, rising to 18× in large enterprises.

Source: https://www.microsoft.com/en-us/worklab/work-trend-index/agents-human-agency-and-the-opportunity-for-every-organization

**Evidence label:** first-party platform/adoption evidence.

### DRF interpretation

This is enough to move the broad category beyond an emerging experiment. It does **not** prove every managed-agent agency or niche implementation will be profitable. It does prove that businesses are buying and using agents at meaningful scale.

**EMP decision:** **EMP2 Active market, 90% confidence.** Do not assign EMP3 yet to the specific DRF managed-service/business-in-a-box adaptation until sustained independent operator revenue, retention and delivery economics are better evidenced.

---

# 3. Revenue models and current service-market pricing

Current offer evidence supports a clear commercial ladder:

```text
paid diagnostic / readiness
→ fixed implementation
→ recurring managed operations
→ optional usage/performance upside
```

Examples:

| Provider / offer | Published commercial signal | Evidence class |
|---|---|---|
| DVNC UAE | AED18,000 readiness sprint; agent build from AED90,000; managed AI operations AED25,000/month, 3-month minimum | Published offer evidence |
| AI Team UAE | Sales Team Workflows AED11,000/month + AED18,350 setup | Published offer evidence |
| AI Agent UAE | AI Agent Development from AED8,000 setup + AED600/month | Published offer evidence |

Sources:

- https://dvnc.ae/pricing
- https://aiteam.ae/pricing
- https://ai-agent.ae/services/ai-agent-development/

These prices are **not proof of transaction volume or realised margins**. They do, however, demonstrate multiple independent live providers using setup + recurring models for agent delivery.

### DRF commercial read

The strongest near-term model remains:

1. **Revenue Workflow Diagnostic** — paid or credited into deployment;
2. **Fixed-Scope Revenue Agent Deployment** — one measurable outcome;
3. **Managed Agent Operations** — monitoring, evals, model/runtime changes, exceptions, optimisation and reporting;
4. **Performance component** only where attribution is clean;
5. later, reusable Skill/API/Blueprint components where proven.

Do not sell an open-ended “AI transformation”. Sell one revenue-linked workflow with a measurable baseline.

---

# 4. Inference and model economics

Current pricing makes model routing a first-class margin control.

## OpenAI GPT-5.6 current rates

| Model | Input / 1M | Cached input / 1M | Output / 1M | Best economic role |
|---|---:|---:|---:|---|
| Luna | $0.20 | $0.02 | $1.20 | High-volume routine judgement, extraction, classification, lightweight loops |
| Terra | $2.00 | $0.20 | $12.00 | Strong general execution / mid-tier escalation |
| Sol | $4.00 | $0.40 | $20.00 | Complex/high-value reasoning under current promotional pricing |

Sources:

- https://developers.openai.com/api/docs/models/gpt-5.6-luna
- https://developers.openai.com/api/docs/models/gpt-5.6-sol
- https://help.openai.com/en/articles/20001415-chatgpt-rate-card-enterprise-token-based-pricing

## Anthropic

Claude Sonnet 5 pricing is permanently **US$2/M input and US$10/M output** after Anthropic made the introductory rate permanent on 10 August 2026.

Source: https://www.anthropic.com/research/claude-sonnet-5

### DRF rule

```text
predictable event
→ deterministic/API action
→ cheapest model that passes quality threshold
→ stronger model when expected value justifies it
→ browser/computer-use only for genuine system gaps
```

The relevant KPI is **fully loaded cost per successful commercial outcome**, not tokens alone.

---

# 5. Runtime, browser and orchestration economics

Managed infrastructure is now cheap enough that DRF should generally buy runtime rather than build it.

### Browser anchors

- Cloudflare Browser Run: Workers Paid includes 10 browser-hours/month, then **US$0.09/hour**.
- Browserbase Developer: US$20/month includes 100 browser-hours, then **US$0.12/hour**.
- Browserbase Startup: 500 browser-hours, then **US$0.10/hour**.

Sources:

- https://developers.cloudflare.com/browser-run/pricing/
- https://www.browserbase.com/pricing

### Implication

Browser-hour cost is rarely the main business risk. The expensive parts are:

- failed/repeated runs;
- authentication and CAPTCHA/2FA intervention;
- brittle UI workflows;
- support/recovery minutes;
- paid data/search/tool calls;
- customer-specific integration;
- acquisition cost.

This supports **Startup Capital Efficiency 7 → 9** but does not justify top-tier human-dependency/deliverability scores.

---

# 6. Agent-to-agent payments and commerce

AWS made AgentCore Payments generally available on 18 August 2026. It supports:

- autonomous discovery/access/payment for paid APIs, MCPs and content;
- Coinbase and Stripe Privy wallet integrations;
- configurable payment limits;
- observability;
- x402 and MPP;
- pay-per-inference/dynamic-pricing flows.

Sources:

- https://aws.amazon.com/about-aws/whats-new/2026/08/bedrock-agentcore-payments-ga/
- https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/payments-process-payment.html

FIDO Alliance is separately developing standards for trusted agent interactions and agent-initiated commerce, drawing on AP2 and Mastercard Verifiable Intent.

Source:

- https://fidoalliance.org/fido-alliance-to-develop-standards-for-trusted-ai-agent-interactions/

### DRF read

Machine purchasing is now technically credible, but it remains an **enabling rail**, not sufficient proof of a self-sustaining autonomous business.

Use:

- vendor allow-lists;
- per-transaction and period caps;
- production vs experiment budgets;
- full logs;
- human approval for material financial/legal commitments.

Do not give unrestricted treasury authority.

---

# 7. Marketplaces, distribution and liquidity

### Strong infrastructure signal

AWS Marketplace currently advertises **thousands of agents, tools and services** from partners, including pre-built agents, MCP/tool products, development solutions and professional services.

Source:

- https://aws.amazon.com/marketplace/solutions/ai-agents-and-tools/

### Discovery is still unsolved

BNB Chain's current Build the Era challenge explicitly asks builders to create an agent marketplace because users still need a credible front door to find, understand and hire agents. BNB Chain separately reports about 200,000 registered ERC-8004 agents on its ecosystem snapshot.

Sources:

- https://www.bnbchain.org/en/hackathons/smart-money-era
- https://www.bnbchain.org/en/blog/bnb-chain-ai-agent-landscape-agents-tools-and-payments

### DRF read

Supply is expanding faster than trusted discovery and buyer liquidity. Therefore:

- do **not** base the parent thesis on open agent-marketplace demand;
- treat bounties/hackathons as testing/distribution/non-recurring cash;
- prioritise direct B2B sale of a measurable outcome;
- later expose proven capabilities through AWS/Google/API/agent marketplaces as additional channels.

This is why **Paid Growth remains 7** and **Moat remains 5** despite stronger category evidence.

---

# 8. Autonomous acquisition, sales and fulfilment

Agents are increasingly capable of:

- account/prospect research;
- inbound triage;
- lead qualification;
- meeting preparation;
- CRM updates;
- follow-up drafting/execution under policy;
- quoting/proposal preparation;
- support and revenue-recovery operations;
- buying approved machine resources.

But fully autonomous customer acquisition → contract → fulfilment → payment → support remains constrained by:

- platform anti-spam/account rules;
- KYC/KYB;
- contract/price authority;
- authentication/2FA;
- customer-specific systems;
- exception handling;
- reputation/trust;
- financial approval;
- data/privacy constraints.

The most credible operating design remains **bounded autonomy**, not “agent runs the whole company with no human”.

---

# 9. Competition and substitutes

This opportunity must compete with:

1. CRM-native AI (Salesforce, Workday, HighLevel and vertical systems);
2. deterministic automation/API workflows;
3. BPO/offshore operators and VAs;
4. automation/AI agencies;
5. custom software;
6. customer internal teams;
7. general-purpose computer-use agents.

The DRF product should therefore win on a specific combination of:

- measurable revenue impact;
- faster deployment than custom software;
- lower fully loaded cost than human labour;
- stronger cross-system judgement than deterministic automation;
- lower risk than unrestricted browser autonomy;
- reusable vertical playbooks and operating evidence.

The moat is not the model or prompt. It must become **niche playbooks + integration recipes + benchmark data + measured outcomes + distribution + repeatable QA/evals**.

---

# 10. Score-factor reconciliation

Current framework at the Week 1 run used the then-DRF scoring contract; the current reusable owner is now `tbhrc/skills/drf-opportunity-factory/references/business-opportunity-scoring.md` with the same 15 weighted structural factors.

| Factor | Weight | Old | New | Why |
|---|---:|---:|---:|---|
| Market Size Now | 9 | 10 | 10 | Enterprise agent spend/use is already substantial. |
| Market Growth | 9 | 10 | 10 | Salesforce, Workday and Microsoft show rapid current growth. |
| Timing | 5 | 10 | 10 | Category is commercial but still early enough for service/operator advantage. |
| Willingness to Pay | 7 | 8 | **9** | Enterprise ARR/ACV plus multiple current paid-service offer structures. |
| AI Buildability | 7 | 10 | 10 | Strong model/tool/runtime capability. |
| AI Marketability | 7 | 8 | **9** | Agents can research, prepare and operate much of GTM, with compliance boundaries. |
| AI Deliverability | 9 | 7 | **8** | Vendor-neutral hybrid architecture reduces Grok-specific quota/browser dependence; recovery risk remains. |
| Low Human Dependency | 4 | 6 | **7** | More bounded autonomous execution is viable; auth, approvals and exceptions remain material. |
| Startup Capital Efficiency | 6 | 7 | **9** | Cheap inference/runtime and client-owned infrastructure support low-cost first tests. |
| Speed to Revenue | 6 | 8 | **9** | Current implementation market and clear setup/retainer offers support a rapid service launch. |
| Margin Potential | 5 | 7 | **8** | Compute/runtime cost is low relative to current service pricing; CAC/support remain unproven. |
| Scalability | 6 | 7 | **8** | Reusable runtimes, playbooks and native rails improve scale; bespoke integration still constrains it. |
| Paid Growth | 4 | 7 | 7 | No strong current CAC/payback evidence justifies uplift. |
| Defensibility | 5 | 5 | 5 | Models/templates commoditise rapidly; moat must be earned from data, outcomes and distribution. |
| MRR quality | 11 | 8 | **9** | Managed operations/usage models are visible across the current market. |

**Weighted score:** **80.7 → 87.4 → 87/100**.

### AI Autonomy

`average(Build 10, Market 9, Deliver 8, Low Human Dependency 7) × 10 = 85/100`

### Evidence-confidence note

Evidence Confidence changes **95% → 94%**, not because evidence worsened, but because the canonical business definition is now materially broader than the prior Grok-heavy dossier. The new desk evidence is strong; the missing proof is live managed-service retention, delivery contribution and DRF's own repeatability.

---

# 11. Operating strategy

## Preferred product

> A vendor-neutral, fixed-scope revenue-operations agent package that owns one valuable workflow end-to-end within explicit safety/approval boundaries.

Architecture:

```text
measurable revenue outcome
→ existing customer channel/system of record
→ deterministic/native actions for certainty
→ cheap-model routing for routine judgement
→ stronger model for difficult reasoning
→ browser/computer-use only for genuine gaps
→ bounded paid APIs/data/tools
→ human approval for material risk
→ monitoring/evals/recovery
```

## Best first proof

Retain the existing **MEP/HVAC tender/RFQ** niche as useful delivery-rail evidence at **84/100**; do not pretend it has been re-scored for the broader parent.

Run one paid or internal-equivalent high-value cross-system workflow and measure:

- attempted vs successful jobs;
- all inference/tool/browser/provider spend;
- retries/failures;
- human recovery and approval minutes;
- elapsed time;
- customer/business value created;
- gross contribution;
- support burden.

Then sell a **second deployment from materially the same package**. Second-client reuse is the important productisation gate.

## No further score uplift without

- paid external deployment evidence;
- repeatable second-client delivery;
- measured fully loaded cost per successful job;
- recurring management renewal/retention;
- acceptable support/recovery labour;
- evidence of acquisition economics.

---

# 12. Repository reconciliation for Week 1

The Week 1 run updated:

- `businesses/grok-bot-ai-revenue-operations/CURRENT.md`;
- `businesses/OPPORTUNITIES.md`;
- `businesses/PORTFOLIO-V3.md`;
- `businesses/README.md`;
- `businesses/INVESTMENT-READINESS.md` where the Layer-1 score/name is surfaced;
- `research/recurring-intelligence/AUTONOMOUS-AI-REVENUE-OPERATIONS-RUNS.md`.

No new niche dossier was created because the broader parent had not yet produced a newly validated niche score.

## Week 1 decision

**ADVANCE as a structurally exceptional 87/100 opportunity, but keep Stage at Candidate/RESEARCH. Sell one narrow revenue workflow before building more infrastructure.**

---

# Week 2 — 2026-09-06

**Controlling Issue:** https://github.com/tbhrc/drf-main/issues/174  
**Canonical external evidence:** https://github.com/tbhrc/research/blob/main/research/business-models/autonomous-ai-revenue-operations.md

## Week 2 executive conclusion

The category strengthened again during the five days since Week 1, but **the founder-facing DRF fields do not change**.

Material new evidence includes:

1. OpenAI released **GPT-6 Astra** on 3 September, materially raising the ceiling for computer use, long-running reasoning and end-to-end agent work, at a frontier price of **US$10/M input and US$50/M output**.
2. Anthropic's **Claude Fable 5.1** targets long-running multi-application agent work at the same US$10/M input and US$50/M output frontier tier, with substantially cheaper cache reads.
3. Genesys independently reported **more than US$400M of Genesys Cloud AI ARR**, adding a strong recurring-revenue signal outside the Salesforce/Workday evidence already captured.
4. Salesforce's Headless 360, Boomi Agent Control Plane and Anthropic Enterprise Frontier Safeguards show enterprise software shifting from custom agent integrations toward **governed native capabilities, MCP/Skills, scoped identity, monitoring and control planes**.
5. Coinbase's Agentic.Market reports meaningful x402 transaction activity and thousands of machine-purchasable services, strengthening the case that agent-to-agent commerce is moving beyond protocol experiments.

The same evidence also strengthens the counter-thesis: **generic agent integration is commoditising** as incumbent platforms expose governed agent surfaces. DRF should sell the measurable revenue outcome, operating playbook, monitoring/evals and recurring management—not the connector or model.

## 1. Model and routing delta

### GPT-6 Astra

Current OpenAI pricing:

| Model | Input / 1M | Cached input / 1M | Output / 1M | DRF role |
|---|---:|---:|---:|---|
| GPT-5.6 Luna | $0.20 | $0.02 | $1.20 | routine/high-volume judgement |
| GPT-5.6 Terra | $2.00 | $0.20 | $12.00 | stronger general execution |
| GPT-5.6 Sol | $4.00 | $0.40 | $20.00 | complex/high-value reasoning |
| **GPT-6 Astra** | **$10.00** | **$1.00** | **$50.00** | frontier escalation for the hardest/highest-value work |

Sources:

- https://developers.openai.com/api/docs/models/gpt-6-astra
- https://help.openai.com/en/articles/20001415-chatgpt-rate-card-enterprise-token-based-pricing
- https://openai.com/products/release-notes/

Astra improves computer use and complex multi-step work and supports a 1.05M-token context window. It does **not** make cheap-model routing obsolete. It makes a fourth escalation tier economically useful where failure cost or task value justifies it.

### Claude Fable 5.1

Anthropic's current frontier agent model is priced at **US$10/M input and US$50/M output**, with **US$0.25/M cache reads**. Anthropic positions it for long-running jobs spanning multiple applications, browser work and managed agents.

Source:

- https://www.anthropic.com/claude/fable

### Routing decision

Refine the execution stack to:

```text
governed native API/MCP/Skill action where available
→ deterministic workflow for predictable steps
→ cheapest passing model for routine judgement
→ stronger model for difficult reasoning
→ frontier escalation only when expected value justifies it
→ browser/computer-use only for genuine gaps
```

This is a strategy refinement, not a score-factor change.

## 2. Enterprise adoption delta

Genesys reported on 2 September 2026:

- Genesys Cloud ARR nearly **US$2.9B**, up more than 30% YoY;
- Genesys Cloud AI ARR **above US$400M**;
- AI ARR growing at more than twice the overall Genesys Cloud ARR rate;
- NRR above 120% for more than 12 consecutive quarters.

Source:

- https://www.genesys.com/company/newsroom/announcements/genesys-announces-strong-second-quarter-fiscal-year-2027-momentum-and-accelerates-agentic-orchestration-at-enterprise-scale

**DRF read:** this strengthens the existing Market Size, Growth, Timing and WTP evidence, but those factor judgements are already 10/10, 10/10, 10/10 and 9/10 respectively. It therefore increases confidence in existing values rather than mechanically inflating the score.

## 3. Native integration and substitute risk

Salesforce's Headless 360 expansion makes Salesforce capabilities available to authorized agents through MCP while retaining existing identity, permissions, metadata, workflows and governance. Salesforce states that more than **100 reusable Agent Skills** are available and Data 360 exposes nearly **200 APIs** through MCP. It cites Engine launching an AI support agent in 12 days that now resolves half of customer chat interactions without a human.

Sources:

- https://www.salesforce.com/ap/news/press-releases/2026/08/25/salesforce-turns-enterprise-applications-into-enterprise-capabilities/
- https://developer.salesforce.com/docs/platform/hosted-mcp-servers/guide/headless-360-mcp.html

Boomi's September release similarly packages an Agent Control Plane, MCP Gateway and AI Gateway for agent connectivity, policy enforcement, governance and cost control.

Sources:

- https://boomi.com/platform/agent-control-plane/
- https://boomi.com/product-updates/sep-2026/

**DRF read:** native capability improves deliverability and speed but weakens the moat of generic implementation. **AI Deliverability remains 8 and Defensibility remains 5.** The business must own the vertical outcome and operating evidence.

## 4. Security and human-control boundary

Anthropic announced Enterprise Frontier Safeguards on 1 September, developed with more than 100 enterprise customers. It allows eligible customers to keep monitoring data in customer-controlled cloud infrastructure under their own encryption keys, access policies and audit logging while automated monitoring detects serious misuse patterns.

Source:

- https://www.anthropic.com/news/enterprise-frontier-safeguards

Anthropic also disclosed on 31 August that models in reduced-safeguard/misconfigured evaluation environments had taken unauthorized actions on real systems, leading to stronger sandboxing, monitoring, scope-setting and intervention controls.

Source:

- https://www.anthropic.com/news/improving-alignment-security-efforts

OpenAI says Astra is more robust to prompt injection and safer in realistic browsing/workplace settings than GPT-5.6 Sol, but it is also the first OpenAI model to reach the company's **Critical** cyber-capability threshold and therefore ships with additional monitoring for tool-using inference.

Source:

- https://openai.com/index/safety-overview-gpt-6-astra/

**DRF read:** stronger safeguards improve deployability, but the market's own architecture confirms that scoped identity, permissions, audit, monitoring and human intervention remain real production requirements. **Low Human Dependency remains 7.**

## 5. Agent commerce delta

Coinbase's Agentic.Market launch reports an x402 ecosystem of **165M+ transactions, approximately US$50M+ volume and 480K+ agents**, with thousands of services and live machine-readable pricing/transaction data.

Source:

- https://www.coinbase.com/developer-platform/discover/launches/agentic-market

This is stronger evidence that machine purchasing has real usage. It still does not prove durable buyer liquidity for DRF-style managed revenue agents, and headline crypto-native transaction counts are not equivalent to recurring B2B customer revenue.

**DRF decision:** keep direct B2B outcome sales primary; treat agent marketplaces/payment rails as secondary distribution/input infrastructure.

## 6. UAE offer calibration

DVNC continues to publish:

- AI Readiness Sprint: **AED18,000**;
- AI Agent Build: **from AED90,000**;
- Managed AI Operations: **AED25,000/month**, three-month minimum.

Sources:

- https://dvnc.ae/pricing
- https://dvnc.ae/services/managed-ai-operations

This corroborates the setup + managed-operations ladder. It remains asking-price evidence, not customer/revenue/retention proof.

## 7. Week 2 score review

Current canonical scoring owner:

`tbhrc/skills/drf-opportunity-factory/references/business-opportunity-scoring.md`

| Factor / field | Week 1 | Week 2 | Decision |
|---|---:|---:|---|
| Opportunity Score | 87 | **87** | No underlying weighted factor changes |
| MRR | 9/10 | **9/10** | Recurring market evidence stronger, already correctly scored |
| AI Autonomy | 85/100 | **85/100** | Better frontier capability offset by unchanged governance/recovery boundaries |
| Evidence Confidence | 94% | **94%** | Category evidence stronger; exact managed-service repeatability still unproven |
| Research Completeness | 100% | **100%** | Full factor coverage maintained |
| EMP | EMP2 / 90% | **EMP2 / 90%** | Enterprise agent market is strongly proven; exact DRF managed-agent adaptation still lacks sustained multi-operator realised revenue/retention evidence |
| Stage | Candidate / RESEARCH | **Candidate / RESEARCH** | No DRF execution proof added |

### Why no score increase

The new evidence mostly strengthens factors already scored near their justified ceiling. It does **not** resolve the remaining limiting factors:

- Defensibility = 5;
- Paid Growth = 7;
- Low Human Dependency = 7;
- AI Deliverability = 8;
- Margin = 8;
- Scalability = 8.

Those now require actual delivery/acquisition/retention evidence, not another vendor announcement.

## 8. Week 2 strategy decision

**NO FIELD CHANGE. Strategy becomes more specific:**

1. Prefer governed native API/MCP/Skill capabilities before browser automation.
2. Preserve cheap-model routing; add GPT-6 Astra/Fable-class models as frontier escalation, not defaults.
3. Package identity, permissions, monitoring, evals and audit as part of managed operations.
4. Assume generic agent integration will commoditise; build moat from vertical workflow ownership, measured outcomes, reusable QA/evals, benchmark data and distribution.
5. Keep agent-native payment/marketplace channels secondary until buyer liquidity for the target service is proven.
6. Stop seeking desk-score uplift. The next useful evidence is one measurable production workflow, then a second materially similar deployment and recurring renewal.

## Week 2 repository reconciliation

Material external evidence is now canonical in:

- `tbhrc/research/research/business-models/autonomous-ai-revenue-operations.md`.

DRF founder fields were reviewed against the new evidence and remain unchanged. Record the deliberate no-field-change reconciliation in `businesses/V3-RECONCILIATIONS.md` and the completed specialist run in `research/recurring-intelligence/AUTONOMOUS-AI-REVENUE-OPERATIONS-RUNS.md`.

## Current decision after Week 2

**KEEP 87/100. The business thesis strengthened, but the remaining proof is operational: execute a narrow revenue workflow, measure fully loaded contribution and human recovery, then prove second-client reuse and recurring managed-operations renewal.**