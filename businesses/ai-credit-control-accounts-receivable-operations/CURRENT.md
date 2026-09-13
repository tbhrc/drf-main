# AI Credit Control & Accounts Receivable Operations — Current State

**Status:** Active Candidate  
**Opportunity Score:** **89/100**  
**MRR:** **10/10**  
**AI Autonomy:** **88/100**  
**Evidence Confidence:** **95%**  
**Research Completeness:** **100%**  
**External Market Proof:** **EMP4 Established and transferable / 95%**  
**Best niche:** UAE B2B service/trading SMEs with 50–500 invoices/month, recurring overdue receivables and no dedicated credit-control team — **89/100 / 91% confidence**  
**RBS:** **85/100**  
**DRF Proof:** **P1 Desk Underwritten**  
**Stage:** **TEST**  
**Capital:** **US$0 now; up to Tier 1 only after founder approval if a paid proof requires bounded tooling**  
**Governing issue:** #186  
**Upstream research:** https://github.com/tbhrc/research/blob/main/research/business-models/ai-credit-control-accounts-receivable-operations-uae.md

## Business definition

> We sell an AI-assisted managed credit-control desk to UAE B2B SMEs for onboarding plus a recurring monthly fee because overdue invoices and inconsistent follow-up trap cash while many SMEs cannot justify a full-time credit controller. Revenue arrives as onboarding + recurring managed AR operations; legal recovery and specialist third-party collection are separately scoped.

This business starts **after an invoice exists**. It is not a duplicate of Revenue Recovery & Reactivation, whose core wedge is stale quotes, renewals and dormant pre-invoice/commercial pipeline.

## Layer 1 score

| Factor | Score |
|---|---:|
| Market Size Now | 9 |
| Market Growth | 8 |
| Timing / First-Mover Window | 8 |
| Willingness to Pay | 9 |
| AI Buildability | 9 |
| AI Marketability | 9 |
| AI Deliverability | 9 |
| Low Human Dependency | 8 |
| Startup Capital Efficiency | 10 |
| Speed to Revenue | 9 |
| Margin Potential | 9 |
| Scalability | 9 |
| Paid Growth Potential | 8 |
| Defensibility / Moat | 7 |
| MRR / Recurring Revenue Quality | 10 |

**Weighted score: 88.5 → 89/100.**  
AI Autonomy = average(9, 9, 9, 8) × 10 = **87.5 → 88/100**.

## External proof

- Atradius reports overdue invoices affecting **58% of UAE B2B sales** in its 2025 survey.
- Mashreq YallaCollect sells recurring AR automation at **AED276–816/month**.
- Steady UAE sells a hybrid automation + bilingual human-credit-control Professional tier at **AED1,799/month**.
- Chaser sells recurring receivables automation plus human-assisted `Care` tiers; current combined plans reach materially higher monthly price points.
- Upflow demonstrates current AI-agent collections/cash-application workflows around incumbent accounting/ERP systems.

This is sufficient for EMP4 because the commercial category is established globally and has strong direct UAE analogues. It does not prove DRF acquisition, collection uplift, human escalation load, margin or renewal.

## First offer — AI Credit Control Desk

Core recurring scope:

- ageing and priority worklist;
- approved email/SMS/WhatsApp reminders;
- bounded AI reply/dispute classification;
- bilingual human phone escalation where justified;
- promise-to-pay and dispute tracking;
- cash/DSO reporting;
- finance/accounting-team coordination;
- authorised legal/collection handoff outside normal credit control.

## Forward-test price

- **AED1,500 onboarding**;
- **AED1,750/month** up to roughly 200 invoices/month;
- **AED2,750/month** higher-volume tier up to roughly 500 invoices/month;
- legal recovery, complex disputes and specialist third-party collection separate.

These are estimates, not accepted-customer prices.

## GTM

Lead with the aged-receivables problem, not AI:

1. owner/CFO/finance-manager accounts with meaningful B2B credit sales;
2. accountant/bookkeeper partnerships;
3. a bounded ageing/collection diagnostic on a real ledger/export;
4. show missed follow-up, dispute backlog and cash at risk;
5. sell a 30-day managed operating cycle before expanding scope.

## Delivery architecture

```text
accounting / ERP AR ledger
→ ageing + client-approved policy
→ deterministic follow-up cadence
→ bounded AI prioritisation / reply-dispute classification
→ human bilingual escalation for selected accounts
→ promise / dispute / payment update
→ system-of-record sync / evidence
→ cash + DSO + contribution report
```

The client's accounting/ERP remains the system of record. Court/legal recovery is outside the first product and routes to authorised professionals/providers.

## RBS — 85/100

| Factor | Score | Basis |
|---|---:|---|
| Demand / market evidence | 9 | Independent UAE late-payment evidence + multiple paid operators. |
| Pain, willingness to pay and pricing | 9 | Direct UAE software and hybrid-managed prices. |
| Revenue quality / retention | 10 | Receivables follow-up recurs continuously for credit-selling businesses. |
| Unit economics / margin | 8 | Automation is favourable; human calls/disputes are the main cost gate. |
| Acquisition | 8 | CFO/founder/accountant routes are identifiable; live CAC unproven. |
| Delivery repeatability | 8 | Common AR workflows; data quality/disputes create exceptions. |
| Scalability / founder independence | 8 | Automation + pooled bilingual escalation can scale if exceptions stay bounded. |
| Capital efficiency / return | 10 | Existing accounting exports/APIs and messaging can test with no platform build. |
| Moat / defensibility | 6 | Raw reminder tech is commoditised; playbooks/data/outcome evidence can compound. |
| Risk / downside resilience | 7 | Low capital; relationship, data and legal-escalation risks are manageable with scope. |

## Return profile

No DRF revenue actual exists for this model.

Desk illustration only: 5 clients × AED1,750/month = **AED8,750 MRR** plus onboarding. The live economics depend primarily on human escalation/dispute minutes and acquisition cost rather than inference cost.

## Hard boundaries / counter-evidence

- low-cost software rejects a generic reminder-dashboard proposition;
- human phone chasing and disputes can make service labour nonlinear;
- client-approved tone/cadence is mandatory to protect customer relationships;
- do not provide unauthorised legal/debt-collection representation;
- sensitive financial/customer data requires governed handling;
- performance claims from vendors are not DRF base rates.

## Next Proof

**Two unrelated paid UAE B2B clients at or above AED1,500 onboarding + AED1,750/month**, each with a real ageing ledger and at least 50 overdue/open-credit invoices where practical.

Run one complete 30-day cycle and measure cash/ageing change, promises/disputes, automated versus human follow-up share, human minutes, channel/tool cost, complaints, gross contribution and renewal intent.

**Pass:** two unrelated paid clients, bounded human escalation, positive expected recurring contribution and credible renewal.  
**Recycle/Hold:** legal/dispute work or manual calls dominate delivery, or buyers only value low-cost software.
