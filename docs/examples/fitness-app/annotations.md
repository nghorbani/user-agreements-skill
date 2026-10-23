---
title: "Fitness app subscription: annotations"
description: The applicability table, clause-by-clause legal basis and conflict checks behind the subscription terms draft.
---

*Fictional product, illustrative draft. Not legal advice.*

# Annotations

Law as of 2026-10-20. Drafting aid for counsel review, not legal advice.

## 1. Applicability table

One row per instrument considered. "Applies" / "does not apply" / "undetermined" per the facts given (Example Fitness GmbH, Ulm; consumers only; mobile fitness app, free tier plus EUR/USD 9.99 monthly subscription with a 7-day free trial; markets Germany, Austria, California, New York; about 40,000 users, 3,000 in California; about EUR 2 million annual revenue; workout, heart-rate and body-weight data; minimum age 16; Frankfurt hosting; US analytics SDK; no AI features; no user content; ships open-source libraries).

| Instrument | Status | Deciding provision | Missing fact / note |
|---|---|---|---|
| Consumer Rights Directive 2011/83/EU | Applies | Art. 2(7), 2(8): Stridewell Plus is sold at a distance, to a consumer, for a price (§ 312 Abs. 1 BGB mirrors this for Germany) | None |
| Unfair Contract Terms Directive 93/13/EEC | Applies | Pre-formulated standard subscription terms offered to a consumer (Art. 2(b), (c)) | None |
| Unfair Commercial Practices Directive 2005/29/EC | Applies | Trader-to-consumer commercial practice (Art. 2(d)) | None |
| Digital Content Directive (EU) 2019/770 | Applies | Stridewell Plus is a digital service (ongoing access), not a single act of supply | None |
| Sale of Goods Directive (EU) 2019/771 | Does not apply | No physical goods are sold; the app is a digital service | None |
| e-Commerce Directive 2000/31/EC | Applies | Own web checkout is an information society service | None |
| Geo-blocking Regulation (EU) 2018/302 | Applies, with an open point | Electronically supplied service sold into more than one Member State (Art. 2(1)) | Whether the EUR/USD dual-pricing design itself creates unlawful customer-location pricing differentiation is flagged in open-points.md, not resolved |
| Rome I / Brussels Ia | Applies | Cross-border EU consumer contract | None |
| GDPR: privacy notice, legal bases, processor/transfer rules, rights | Applies, but out of scope for this delivery | Personal data (workout, heart rate, weight) processed from an EU establishment | A privacy notice is a separate document this delivery does not draft; flagged in open-points.md |
| ePrivacy / TDDDG (cookies) | Applies, but out of scope for this delivery | Online interface used by consumers in the EU/Germany | Not drafted in this delivery (no cookie notice requested) |
| Digital Services Act | Does not apply to the subscription/withdrawal documents drafted | Stridewell is not a hosting service or online platform: no user content, confirmed by the client | None |
| AI Act | Does not apply | Client confirmed no AI features | None |
| Software Directive 2009/24/EC | Applies, narrowly | Stridewell ships open-source libraries and is itself an app with software components | The subscription-terms draft does not include a full EULA/licence-grant clause since none was requested; flagged in open-points.md as a document not drafted |
| BGB consumer contracts / distance selling (§§ 312-312m) | Applies | Example Fitness GmbH is established in Germany and sells to German consumers at a distance | None |
| BGB right of withdrawal (§§ 355-361) | Applies | Distance contract for a digital service, no goods exception applies | None |
| BGB standard terms control (§§ 305-310) | Applies | Subscription terms are AGB offered to German consumers | None |
| BGB digital products (§§ 327-327u) | Applies | Stridewell Plus is a digital service supplied against a price | None |
| Impressum (DDG) | Applies, but out of scope for this delivery | Commercial digital-service provider established in Germany | Not drafted in this delivery; flagged in open-points.md |
| Cookie/tracking (TDDDG) | Applies, but out of scope for this delivery | German users, online interface | Not drafted in this delivery |
| US federal: ROSCA / Negative Option Rule | Applies (ROSCA); Negative Option Rule (16 C.F.R. Part 425) does not apply | Sale is effected on the internet (ROSCA, § 8403); Part 425 is scoped to physical merchandise shipped by mail, which Stridewell is not | None |
| US federal: online assent / ESIGN | Applies | US checkout and clickwrap/assent flow | None |
| US federal: FTC Act dark patterns | Applies | Any US-facing design | None |
| California Automatic Renewal Law | Applies, subject to one check | Automatic renewal offer made to a California consumer; none of the six exempt categories (franchise, CPUC/FCC/FERC-regulated affiliate, Department of Insurance entity, alarm company, bank/credit union, service-contract seller) was named as applicable | Confirm Example Fitness GmbH and any affiliate do not fall into an exempt category (§ 17605(a)-(f)); nothing in the facts suggests it does |
| California CCPA | Undetermined | Revenue/user-volume/revenue-share thresholds (Cal. Civ. Code § 1798.140) | See open-points.md; the facts given do not let the skill calculate whether a threshold is crossed |
| CalOPPA | Applies, but out of scope for this delivery | Commercial online service collecting PII from California residents | Not drafted; feeds the (separate) privacy notice |
| New York GBL 527/527-a | Applies, subject to one check | Automatic renewal/continuous service offer made to a New York consumer; none of the five exempt categories named | Confirm no exempt-category status (§ 527-a(4)(a)-(e)); nothing in the facts suggests it applies |
| Washington My Health My Data Act | Undetermined, flagged only | Depends on whether Washington residents use Stridewell and whether heart-rate/weight data is "consumer health data" under the Act's broad definition | Not among the stated markets (Germany, Austria, California, New York); flagged only because the data categories are of the kind the Act reaches, in case of future expansion |
| Illinois BIPA | Does not apply on the facts given | No stated biometric identifier (fingerprint, iris/retina scan, voiceprint, face/hand geometry scan) is collected; heart rate and body weight are not biometric identifiers under the Act's definition | None |
| Virginia / Colorado / Connecticut / Texas privacy acts | Does not apply on the facts given | None of these states is a named market | None |

## 2. Clause-by-clause legal basis (subscription-terms.md)

| Clause / module | Legal basis | Purpose |
|---|---|---|
| Acceptance and sign-up | Art. 8(2), Art. 6(1) CRD; § 312j Abs. 2, 3 BGB; Case C-249/21 Fuhrmann-2; `references/clauses/acceptance-and-formation.md` | States how the contract forms and what must sit next to the order button |
| Price and payment | Art. 6(1)(e), 19, 22 CRD; § 312a, § 312j Abs. 1, 2 BGB; `references/clauses/price-and-payment.md` | States the EUR/USD 9.99 price, payment methods, and the no-surprise-charges rule |
| Term, renewal and cancellation | `references/clauses/term-renewal-and-cancellation.md`; `references/checklists/subscription-auto-renewal.md`; § 309 Nr. 9, § 312k BGB; Cal. Bus. & Prof. Code §§ 17601-17606; N.Y. GBL § 527-a | States the monthly renewal mechanism, the German cancellation button, and the US disclosure/consent/cancellation duties |
| Free trial conversion | 15 U.S.C. § 8403 (ROSCA); Cal. Bus. & Prof. Code § 17602(a)(1), (b)(1); N.Y. GBL § 527-a(1)(a), (h); Art. 6(1)(e) CRD | States the 7-day trial, the pre-conversion disclosure, and the reminder timing |
| Changes to these terms | `references/clauses/changes-to-terms.md`; UCTD Annex points (i), (j), (k); § 308 Nr. 4, § 309 Nr. 9 BGB; Art. 19 DCD; § 327r BGB | Limits Stridewell's ability to change price or features unilaterally |
| The right to withdraw (EU and Germany) | `references/clauses/withdrawal-eu.md`; Art. 9-16a CRD; §§ 355-361 BGB | Gives EU/German consumers the 14-day cooling-off right for the subscription |
| What the subscription delivers (conformity) | `references/clauses/warranty-and-conformity.md`; Art. 6-8 DCD; §§ 327d-327f BGB | States Stridewell's conformity duty as a digital service |
| Liability and disclaimers | `references/clauses/liability-and-disclaimers.md`; UCTD Annex (a), (b); § 309 Nr. 7 BGB | Sets the liability floor that cannot be excluded, and the narrow band that can be limited |
| Your personal data | `references/clauses/privacy-and-data.md` (cross-reference only; full privacy notice not drafted here) | Points to the separate privacy notice rather than restating GDPR content in the subscription terms |
| Age and children | `references/clauses/children-and-age.md`; Art. 8 GDPR; 16 C.F.R. Part 312 (COPPA, for the US market even though Stridewell's stated floor of 16 is above COPPA's 13) | States the age-16 floor and what happens if a younger user is found |
| Governing law and jurisdiction | `references/clauses/governing-law-and-jurisdiction.md`; Rome I Art. 6; Brussels Ia Art. 18, 19, 25; Case C-191/15 VKI v Amazon | Splits EU-consumer and US modules per Conflicts C-3, C-4 |
| Notices and communications | `references/clauses/notices-and-communications.md` | States how notices (including renewal and price-change notices) are delivered |

## 3. Checklist results

### subscription-auto-renewal.md

One row per checklist item that applies to Stridewell Plus (monthly, EUR/USD 9.99, 7-day free trial, EU web checkout plus app-store IAP, Germany/Austria/California/New York markets). "Met" cites the clause that meets it; "open point" cites the open-points.md entry; items about a jurisdiction not reached by this subscription (financial services, exempt business categories) are marked not applicable.

| Item | Status | Evidence |
|---|---|---|
| Scope: not a distance financial-services contract | Met | Stridewell is a fitness app subscription, not a financial-services contract |
| Scope: not a California-exempt business category | Met, pending confirmation | No exempt category named in the facts; flagged for a final confirmation in annotations table above |
| Scope: not a New York-exempt business category | Met, pending confirmation | Same as above |
| Scope: German cancellation-button duty carve-outs do not apply | Met | Stridewell is not a financial-services website and its cancellation is not required in a stricter-than-text form |
| Total price, duration, termination conditions shown before binding (EU) | Met | Subscription-terms.md, "Acceptance and sign-up" and "Price and payment" modules |
| Renewal offer terms clear and conspicuous (CA) | Met | Subscription-terms.md, "Term, renewal and cancellation" module, US sub-module |
| Offer's material terms clear and conspicuous (NY) | Met | Same module |
| Free trial price-change disclosure | Met | "Free trial conversion" paragraph in Term, renewal and cancellation module |
| No contract term undermines consent (CA) | Met | "Must not" statement carried into the US module |
| Payment-method surcharge rule (DE) | Met | Price and payment module, Germany sub-module |
| No pre-ticked paid option (DE) | Met | Same |
| Renewal term cap (DE, § 309 Nr. 9 BGB) | Met | Term, renewal and cancellation module, Germany sub-module: Stridewell Plus renews monthly, well under the two-year/one-month-notice cap |
| Pre-billing negative-option disclosure (US federal) | Met | Free trial conversion paragraph |
| Order button prescribed label (EU/DE) | Met | Acceptance and sign-up module; implementation-requirements.md row 1 |
| Input-error correction step (DE) | Met | Implementation-requirements.md, Offer and checkout section |
| Express consent before first charge (CA/NY) | Met | Free trial conversion paragraph |
| Simple stop-charges mechanism (US federal) | Met | Term, renewal and cancellation module, US sub-module |
| Durable-medium order confirmation (EU) | Met | Acceptance and sign-up module |
| Pre-billing trial-end notice, 3-21 days (CA) | Met | Free trial conversion paragraph; implementation-requirements.md Renewal and reminders section |
| Material-change notice (CA/NY) | Met | Changes to these terms module |
| Deemed-consent price-change ban (DE) | Met | Changes to these terms module, Germany sub-module |
| German cancellation button, confirmation page, five fields only | Met | Term, renewal and cancellation module, Germany sub-module; implementation-requirements.md Cancellation and Withdrawal sections |
| No login step in German cancellation flow | Open point | Pending 5 November 2026 BGH ruling; drafted on the no-login assumption, flagged in open-points.md |
| Missing/non-compliant button = any-time cancellation (DE) | Met | Term, renewal and cancellation module, "Must not" statement |
| EU 14-day withdrawal right and function | Met | withdrawal-information.md and the withdrawal module in subscription-terms.md |
| Records of consent and information shown | Open point (product build, not drafting) | Implementation-requirements.md, Records section |

### eu-b2c.md

Every item in the "Before drafting," "Checkout and the order button," "Confirmation after the order," "Cancellation and termination" and "The EU right of withdrawal" sections is either met by the drafted clauses (see legal-basis table above) or carried into implementation-requirements.md as a build item. Items under "Repair" are not applicable (Stridewell is a digital service, not a repairable good). Items under "Cross-border sales and non-discrimination" are met in principle but carry the open point on dual EUR/USD pricing noted in open-points.md.

### de-agb.md

Every item under "Checkout and the order button," "Confirmation after the order" and "Cancellation button and flow" is met by the Germany sub-modules of subscription-terms.md and by implementation-requirements.md. Items under "Goods: conformity, defects and consumer-sales rules" and "Digital products" conformity sections are not applicable to the subscription-terms deliverable as drafted (conformity is addressed at clause level, not the full BGB digital-products remedy ladder, since the client asked specifically for subscription terms and withdrawal information rather than a full terms-of-service). The VSBG dispute-resolution notice and the Impressum are flagged as separate documents not drafted in this delivery (open-points.md).

### us-consumer.md

Not run as a separate checklist pass: the client's request (subscription terms, withdrawal information, and checkout/renewal/cancellation flow requirements) is substantially covered by the subscription-auto-renewal.md checklist for the US modules. A full us-consumer.md pass would be needed before a complete US-facing terms-of-service (dispute resolution, liability caps, indemnity) ships; flagged in open-points.md as out of scope for this delivery.

## 4. Prescribed-wording check (flows and controls)

| Control | Label used | Reference |
|---|---|---|
| EU/German order-submission button | "zahlungspflichtig bestellen" (DE) / "order with obligation to pay" (other EU) | PW-DE-1 / PW-EU-1 |
| German cancellation button | "Verträge hier kündigen" | PW-DE-2 |
| German cancellation confirmation button | "jetzt kündigen" | PW-DE-3 |
| German/EU withdrawal function | "Vertrag widerrufen" (DE) / "withdraw from contract here" (other EU) | PW-DE-4 / PW-EU-2 |
| German/EU withdrawal confirmation function | "Widerruf bestätigen" (DE) / "confirm withdrawal" (other EU) | PW-DE-5 / PW-EU-3 |
| California phone cancellation trigger | "cancel" | PW-US-CA-1 |
| California online cancellation control | "click to cancel" | PW-US-CA-2 |

All five German labels (PW-DE-1 through PW-DE-5) are checked together as the conflicts.md C-7 entry requires, since Stridewell Plus's flow touches §§ 312j, 312k and 356a BGB together.

## 5. Conflicts checked (references/conflicts.md)

| Conflict | Applies to Stridewell | Resolution used |
|---|---|---|
| C-1 / C-2 (arbitration, delegation clauses) | Not applicable: no dispute-resolution clause drafted in this delivery | N/A |
| C-3 (governing law naming trader's home state) | Applies | EU module states the mandatory-protection disclosure; US module keeps the home-state clause |
| C-4 (forum-selection clause) | Applies | EU module states the Brussels Ia dual-forum rule instead of a single named court |
| C-5 (broad as-is disclaimer) | Applies | EU/Germany liability module keeps only the narrow permitted exclusions; US module keeps the broader disclaimer |
| C-6 (unilateral change clause) | Applies | Changes-to-terms module splits EU/Germany (reasoned, capped, notice-and-termination) from US (broader) |
| C-7 (auto-renewal/cancellation mechanics) | Applies directly | Germany gets its own cancellation button and confirmation page; US keeps its own retention-offer-after-request model |
| C-8 (retention offers before cancellation) | Applies | Dropped entirely from the German confirmation page; kept, single-offer-only, for the US module |
| C-9 through C-19 | Reviewed; not materially triggered on the facts given (no user content, no AI features, no platform/marketplace structure, no software licence sold as a one-off perpetual fee) | N/A, noted for completeness |

## Reminder

Law as of 2026-10-20. A qualified lawyer must review these drafts before Example Fitness GmbH relies on them.
