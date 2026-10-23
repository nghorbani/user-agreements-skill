---
name: user-agreements
description: Draft user agreements for software, apps, SaaS and connected products sold in the EU and the US. Covers terms of service, EULAs, subscription and auto-renewal terms, privacy and cookie notices, acceptable use policies, B2B data processing agreements, and the EU consumer add-ons (withdrawal information with the model form, the German Impressum). Use when asked to write, review or adapt such a document, or to check a checkout, renewal or cancellation flow against consumer law in Germany, the EU, California, New York or other US states. The output is a set of drafts for a lawyer to review, with annotations, open points and the date of the law used. It is not legal advice.
license: Apache-2.0
metadata:
  version: "0.1.0"
  law-as-of: "2026-10-20"
---

# User agreements

Drafts for counsel, not legal advice. The references state the law as of 20 October 2026. Say both things in the first answer of a session.

## Scope

- EU directives and regulations, with Germany as the reference member state. For other EU member states, draft at directive level and list the national rules to verify as open points.
- US federal law, California and New York in full. Other US states through `references/us-states/state-matrix.md`, as flags to check.
- Out of scope: UK law, sector regimes (health, financial services, payment card rules), employment, tax and export control. If a request needs one of these, say so for that part and continue with the rest.

## Workflow

### 1. Intake

Before drafting, ask in one message for what you do not know yet:

1. Seller: legal entity, seat, postal and email contact; consumers, business customers or both.
2. Product: web service, app, desktop software, firmware on a device, or a platform hosting user content; how it is delivered and updated.
3. Markets: countries and US states sold to, user or household counts per state where privacy laws have thresholds, annual revenue.
4. Money: one-off price, subscription, free trial, freemium or in-app purchases; renewal and price change plans.
5. Personal data: categories, health-related or other sensitive data, children or teenagers in the audience, controller or processor role, data leaving the EU.
6. Cookies, SDKs, analytics and advertising tools.
7. AI features that users see or that decide about them.
8. User content and moderation; whether the service is an online platform or a marketplace.
9. Open source components and third-party licences that ship with the product.
10. Warranty, support and update promises; any hardware.
11. Existing documents and the current checkout, renewal and cancellation flows.
12. Who reviews the drafts, and by when.

If two answers contradict each other, point it out and ask before you go on.

If the user wants drafts in the same turn, open the reply with the missing facts as numbered questions, then draft on assumptions you state, and mark in the open points what each answer would change.

### 2. Applicability

For every instrument in the references, decide whether it applies, does not apply, or is undetermined. For an undetermined instrument, name the missing fact and the question that settles it. Do not draft the clauses that depend on it; put them in the open points. Keep the result as a table in the annotations.

- Name the provision that decides each classification in the table: consumer or business, goods with digital elements or digital content, connected product and its user, hosting service or online platform, controller or processor.
- Decide the controller or processor role per category of personal data, not once per contract.
- Every market the user names gets a line: covered by a reference file, or an open point saying the references do not cover it.
- Decide a threshold, and any other factual test (who mainly uses the service, whether data is sold or shared), only from facts the user gave. Read the law's own test and its own consumer definition (several state laws leave out people acting in a business or employment context, and a count limb may turn on data bought, sold or shared rather than on users). Never estimate a threshold from unit sales, user totals, market size or population shares; an unknown threshold leaves the instrument undetermined, and nothing that depends on it is drafted as settled.
- An instrument that does not apply gets its line in the table and nothing in the drafts or the implementation register: no defensive clauses or product controls added to be safe.

### 3. Document set

Pick the documents the applicable law requires and the product needs. A typical EU consumer subscription needs terms of service with subscription terms, withdrawal information with the model withdrawal form, a privacy notice, a cookie notice and, for Germany, an Impressum. A typical US set is terms of service, subscription terms with the state renewal disclosures, and a privacy notice with state supplements. Each contract type gets its own withdrawal information: a one-off sale of goods uses the goods variant of the model (period from receipt of the goods), a subscription or digital service the services variant (period from conclusion). Business buyers get a separate track without the consumer-only rules.

### 4. Draft

Start from `templates/` and the clause rules in the references. Write one common core with marked modules for EU consumers, EU business customers and the US when one text can serve all of them. Split into separate versions when `references/conflicts.md` says two modules cannot live in one text. Use plain language and short sentences, and use defined terms the same way throughout. Keep legal citations and drafting notes out of the agreement text.

### 5. Conflict check

Check every draft against `references/conflicts.md` and every checklist that fits the deal: the one for its document type, `eu-b2c` or `eu-b2b`, `de-agb` for Germany, and `us-consumer` for US consumers. Common failures: arbitration or class action waivers applied to EU consumers, unlimited disclaimers, change clauses without notice and a right to leave, a choice of law that strips consumer protection, missing withdrawal information, and renewal flows without the required notices.

Record the result in `annotations.md` as a checklist table: one row per item of every checklist that fits the deal, marked met (with the clause or requirement that meets it), not applicable (with the reason), or open point. Fix a draft before hand-over wherever an item is neither met nor an open point.

Then go through every button and control the flows need (order submission, cancellation, its confirmation, the withdrawal function, its confirmation) and check each one against its entry in `references/prescribed-wording.md`.

### 6. Hand-over

Deliver:

- the drafts;
- `annotations.md`: for each clause, its legal basis (article or section) and its purpose, plus the applicability table and the checklist table;
- `open-points.md`: undetermined facts, national law to verify, rules that take effect later, and the decisions counsel has to make;
- `implementation-requirements.md`: the product behaviour the documents assume (order button label, cancellation path, withdrawal function, consent banner, notices and reminders, records to keep), with owner and evidence columns;
- the law-as-of date, and the reminder that a qualified lawyer has to review the drafts.

## Rules

- Quote prescribed wording (button labels, model forms, statutory notices) exactly as it appears in `references/prescribed-wording.md`. Never paraphrase it, and never translate it yourself.
- Every legal statement in the annotations comes from a reference file and carries its citation. Where the references are silent, say so in the open points instead of filling the gap from memory.
- Name a court case, a docket number, a hearing date or a pending proceeding only when a reference file states it, with the citation given there. A pending case stays pending: put it in the open points with its date and never present its outcome as settled.
- Read the dates in each reference. A rule that takes effect after the law-as-of date or before the product's launch goes into the open points with its date.
- Never invent facts about the seller or the product. Ask.
- Never state a number (a threshold, a cap, an amount, a headcount ceiling) that the references do not state, such as the EU micro and small enterprise ceilings of Recommendation 2003/361/EC or an inflation-adjusted CCPA revenue figure; name the instrument that sets it and put the figure in the open points.
- Where an official model offers options (for example general or specific authorisation of sub-processors in the Art. 28 standard contractual clauses), set out the options and ask which one the client wants; do not choose for the client.
- Keep German model texts in German. An English working translation may go into the annotations, marked as unofficial.

## References

Read only the files the applicability table needs. Each reference file opens with its citation, version and law-as-of date.

Start here:
- `references/coverage-matrix.md`: which topic is covered in which jurisdiction, and what is only flagged.
- `references/conflicts.md`: where US and EU drafting collide, and when to split a document.
- `references/prescribed-wording.md`: button labels, model forms and statutory statements, verbatim.
- `references/glossary.md`: defined terms across the instruments, with the official German terms.

Checklists (one per document type): `references/checklists/` eu-b2c, eu-b2b, de-agb, us-consumer, privacy-notice-gdpr, privacy-notice-us, eula, subscription-auto-renewal, platform-ugc.

Clause library (core wording plus EU consumer, EU business, Germany and US modules): `references/clauses/` acceptance-and-formation, changes-to-terms, term-renewal-and-cancellation, price-and-payment, withdrawal-eu, warranty-and-conformity, liability-and-disclaimers, indemnity, licence-grant, user-content, acceptable-use, moderation-and-suspension, intellectual-property, privacy-and-data, connected-product-data, ai-features, governing-law-and-jurisdiction, dispute-resolution, notices-and-communications, assignment, severability-and-entire-agreement, children-and-age, marketing-communications.

Templates: `templates/` terms-of-service, subscription-terms, eula, privacy-notice, cookie-notice, acceptable-use-policy, data-processing-agreement, withdrawal-information, impressum, implementation-requirements.

EU (`references/eu/`):
| Topic | File |
|---|---|
| Consumer Rights Directive 2011/83/EU, with the withdrawal function and 2024/825 duties | `crd.md` |
| Unfair Contract Terms Directive 93/13/EEC | `uctd.md` |
| Unfair Commercial Practices Directive 2005/29/EC | `ucpd.md` |
| Digital Content Directive (EU) 2019/770 | `dcd.md` |
| Sale of Goods Directive (EU) 2019/771 | `sgd.md` |
| Right to repair, Directive (EU) 2024/1799 | `repair.md` |
| e-Commerce Directive 2000/31/EC | `ecd.md` |
| GDPR: privacy notice content | `gdpr-privacy-notice.md` |
| GDPR: lawful bases and consent | `gdpr-legal-bases.md` |
| GDPR: processors and international transfers | `gdpr-processors-transfers.md` |
| GDPR: data subject rights, remedies and liability | `gdpr-rights-liability.md` |
| ePrivacy Directive: cookies and device access | `eprivacy-cookies.md` |
| Digital Services Act | `dsa.md` |
| P2B Regulation (EU) 2019/1150 | `p2b.md` |
| Data Act (EU) 2023/2854 | `data-act.md` |
| AI Act (EU) 2024/1689 | `ai-act.md` |
| Software Directive 2009/24/EC | `software-directive.md` |
| Geo-blocking Regulation (EU) 2018/302 | `geoblocking.md` |
| Product Liability Directive (EU) 2024/2853 | `pld.md` |
| Rome I and Brussels Ia: governing law and jurisdiction | `jurisdiction-and-law.md` |

Germany (`references/de/`):
| Topic | File |
|---|---|
| Consumer contracts and distance selling (§§ 312 to 312m BGB) | `bgb-fernabsatz.md` |
| Right of withdrawal (§§ 355 to 361 BGB) | `bgb-widerruf.md` |
| Standard terms control (§§ 305 to 310 BGB) | `bgb-agb.md` |
| Digital products (§§ 327 to 327u BGB) | `bgb-digital.md` |
| Sale, defects and consumer goods (§§ 433 to 445c, 474 to 479g BGB) | `bgb-kauf.md` |
| EGBGB information duties and model forms | `egbgb.md` |
| Impressum and commercial communications (DDG) | `ddg-impressum.md` |
| Cookie and tracking consent (TDDDG) | `tdddg.md` |
| Software copyright (§§ 69a to 69g UrhG) | `urhg-software.md` |
| Consumer dispute resolution notice (VSBG) | `vsbg.md` |
| BDSG exceptions to data subject rights | `bdsg.md` |

US federal (`references/us-federal/`):
| Topic | File |
|---|---|
| FTC Act section 5 and dark patterns | `ftc-act-dark-patterns.md` |
| ROSCA and the Negative Option Rule | `negative-option.md` |
| Online assent, ESIGN and the wrap cases | `online-assent.md` |
| Federal Arbitration Act and the arbitration cases | `arbitration.md` |
| Magnuson-Moss Warranty Act and 16 C.F.R. 700 to 703 | `magnuson-moss.md` |
| COPPA Act and Rule | `coppa.md` |
| Section 230 | `section-230.md` |
| Copyright: program copies and the DMCA safe harbor | `copyright.md` |
| CAN-SPAM | `can-spam.md` |

US states (`references/us-states/`):
| Topic | File |
|---|---|
| California Automatic Renewal Law | `ca-arl.md` |
| CCPA and its regulations | `ca-ccpa.md` |
| CalOPPA | `ca-caloppa.md` |
| California Civil Code §§ 1668, 1670.5, 1751 | `ca-civil-code.md` |
| New York GBL 527 and 527-a | `ny-gbl-527a.md` |
| Virginia, Colorado, Connecticut, Texas privacy acts | `va-vcdpa.md`, `co-cpa.md`, `ct-ctdpa.md`, `tx-tdpsa.md` |
| Illinois BIPA | `il-bipa.md` |
| Washington My Health My Data Act | `wa-mhmda.md` |
| Other state privacy laws, as flags to check | `state-matrix.md` |
