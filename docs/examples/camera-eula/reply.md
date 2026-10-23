---
title: "Connected camera EULA: reply to the client"
description: The skill's questions and stated assumptions for Fernlook Optics' camera EULA, cloud terms and privacy notice.
---

*Fictional product, illustrative draft. Not legal advice.*

# Reply to Fernlook Optics B.V.

These are drafts for your in-house counsel to review before the March 2027 launch, not legal advice. The law stated is current as of 20 October 2026.

## Questions we need answered before the drafts can be finalized

Where an answer is missing we drafted on a stated assumption and flagged what your answer would change in `open-points.md`. Please answer these before counsel signs off:

1. **California and New York volume/revenue, and whether diagnostic data is sold or shared.** You gave us 140,000 units expected in California over two years and a New York concentration, but no total US unit count, no revenue figure, and no per-state household count for New York, Virginia, Colorado, Connecticut or Texas. The CCPA attaches to a business that buys, sells or shares 100,000 or more consumers' or households' personal information a year, or that has over $25,000,000 in revenue, or that gets 50% or more of its revenue from selling or sharing data (Cal. Civ. Code § 1798.140(d)(1)). A unit or registration count is not the same measure as the consumer/household count the statute uses, and the drafts already state that diagnostic data is not sold. We need your actual revenue figure, and whether diagnostic data (or any other personal information) is sold or shared with any third party, before we can say whether the CCPA applies at all. We drafted the full CCPA module so it is ready to use if the answer is yes, but marked it conditional pending your answer.
2. **Who is the Scout Cloud "controller" versus "processor" for diagnostic data from a business customer (nature reserve, farm)?** You told us diagnostic data goes to you regardless of plan. For Scout Cloud photo storage bought by a business customer, do you process that content for your own purposes (controller) or only to provide storage (processor)? This decides whether a data processing agreement is needed for business subscribers.
3. **Does the on-device species-suggestion label ever get used by, or shared with, anyone who decides something about a person** (for example a reserve deciding to restrict a visitor's access based on a photo)? You said no, but please confirm this stays a pure convenience label with no downstream decisional use, since that keeps it outside GDPR Art. 22 and outside the EU AI Act's higher-risk categories.
4. **Does the camera or app ever process biometric data to identify a specific person** (e.g., facial recognition of visitors, as opposed to wildlife species ID)? You described species identification only; please confirm no human-identifying biometric processing exists, since that would trigger GDPR Art. 9 and the EU AI Act's biometric-categorisation rules.
5. **Retailer marketplaces: who is the seller of record?** You sell through your own web store and two electronics retailers' marketplaces. Do you sell directly to the end customer through those marketplaces (you are the trader, the marketplace is a P2B intermediation service you use), or does the retailer buy from you and resell in its own name? This decides whether our terms are the end-customer contract on marketplace sales at all, and whether the EU P2B Regulation reaches your relationship with those two retailers.
6. **Firmware support window.** You said firmware updates run "for as long as we support the model" with no stated figure. EU and German law require updates for the conformity period or a period the consumer may reasonably expect, whichever is relevant; please give us your actual planned minimum support commitment (e.g., "5 years from last unit sold") so we can state a concrete, binding figure rather than the open-ended phrase, which is itself a conformity risk if too short for what a consumer in this product category would reasonably expect.
7. **Perpetual desktop app licence: is it tied to the device, or freestanding?** You said the companion app licence is "included in the camera price" and "perpetual." Does the licence end if the camera is destroyed/sold, or does the user keep the app regardless? This affects the resale/transfer (UsedSoft exhaustion) clause.
8. **Does Scout Cloud offer any free tier or storage bundled with the camera purchase itself**, separate from the paid add-on? You said "no free trial," but please confirm there is no free photo-storage allotment that later converts to paid, since that would trigger different auto-renewal disclosure timing.
9. **Does the company collect, or plan to collect, data on US children under 13, or market to a younger audience in any market?** You said "no children's features" and nothing in the facts points to a younger audience, so we have not built any children's-data provisions into the EULA or the privacy notice. Please tell us if that changes.
10. **Does the Wi-Fi camera transmit wildlife photos to Fernlook's own servers at all outside Scout Cloud** (e.g., transiently for firmware/app features), or do non-subscribers' photos stay entirely on local/device storage with zero transit through your infrastructure? This affects whether a non-subscriber's photos are "diagnostic data" adjacent processing requiring its own basis.
11. **Does the retail packaging or any point-of-sale material in Germany, the Netherlands or the US make a specific durability, repairability or environmental claim** (e.g., "weatherproof for 5 years," "eco-friendly packaging")? We need the exact wording used, since such claims carry their own substantiation and disclosure duties we cannot draft without seeing them.
12. **Reviewer and timeline.** You said in-house counsel reviews before March 2027 launch; please confirm the specific reviewer and any earlier internal milestone (e.g., packaging print deadline) we should work backward from, since packaging artwork typically locks months before launch.

## What we delivered now, on stated assumptions

We drafted all four requested documents plus the supporting hand-over files on the following assumptions, each marked in `open-points.md` with what your answer would change:

- CCPA applicability is undetermined until you confirm your revenue and whether any personal information is sold or shared; the CCPA module is drafted in full and ready to use if the answer turns out to be yes (confirm with Q1).
- Scout Cloud is a controller relationship for both consumer and business subscribers (assumption; confirm with Q2).
- The species-suggestion feature is a pure convenience label with no decisional use and no biometric human-identification (assumption; confirm with Q3-Q4).
- You sell directly to end customers through the two retailer marketplaces, i.e. you are the trader of record there too (assumption; confirm with Q5).
- Firmware support runs for a minimum of 5 years from last unit sold, stated as a placeholder figure you must replace (assumption; confirm with Q6).
- The desktop app licence survives transfer of the camera as a resalable bundle under the EU exhaustion rule (one-off fee, unlimited duration) (assumption; confirm with Q7).
- No bundled free Scout Cloud tier exists (assumption; confirm with Q8).
- No children's features and nothing aimed at a younger audience, so no children's-data provisions are built into the drafts (assumption; confirm with Q9).
- Diagnostic data transits Fernlook's infrastructure for every camera, subscriber or not, since the camera itself is Wi-Fi connected and always reports (assumption; confirm with Q10).
- No specific durability/environmental claim exists yet in packaging copy (assumption; confirm with Q11).

## Documents delivered

In this hand-over:

1. `eula-desktop-app-and-firmware.md` -- End user licence agreement for the Scout desktop app and the camera firmware (EU consumer, EU business, Germany and US modules).
2. `scout-cloud-terms.md` -- Terms for the Scout Cloud subscription add-on (EU consumer, EU business, Germany, US consumer modules; auto-renewal disclosures).
3. `privacy-notice.md` -- Privacy notice covering the diagnostic/usage data stream and the Scout Cloud photo data, with GDPR, German (TDDDG/BDSG) and US (CCPA, CalOPPA; Virginia/Colorado/Connecticut/Texas flagged) modules.
4. `impressum.md` -- German legal notice (Impressum) page content, since Germany is a launch market.
5. `annotations.md` -- Clause-by-clause legal basis and purpose, plus the applicability table and the checklist tables.
6. `open-points.md` -- Every undetermined fact, national-law gap, future-effective rule, and decision reserved to counsel.
7. `implementation-requirements.md` -- What the packaging, first-run setup, account flow, checkout and app must actually do, with owner/evidence columns for your product and engineering teams.

We did not draft a data processing agreement template as a standalone document because your message did not describe a scenario where Fernlook processes personal data on another party's instructions as a processor (the business-reserve/farm customers appear to be Fernlook's own direct customers, with Fernlook as controller of their account and diagnostic data) -- see the applicability table in `annotations.md` and open point OP-2. If Q2's answer shows a processor relationship exists (for example, if a reserve operator is itself a controller of photos containing identifiable people and asks Fernlook to process them as DPA-governed processor data), tell us and we will add the data processing agreement from the skill's template.

A qualified lawyer must review all of these drafts before they are used or relied on.
