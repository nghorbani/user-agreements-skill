---
title: "Connected camera EULA: implementation requirements"
description: Hand-over register from the Fernlook Scout legal drafts to product, packaging and engineering teams.
---

*Fictional product, illustrative draft. Not legal advice.*

# Implementation requirements -- Fernlook Scout

Law as of 20 October 2026. This is the hand-over register from the legal drafts to product, packaging and engineering. Fill in Owner and Status; Requirement, Legal basis and Evidence come from the drafts and the skill's reference files and do not change without a change to those.

Status values: not started, in progress, built, verified.

## Product packaging

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Packaging states Fernlook's identity, postal address and contact email in an easily accessible place, consistent with the Impressum and the pre-contract information duty, for any box sold at retail in Germany | § 5 Abs. 1 DDG (for the online listing); general EU trader-identification practice for packaging | | | not started |
| If packaging makes any durability, repairability, weatherproofing or environmental claim, the qualifying detail sits with the claim itself, and dated substantiation is kept ready to produce; no claim is finalized until legal reviews the actual wording (see `open-points.md`, OP-11) | UCTD Annex point 4a; Art. 12 Directive 2005/29/EC | | | not started |
| Packaging or an insert states the EULA and privacy notice are available before purchase, with a URL or QR code, since a consumer cannot be bound to terms they had no opportunity to see before buying a sealed retail product | Art. 6(1) Directive 2011/83/EU (pre-contract information); EU B2C checklist | | | not started |
| Packaging or insert discloses that the camera is a connected product that transmits diagnostic data when online, pointing to the privacy notice, as part of the Data Act Art. 3(2) pre-contract disclosure | Art. 3(2)(a) to (d) Regulation (EU) 2023/2854 | | | not started |
| If an offline-only mode exists that avoids diagnostic-data transmission, packaging or setup states this as a genuine option, not merely implied | Flagged in privacy-notice.md pending product confirmation | | | not started |

## First-run setup (App and camera pairing)

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| EULA acceptance control sits on the same screen as the sentence naming it, in a size and colour comparably prominent to surrounding text, directly next to the control, visible without scrolling, for US users | Berman v. Freedom Financial Network, LLC, 30 F.4th 849; online-assent.md | | | not started |
| EULA acceptance control for German/EU users is preceded, immediately and with nothing else in between, by the Art. 10(1)(a)-(d) technical-steps disclosure | Art. 10(1) Directive 2000/31/EC | | | not started |
| First-run setup carries an age-representation step calibrated per the user's jurisdiction, not one hard-coded age for every market (EULA § 10) | Art. 8(1), (2) Regulation (EU) 2016/679; `references/clauses/children-and-age.md` | | | not started |
| First-run setup surfaces the privacy notice's first-layer summary (diagnostic data transmission) at the point the camera is connected to Wi-Fi, not only inside a linked document reached later | Art. 12(1), 13(1) GDPR | | | not started |
| First-run setup for a camera with no screen (the camera itself) carries its own notice channel -- a URL printed on the quick-start card or an audio/LED confirmation -- since the GDPR notice duty applies at the point of collection, and the camera itself has no display | Art. 13(1) GDPR; privacy-notice-gdpr.md, "Surfacing the notice" | | | not started |
| Species-suggestion feature's first display carries a plain-language explanation that it is a convenience label, not a security or access-control feature, so it is never later read as a biometric identification capability | `references/clauses/ai-features.md` Must-not list | | | not started |
| Setup flow does not pre-select or default-enable any Scout Cloud upsell in a way that charges the user without a distinct, logged affirmative step | Art. 22 Directive 2011/83/EU; Cal. Bus. and Prof. Code § 17602(a)(5) | | | not started |

## Scout Cloud checkout and account flow

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Order/subscribe button carries PW-DE-1 ("zahlungspflichtig bestellen") or equivalent for German users, with nothing else on the button | § 312j Abs. 3 Satz 2 BGB; Case C-249/21, Fuhrmann-2 | | | not started |
| Price (EUR 4.99 / USD 4.99 per month), renewal terms and cancellation method shown directly before the subscribe button, not behind a link | § 312j Abs. 2 BGB; Cal. Bus. and Prof. Code § 17601(a)(2) | | | not started |
| Consent checkbox for the negative-option feature (if any is used beyond the subscribe button itself) renders unchecked by default | 15 U.S.C. § 8403(2) | | | not started |
| Confirmation email/in-app receipt sent promptly after sign-up, covering price, frequency, and cancellation instructions | Cal. Bus. and Prof. Code § 17602(a)(3); N.Y. Gen. Bus. Law § 527-a(1)(c) | | | not started |
| Permanently available cancellation button in the account/app settings, labelled PW-DE-2 for German users, routing directly to a confirmation page labelled PW-DE-3, with no login step inserted between them | § 312k Abs. 1, 2 BGB; pending BGH ruling 5 Nov 2026 -- see `open-points.md`, OP-19 | | | not started |
| Cancellation confirmation page asks only for the five statutory fields; no retention offer, discount pitch, or pause option appears on it | § 312k Abs. 2 Satz 3 BGB; BGH, 16 July 2026, I ZR 200/25 | | | not started |
| US cancellation path reachable through at least the same medium used to sign up (in-app, if sign-up was in-app), with no extra authentication step beyond what sign-up itself required | Cal. Bus. and Prof. Code § 17602(d), (f); N.Y. Gen. Bus. Law § 527-a(1)(d) | | | not started |
| A single, non-repeated retention offer may appear after a US cancellation request, never before or instead of it | Cal. Bus. and Prof. Code § 17602(e); N.Y. Gen. Bus. Law § 527-a(1)(e) | | | not started |
| EU/German withdrawal function (14-day cooling-off) available from account settings for the first 14 days after subscribing, separate from the ordinary cancellation button, labelled PW-EU-2/3 or PW-DE-4/5 | Art. 11a CRD; § 356a BGB | | | not started |
| Billing system records the sign-up medium per subscriber, so cancellation-medium parity can be shown on request | FTC 2021 negative-option guidance; Cal. Bus. and Prof. Code § 17602(f) | | | not started |
| Consent/acceptance record (timestamp, IP or device ID, terms version accepted) retained at least 3 years or 1 year past termination, whichever is longer, for California | Cal. Bus. and Prof. Code § 17602(a)(6) | | | not started |

## Diagnostic data pipeline

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Diagnostic-data vendors/sub-processors (cloud infrastructure, analytics, support tooling) are named once confirmed, and the privacy notice's "who else sees it" line is updated to match actual vendors before publication | Art. 13(1)(e) GDPR | | | not started |
| A stated or criteria-based retention period for diagnostic data is set and reflected in the privacy notice before publication; "as long as necessary" alone does not meet the GDPR floor | Art. 13(2)(a) GDPR | | | not started |
| If diagnostic data is processed outside the EEA (e.g., a US cloud region), the adequacy decision or Art. 46 safeguard relied on is documented and named in the privacy notice | Art. 13(1)(f), 44-49 GDPR | | | not started |
| Legitimate-interest assessment for diagnostic-data processing is documented (necessity and balancing test) before relying on Art. 6(1)(f), and a summary is available to data subjects on request | Art. 6(1)(f) GDPR; GDPR Guidelines 1/2024 | | | not started |
| Diagnostic-data access/export/erasure request channel exists and is tested, matching the connected-product-data clause's "accessible, retrievable, erasable" commitment | Art. 3(1), 4(1) Regulation (EU) 2023/2854 | | | not started |
| Diagnostic data is confirmed not sold or shared as defined by the CCPA before the privacy notice's "we do not sell this data" statement is published; whether the CCPA even applies to Fernlook is itself still open (see `open-points.md`, OP-1), so this confirmation matters regardless of that answer | Cal. Civ. Code § 1798.140(ad) | | | not started |

## Business (B2B) account flows -- nature reserves and farms

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Account creation flow distinguishes a business customer from a consumer at signup (e.g., an account-type selector or VAT-number field), since the EU consumer protections (withdrawal right, UCTD unfairness test) do not apply to a business acting in that capacity | Art. 2(1) Directive 2011/83/EU; `references/clauses/withdrawal-eu.md` EU business customers module | | | not started |
| Confirm, per Q2 in `reply.md`, whether Fernlook is a controller or processor of personal data for business-subscriber Scout Cloud content, and build the data processing agreement if a processor relationship is confirmed | GDPR Art. 28 | | | not started |
| Connected-product Data Act disclosures (type/volume/retention of diagnostic data) are given to business buyers the same way as consumers, since Data Act Chapter II is not limited to consumer users, unless the microenterprise/small-enterprise carve-out applies | Art. 2(12), 7(1) Regulation (EU) 2023/2854 | | | not started |

## California/CCPA-specific build items (pending OP-1 confirmation)

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Once the CCPA threshold question is resolved (both whether it applies at all, and from what date), at least two designated request channels for delete/correct/know requests, and a channel for opt-out/limit requests, are built | Cal. Civ. Code § 1798.130(a)(1) | | | not started |
| Privacy policy review-and-update cadence (at least every 12 months) is calendared | Cal. Civ. Code § 1798.130(a)(5) | | | not started |
| If Fernlook's actual data practices change such that it sells or shares personal information, the "Do Not Sell or Share My Personal Information" and "Limit the Use of My Sensitive Personal Information" links (or the combined alternative) are added to the homepage before that practice starts, using the exact prescribed titles | Cal. Civ. Code § 1798.135(a); PW-US-CA-3, PW-US-CA-4 | | | not started |

## Open points to raise

- The exact placement and click-count for the Impressum and privacy-notice links across the web store, the app, and the camera's own (screen-less) interface is not fixed by any reference file; product decides the placement, legal confirms it meets the "easily recognisable, directly accessible" and "surfaced at collection" standards once built.
- Whether Scout Cloud billing will run through Fernlook's own payment processor or a third-party platform (app store billing) is not stated; this decides whether the same-medium-as-consent cancellation duty and the German cancellation-button duty can be met through a platform's own flow, an open point the underlying clause files raise without settling.
- See `open-points.md` for the full list of undetermined facts this register depends on.
