---
title: "Photo community with user content: questions back to the client"
description: The questions the skill asked back before drafting, and the list of files handed over.
---

*Fictional product, illustrative draft. Not legal advice.*

# Shutterline documents: drafts for counsel review

These are drafts for your outside counsel to review before launch. They are not legal advice. The underlying references are stated as of 20 October 2026; a rule that takes effect after that date, or a point this skill's references leave open, is called out in `open-points.md` rather than drafted as settled.

## Questions I still need answered

A few facts decide specific clauses below. I drafted on the stated assumption in each case and marked in `open-points.md` what your answer would change.

1. **Which EU member states beyond Germany, France and Spain, if any, do you actually sell into or direct marketing to?** I drafted the EU consumer module at directive level (it covers Germany, France and Spain at that level) and the Germany module in full detail. France and Spain each have their own national transposition of several directives (notably withdrawal mechanics and standard-terms control) that these references do not carry in full; that is an open point for local counsel in each state. If your activity reaches any other EU state, the same gap applies there too.
2. **Has Shutterline's annual turnover or headcount changed in the last 12 months, and do you know whether Shutterline qualifies as a micro or small enterprise under the EU recommendation that sets those categories?** This decides whether the DSA's internal-complaint, out-of-court-settlement and trusted-flagger duties (Art. 20 to 24) apply in full, or whether only the lighter Art. 14 to 18 duties apply. I did not estimate this from your revenue or headcount figures; the figures you gave do not by themselves answer the test the Recommendation sets, so I drafted the fuller Art. 20 to 24 duties as the safer default and flagged the exemption question as open.
3. **How exactly is personalised advertising built: from a user's own on-platform activity only, or does it also draw on browser/device tracking across other sites, SDK data from a mobile app, or data bought from third parties?** This affects both the GDPR legal-basis analysis (behavioural advertising from a free, ad-funded service needs consent, not legitimate interest) and which cookie/SDK inventory needs to be disclosed. I drafted on the assumption that personalisation uses only on-platform behaviour (views, likes) and no cross-site tracking; if that is wrong, the cookie notice and the privacy notice both need another pass.
4. **Does Shutterline process payment data, run a mobile app with its own SDKs, or store data outside the EU (backups, support tooling, a CDN, an analytics vendor outside the EEA)?** You said data sits on your own EU servers; I need to know whether any processor (hosting partner, support tool, analytics, crash reporting, push notification service) is outside the EEA before the privacy notice's international-transfer section can be finalised. Drafted as "no transfer" for now; flag if any vendor is non-EEA.
5. **Has Shutterline crossed, or do you know whether it has crossed, the CCPA's own revenue or data-volume thresholds (a specific dollar figure and a specific record count that the statute itself sets, not your global turnover)?** I cannot estimate this from the EUR 20 million global turnover figure you gave, because the CCPA test looks at gross revenue in a specific currency and a specific prior calendar year, and at records bought, sold or shared, not at global turnover as such. CalOPPA has no such threshold and applies regardless, so the US privacy notice is drafted to CalOPPA plus a conservative CCPA-style notice; confirm with counsel whether the CCPA's own numeric test is met before relying on the lighter read.
6. **What is Shutterline's actual age-verification mechanism beyond self-declared birth date, and does the product have any feature (a public leaderboard, a "nearby photographers" feature, direct messaging defaults) that could make it attractive to, or predominantly used by, under-16s?** This affects both the DSA's minors-facing language duty and the GDPR Art. 8 age-gate analysis. Drafted on the assumption that the product is not directed at or predominantly used by minors.
7. **Who is the actual contact point for the DSA's single point of contact for authorities and the separate point of contact for users, and is there a named Datenschutzbeauftragter (DPO) or other EU representative?** Placeholder contact details are used throughout; these need filling in before publication.
8. **Does Shutterline want a US arbitration and class-action-waiver clause in the US terms, or does it prefer the same dispute-resolution approach for both markets?** I drafted a US module with individual arbitration and a class-action waiver as the US-market default (per the skill's conflicts analysis), since EU law bars this for EU consumers; confirm this is the commercial preference before it goes to counsel.

## What is in this folder

- `terms-of-service.md`: the main Shutterline Terms of Service (EU consumer, EU business/advertiser, Germany and US modules throughout).
- `content-moderation-policy.md`: the content and moderation policy: what happens when a photo, comment or message is reported as infringing or against the rules, including the DSA notice-and-action flow and the US DMCA/Section 230 flow.
- `notice-and-complaint-procedures.md`: the step-by-step notice, statement-of-reasons, internal-complaint, out-of-court-settlement and counter-notice flows a user or a rights holder actually uses, written as a user-facing how-to rather than legal clause text.
- `privacy-notice.md`: the GDPR/CCPA-style privacy notice.
- `cookie-notice.md`: the cookie and tracking-technology notice (EU opt-in model with a US note).
- `impressum.md`: the German legal notice (Impressum) under the DDG.
- `annotations.md`: for every clause, its legal basis and purpose, the applicability table, and the conflict/checklist tables.
- `open-points.md`: undetermined facts, national-law gaps, rules not yet in force, and decisions for counsel.
- `implementation-requirements.md`: what the product (upload flow, report button, complaint/appeal screens, ad labelling) actually has to build, with owner and evidence columns for your team to fill in.

The law-as-of date for every reference used is **20 October 2026**. These are drafts for a qualified lawyer to review before launch; nothing here is legal advice.
