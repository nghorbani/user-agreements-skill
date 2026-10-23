---
title: "B2B SaaS for manufacturers: annotations"
description: The applicability table, clause-by-clause legal basis and checklist results behind the drafts.
---

*Fictional product, illustrative draft. Not legal advice.*

# Annotations

Law as of: 20 October 2026. These annotations accompany drafts for a lawyer to review; they are not
legal advice.

## Applicability table

| Instrument | Applies? | Deciding provision | Note |
|---|---|---|---|
| EU Consumer Rights Directive 2011/83/EU | Does not apply | Art. 2(1) CRD defines "consumer" as a natural person acting outside their trade, business, craft or profession; every Example Machines customer signs through its purchasing department acting for its employer | No withdrawal right, no CRD order-button information duty, no auto-renewal consumer disclosures |
| EU Unfair Contract Terms Directive 93/13/EEC | Does not apply | Art. 2(b), (c) UCTD: protects only a consumer against a seller or supplier | German AGB content control (§ 307 BGB) still applies independently - see below |
| EU e-Commerce Directive 2000/31/EC | Applies (narrowed) | Art. 10(1), (2), 11(1), (2): fall away only where both parties agree otherwise and neither is a consumer | Kept in the drafts since no such agreement is stated; storable-terms and deemed-receipt rules (Art. 10(4), 11(3)) apply regardless |
| EU P2B Regulation 2019/1150 | Does not apply | Art. 1(2): reaches a provider of online intermediation services connecting business users to consumers | Example Machines sells Spindlewise directly to manufacturers for their own internal use; it is not an intermediation service, and customers do not use it to offer goods/services to consumers |
| EU Data Act 2023/2854, Chapter II (connected product/related service) | Applies | Art. 2(5), (6), (12): Spindlewise is a related service to the customer's connected machines; "user" reaches a business | Pre-contract disclosures, default access, third-party sharing duties all apply (Section 7 of the subscription terms) |
| EU Data Act, Art. 13 B2B unfair-terms test | Applies | Reaches any unilaterally imposed data-related term between enterprises | Checked against the liability and change clauses; see checklist below |
| EU Data Act, Chapter VI (cloud switching) | Undetermined | Art. 23-30 bind a "data processing service" provider, source side only | Open point: whether Spindlewise itself, or only Example Machines' own upstream cloud provider, is in scope - see open-points.md |
| GDPR (processor/controller rules) | Applies | Example Machines processes Account Data on customer instructions (processor) and some data for its own purposes (controller) | DPA covers the processor role; Section 8 of subscription terms covers the controller slice |
| GDPR Chapter V (international transfers) | Applies | The US ticketing vendor sees support ticket content | Transfer mechanism (DPF adequacy or SCCs) is an open point pending vendor confirmation |
| German BGB §§ 312 to 312m (consumer distance-selling) | Does not apply | § 13, § 14 BGB: counterparty is always an Unternehmer | No cancellation button (§ 312k), no order-button wording duty (§ 312j) |
| German BGB §§ 305 to 310 (AGB control) | Applies, narrowed | § 310 Abs. 1 BGB: against a business counterparty, §§ 308, 309 fall away; § 307 Abs. 1, 2 still applies | Checked clause by clause below; no named financial-sector or großer-Unternehmer carve-out assumed to apply (open point) |
| German DDG (Impressum) | Applies | § 5 Abs. 1 DDG: standing duty for any commercial digital-service provider, regardless of B2B/B2C | Not drafted here - the client did not ask for an Impressum and none was in scope of this request; flagged as a gap if Example Machines' website needs one and does not already have it |
| German VSBG (consumer dispute-resolution notice) | Does not apply | § 36 VSBG reads toward consumers; no consumer contracts are concluded | No VSBG notice included |
| US ROSCA / Negative Option Rule | Does not apply | 15 U.S.C. § 8403 and Part 425 govern consumer-facing negative-option and prenotification plans | No consumer transactions |
| California Automatic Renewal Law | Does not apply | Cal. Bus. & Prof. Code § 17601(a) applies to a "consumer" auto-renewal; Spindlewise customers are businesses | |
| New York GBL 527-a | N/A - not a target market | Not named as a market in the facts | No NY-specific drafting included |
| California CCPA | Undetermined | Threshold test (revenue, volume, revenue share) under Cal. Civ. Code 1798.140(d) not yet confirmed; no employment-context exclusion from "consumer" the way Virginia/Texas have | DPA includes a conditional CCPA service-provider section; open point |
| California CalOPPA | Likely does not apply directly to Example Machines' own site unless Example Machines itself meets the "operator" definition and collects PII from CA residents online in a consumer-facing way | § 22577(c) | Not drafted; low relevance to a B2B backend |
| Texas TDPSA | Applies | No revenue/volume threshold; applies unless Example Machines is an SBA small business | DPA includes Texas processor-contract terms unconditionally, with the small-business consent duty for sensitive-data sale carved out separately (not expected to apply - no sale of data) |
| Ohio privacy law | Not covered - no comprehensive statute exists | `references/us-states/state-matrix.md` lists no Ohio row | Federal baseline (FTC Act, CAN-SPAM) only |
| US federal FTC Act / dark patterns | Applies as general baseline | Always-applicable floor | Reflected in plain-language drafting; no specific clause needed given no consumer-facing dark-pattern risk in a B2B sign-up flow |
| EU AI Act | Does not apply | No AI feature in Spindlewise per the facts given ("No AI features") | No AI-features clause included |
| EU DSA / Section 230 (platform/UGC rules) | Does not apply | No hosting of third-party content, no user-generated content beyond support tickets (which are not "content" the Platform disseminates to others) | No moderation, notice-and-action or UGC licence clauses included |
| EU Product Liability Directive 2024/2853 | Applies (narrow) | Art. 6(1): reaches an injured natural person from a defective product; Spindlewise is software | Floor stated in Section 11 of the subscription terms; open point on whether the product (software placed on the market) is "placed on the market" before or after 9 December 2026 |

## Clause-by-clause legal basis (master-subscription-terms.md)

| Section | Legal basis | Purpose |
|---|---|---|
| 2 Formation | `references/eu/ecd.md` Art. 10(1), (2), (4), 11(1) to (3) | Order/acknowledgment mechanics survive for a B2B contract absent a displacing agreement |
| 4 Price and payment | `references/clauses/price-and-payment.md`, EU business customers module | Consumer-specific fee caps dropped; ordinary commercial terms stated |
| 5 Term, renewal, cancellation | `references/clauses/term-renewal-and-cancellation.md`, EU business customers module; `references/de/bgb-agb.md` § 310 Abs. 1 BGB | No statutory term-length or notice-period floor for a B2B contract; § 307 fairness check still applies |
| 6 Changes to terms | `references/clauses/changes-to-terms.md`, EU business customers module; `references/de/bgb-agb.md` § 310 Abs. 1 BGB | UCTD/DCD change conditions dropped; notice-based, non-retroactive design kept voluntarily for § 307 fairness |
| 7 Machine Data / Data Act | `references/eu/data-act.md` Art. 3, 4, 5, 6, 7; `references/clauses/connected-product-data.md`, EU business customers module | Full Chapter II access/sharing duties, since "user" reaches a business |
| 8 Personal data | `references/eu/gdpr-processors-transfers.md`; `references/clauses/privacy-and-data.md`, EU business customers module | Controller/processor split for Account Data |
| 9 Data on termination | `references/eu/data-act.md` Art. 4; DPA Clause 10(d) | Parallel mechanics for Machine Data and Account Data |
| 10 Warranty | `references/clauses/warranty-and-conformity.md` (EU business customers module: consumer-specific elements dropped) | No statutory B2B SaaS warranty floor stated in the references; commercial drafting, open point for counsel |
| 11 Liability | `references/de/bgb-agb.md` § 309 Nr. 7, § 310 Abs. 1 (via § 307); `references/eu/pld.md` Art. 15, 16, 17 | Mandatory floor for death/personal injury/gross negligence preserved regardless of B2B status; PLD floor stated separately |
| 12 Acceptable use | `references/clauses/acceptable-use.md` | General good-practice clause, no specific statutory duty for this B2B context |
| 13 Confidentiality/IP | `references/clauses/intellectual-property.md`; `references/eu/software-directive.md` (not quoted verbatim since no software licence to an installed copy is granted - Spindlewise is accessed as a hosted service) | |
| 14 Indemnity | `references/clauses/indemnity.md`, EU business customers module; `references/de/bgb-agb.md` § 310 Abs. 1 | Outside UCTD; § 307 fairness check kept in mind via even-handed drafting |
| 15 Data Act cloud switching | `references/eu/data-act.md` Art. 23-30 | Open point, not drafted as a settled clause |
| 16 Governing law/jurisdiction | `references/eu/jurisdiction-and-law.md` Rome I Art. 3, 4; Brussels Ia Art. 25(1) | Consumer floors (Rome I Art. 6, Brussels Ia Art. 17/18) do not apply; exclusivity stated expressly per Art. 25(1) |
| 17 Dispute resolution | `references/clauses/dispute-resolution.md`, EU business customers module; `references/de/vsbg.md` (inapplicable) | No VSBG notice; no arbitration clause included by default (commercial choice) |
| 18 Notices/assignment/severability | `references/clauses/notices-and-communications.md`; `references/clauses/assignment.md`; `references/clauses/severability-and-entire-agreement.md` | Standard administrative clauses |

## Checklist results

### `references/checklists/eu-b2b.md`

Most of this checklist's content (platform terms, ranking transparency, ancillary-goods/parity,
internal complaint-handling system) is P2B-specific and **not applicable**: Example Machines is not a provider of
online intermediation services or a search engine (see applicability table). The items that do apply:

| Checklist item | Status | Evidence |
|---|---|---|
| Data Act: roles classified by actual function, not label | Met | Master Subscription Terms Section 7-8 and DPA scope note classify Example Machines as related-service provider/data holder for Machine Data and as processor/controller (split) for Account Data |
| Data Act: pre-contract disclosures for connected product/related service (Art. 3(2), 3(3)) | Partial | Drafted in Section 7 of the subscription terms, but the actual figures (volume, retention period) are bracketed pending product input - see implementation-requirements.md |
| Data Act: default access / third-party sharing (Art. 3(1), 4, 5) | Met | Section 7 |
| Data Act: trade-secret and security restriction mechanics (Art. 4, 5) | Met | Section 7, restriction paragraph |
| Data Act: gatekeeper exclusion (Art. 5(3)) | Met | Section 7, final paragraph |
| Data Act: B2B unfair-terms test (Art. 13(4), (5)) | Met | Section 11 (liability) avoids excluding liability for intent/gross negligence or giving Example Machines sole conformity-decision rights; Section 6 (changes) states a valid reason and advance notice for any price change, consistent with the Art. 13(5) second-subparagraph safe harbor |
| Processor contract (Art. 28(3), (4)) | Met | DPA Part A, full EU SCCs |
| Joint controller check | Met (negative finding) | No joint-controller relationship identified on the facts; Example Machines and Customer each act in their own distinct controller/processor roles |
| International transfers | Open point | DPA Clause 7.8 and Annex II flag the mechanism as pending vendor confirmation |
| Governing law/jurisdiction (Rome I, Brussels Ia) | Met | Section 16 of subscription terms |

### `references/de/bgb-agb.md` (German AGB checklist)

| Checklist item | Status | Evidence |
|---|---|---|
| Counterparty classified as Unternehmer, not Verbraucher | Met | Section 1 of subscription terms; open point on whether any customer is also a großer Unternehmer or named financial-sector business (does not change the analysis either way, since §§ 308/309 already fall away for an ordinary business) |
| §§ 308, 309 content control does not apply | Met (by classification) | § 310 Abs. 1 BGB |
| § 307 Abs. 1, 2 still applies | Met | Liability clause (Section 11) and change/renewal clauses (Sections 5, 6) drafted to stay even-handed and avoid an unreasonably disadvantageous design, in anticipation of § 307 review |
| § 309 Nr. 7 mandatory liability floor (no business carve-out from the underlying substance) | Met | Section 11, first paragraph |
| No deemed-consent change mechanism (BGH XI ZR 26/20) | Met | Section 6 is notice-based and prospective, not silence-based, even though the ruling's holding does not bind a B2B contract by its own terms |
| Impressum (DDG) | Not applicable to this deliverable | Not requested; flagged as a standing duty for Example Machines' website separately from these contract documents |
| VSBG notice | Not applicable | No consumer contracts |

### `references/checklists/subscription-auto-renewal.md`

Not applicable as a whole: every item on this checklist (CRD Art. 6/8/9-11a, CA ARL, NY GBL 527-a,
ROSCA/Negative Option Rule) is scoped to a consumer transaction, and Example Machines' customers are businesses
in every target market. No item from this checklist is drafted into the subscription terms; the
renewal and cancellation mechanics in Section 5 are accordingly ordinary commercial drafting, not a
compliance response to this checklist.

## Prescribed wording

None of the prescribed-wording items in `references/prescribed-wording.md` (PW-DE-1 through PW-DE-5,
PW-EU series, PW-US-FED series, PW-US-CA series) apply to these documents: every one of them is tied to
a consumer-facing mechanic (the German order button and cancellation button, the EU withdrawal
function, US warranty captions, California opt-out links) that this B2B relationship does not trigger.
