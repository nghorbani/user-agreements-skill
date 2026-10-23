---
title: "Photo community with user content: implementation requirements"
description: The hand-over register from the legal drafts to the product and engineering teams, with owner and evidence columns.
---

*Fictional product, illustrative draft. Not legal advice.*

# Shutterline implementation requirements

Law as of: 2026-10-20. This is the hand-over register from the legal drafts to the product and engineering teams that build the upload flow, the report button, the complaint and appeal screens, and ad labelling. Each row names one thing the product must do, the rule it rests on, who owns building and checking it, what evidence proves it is done, and its status. Fill in Owner and Status for your own team; Requirement, Legal basis and Evidence come from the drafts and do not change without a change to them.

Status values: not started, in progress, built, verified.

## Account creation and age gate

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Sign-up flow asks for birth date and blocks account creation for anyone under 16 | ToS §1; Content and Moderation Policy; GDPR Art. 8 | | | not started |
| Assent sentence sits on the same screen as the "Create account" button, names that exact button label, and is updated whenever the label changes | ToS §1 US module; Chabolla v. ClassPass | | | not started |
| Full terms are reachable, storable and reproducible from the sign-up screen (not displayed once and gone), including on an email-only channel if one exists | ToS §1 EU module; Art. 10(3), (4) Directive 2000/31/EC | | | not started |
| Electronic acknowledgement of account creation sent without undue delay | ToS §1 EU module; Art. 11(1) Directive 2000/31/EC | | | not started |
| Standing, permanently linked legal-notice (Impressum) page exists, independent of the sign-up flow, kept current as the business's registration details change | Impressum document; § 5 Abs. 1 DDG | | | not started |

## Upload flow

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Upload flow lets a user confirm, before posting, that they have the rights needed to post the content and that it does not infringe a third party's rights | ToS §5 | | | not started |
| Public photo/comment content is distinguished in the system from direct-message content, so the licence granted and the moderation process applied match the content type (public licence vs. limited delivery-only licence for messages) | ToS §5, §9 | | | not started |
| Content-moderation tooling records, per piece of content, whether a decision (if any) was made by an automated tool, a human reviewer, or both | Content and Moderation Policy §2; Art. 16(6), 17(3) Regulation (EU) 2022/2065 | | | not started |
| An automated hash-match system for known child sexual abuse material removes matching content immediately, without discretion, and logs the action | Content and Moderation Policy §2 | | | not started |

## Report button and report form

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| A "Report" control is shown on every public photo and comment, and on a direct message (visible only to its recipient) | Notice and Complaint Procedures §1; Content and Moderation Policy §3, §4 | | | not started |
| Report form captures: reason category, free-text explanation, automatic location capture (no manual link needed), reporter name and email (skipped only for the CSAM category), and a good-faith accuracy confirmation checkbox | Notice and Complaint Procedures §1; Art. 16(2)(a) to (d) Regulation (EU) 2022/2065 | | | not started |
| Report submission triggers an automatic confirmation-of-receipt email where the reporter gave an email address, sent without undue delay | Notice and Complaint Procedures §1; Art. 16(4) Regulation (EU) 2022/2065 | | | not started |
| Reports meeting all required fields are routed to priority/expedited review queues over incomplete reports | Notice and Complaint Procedures §1; Art. 16(3) Regulation (EU) 2022/2065 | | | not started |
| A trusted-flagger account type exists (or can be configured) so a report from a Digital-Services-Coordinator-awarded trusted flagger is automatically routed to priority processing within its designated area | Content and Moderation Policy §5; Art. 22(1) Regulation (EU) 2022/2065 | | | not started |
| System logs, for each trusted flagger, the rate of reports found manifestly unfounded, to support the required escalation to the awarding Digital Services Coordinator instead of a unilateral internal de-prioritisation | Content and Moderation Policy §5; Art. 22(6), (7) Regulation (EU) 2022/2065 | | | not started |
| US copyright-specific notice path (DMCA form or dedicated email) exists separately from the general report form, capturing all six statutory elements | Notice and Complaint Procedures §5; 17 U.S.C. § 512(c)(3) | | | not started |
| Designated DMCA agent's name, address, phone and email are published on a reachable page and kept in sync with the filing made with the US Copyright Office | ToS §8; 17 U.S.C. § 512(c)(2) | | | not started |

## Decision and statement-of-reasons delivery

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Every content removal, visibility restriction, or account suspension/termination triggers an automatic statement-of-reasons message to the affected user (where contact details are known), covering: what was decided, why, whether a report or own-initiative review led to it, whether automated means were used, the rule applied, and how to challenge it | Notice and Complaint Procedures §2; Content and Moderation Policy §3; Art. 17(1) to (4) Regulation (EU) 2022/2065 | | | not started |
| Statement-of-reasons template is maintained per decision type (removal, visibility restriction, account suspension, account termination, monetisation restriction) rather than one generic template for all | Content and Moderation Policy §3 | | | not started |
| Reported-content decision workflow notifies the original reporter of the outcome, without undue delay | Notice and Complaint Procedures §1; Art. 16(5) Regulation (EU) 2022/2065 | | | not started |

## Complaint and appeal screens

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| An in-product appeal screen exists (Settings → Account → Appeals, or a direct reply path from the decision notice), accessible without charge | Notice and Complaint Procedures §3; Art. 20(1), (2) Regulation (EU) 2022/2065 | | | not started |
| Appeal screen stays open and usable for at least six months from the date the user was notified of the decision being appealed | Notice and Complaint Procedures §3; Art. 20(1) Regulation (EU) 2022/2065 | | | not started |
| Appeal decisions are made or confirmed by a trained human reviewer, never solely by an automated system | Content and Moderation Policy §2, §6; Art. 20(6) Regulation (EU) 2022/2065 | | | not started |
| A sustained appeal automatically reverses the original decision (restores content, lifts suspension) without a separate manual step once approved | Notice and Complaint Procedures §3; Art. 20(4) Regulation (EU) 2022/2065 | | | not started |
| Appeal outcome notification includes the out-of-court settlement route information for EU users | Notice and Complaint Procedures §3, §4; Art. 20(5) Regulation (EU) 2022/2065 | | | not started |
| A page or in-product section lists the certified out-of-court dispute settlement bodies (or states that any DSA-certified body can be chosen), and tracks the asymmetric fee rule if Lumenfolk pays a body directly | Notice and Complaint Procedures §4; Art. 21(1), (5) Regulation (EU) 2022/2065 | | | not started |
| Misuse-suspension logic implements the four-factor case-by-case assessment (absolute count, proportion, gravity, intent) and issues a prior warning before any suspension of this kind | Content and Moderation Policy §8; Art. 23(1) to (3) Regulation (EU) 2022/2065 | | | not started |
| DMCA counter-notice flow captures the four statutory elements, forwards a valid counter-notice to the original notifier, and restores content between 10 and 14 business days later absent notice of a lawsuit | Notice and Complaint Procedures §5; 17 U.S.C. § 512(g) | | | not started |

## Ad labelling and ad-personalisation controls

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Every advertisement carries a real-time label showing it is an advertisement, who it is for, who paid (if different), and the main targeting parameters with a way to change them | ToS §10; Art. 26(1) Regulation (EU) 2022/2065 | | | not started |
| Personalised-advertising toggle exists, defaults to off for EU/UK users pending consent, and is wired to the cookie/consent banner choice rather than a separate, disconnected setting | Cookie Notice §1, §2; Privacy Notice §1 | | | not started |
| Ad-serving logic never selects an advertisement using special-category personal data, and never personalises an advertisement to a user known with reasonable certainty to be a minor | ToS §10; Art. 26(3), 28(2) Regulation (EU) 2022/2065 | | | not started |
| A user-facing control lets a user declare their own content contains commercial communications, and marks it for other users in real time | ToS §10; Art. 26(2) Regulation (EU) 2022/2065 | | | not started |
| Consent-management tooling (cookie banner) gives per-purpose controls, starting off, with an equally prominent reject option on the same screen as accept | Cookie Notice §2 | | | not started |
| A centralised "Privacy settings" or "Cookie settings" page lets a user withdraw ad-personalisation consent at any time, in the same number of steps the consent flow took | Cookie Notice §2, §4; Privacy Notice §5 | | | not started |
| US opt-out mechanism (or recognised opt-out preference signal) for cross-context behavioural advertising is honoured for US users | Cookie Notice §3 | | | not started |

## Privacy rights handling

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| A rights-request channel (access, rectification, erasure, restriction, objection, portability) exists, free by default, answered within one month (extendable by two further months with a logged reason) | Privacy Notice §4 | | | not started |
| Direct-marketing objection control is distinguishable from the general objection control, needs no justification, and has no internal override | Privacy Notice §4 | | | not started |
| Account-deletion flow deletes or anonymises personal data per the retention schedule, cascading to any processor holding a copy | Privacy Notice §3 | | | not started |

## Open items for product/engineering to flag back to legal

- Whether the personalised-advertising mechanism reads any identifier beyond on-platform activity (cross-device matching, SDK data, third-party data): see `open-points.md` item 6; this changes the cookie notice's third-party table and the ad-serving requirements above.
- Whether any vendor in the hosting, analytics, support or notification stack is located outside the EEA: see `open-points.md` item 7; this changes the privacy notice's international-transfer section.
- Per-country/per-state breakdown of the EU and US user base, once available, to resolve the DSA micro/small-enterprise question (item 2) and the US state-threshold questions (items 4, 5).
