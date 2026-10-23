---
title: "Connected camera EULA"
description: A Wi-Fi wildlife camera sold in Germany, the Netherlands and the US asks for a licence agreement, cloud terms and a privacy notice.
---

*Fictional product, illustrative draft. Not legal advice.*

# Connected camera EULA

## The request

```text
We are Fernlook Optics B.V., Kerkstraat 24, 1017 GB Amsterdam, Netherlands, legal@fernlook-optics.test,
managing director Sanne Dekker, registered at Kamer van Koophandel 00000000. We make Fernlook Scout, a Wi-Fi
connected camera for wildlife and nature photography, a one-off hardware purchase at EUR 249 or USD 259. It
ships with a desktop companion app for Windows and macOS under a perpetual licence included in the camera
price, and the camera receives firmware updates over the air from us for as long as we support the model. We
also offer Scout Cloud, an optional add-on plan at EUR 4.99 or USD 4.99 per month for cloud photo storage,
billed monthly and renewing automatically until cancelled; no free trial on Scout Cloud. Sold to consumers and
to businesses (for example nature reserves and farms using it for monitoring) through our own web store and
through two electronics retailers' marketplaces. Markets at launch: Germany, the Netherlands, and the United
States, nationwide, with concentrations in California (about 140,000 units expected to be registered to
California addresses in the first two years) and New York. The camera continuously collects diagnostic and
usage data, such as device temperature, battery health, Wi-Fi signal quality, firmware version, and crash
logs, and transmits it to us whenever the camera is online; this is separate from the wildlife photos
themselves, which stay on the user's own storage or in Scout Cloud if they subscribe. No children's features
and nothing aimed at a younger audience. No AI-based decisions about people; the app does on-device species
suggestions only as a convenience label on photos, nothing automated that affects a person's rights. Market
launch is planned for March 2027. We need the end user licence agreement for the desktop app and the firmware,
the terms for Scout Cloud, a privacy notice covering the diagnostic data, and a clear statement of what our
product packaging, first-run setup and account flows have to do to be compliant. Our in-house counsel wants to
review everything before the launch date.
```

## What the skill asked back

Before finishing the drafts, the skill asked the client twelve questions. The short form:

1. What are the actual California and New York sales figures, and does the company sell or share any personal information with third parties?
2. Is Fernlook a controller or a processor of diagnostic data for business (reserve/farm) Scout Cloud subscribers?
3. Does the species-suggestion label ever feed into a decision about a person?
4. Does the camera or app ever identify a specific person biometrically?
5. On the two retailer marketplaces, is Fernlook the seller of record, or does the retailer resell in its own name?
6. What is the actual firmware support window?
7. Does the desktop app licence travel with the camera when it is resold, or stay with the original buyer?
8. Is there any bundled free Scout Cloud storage, separate from the paid plan?
9. Does the product collect data on US children, or market to a younger audience anywhere?
10. Does the camera send photos to Fernlook's own servers outside Scout Cloud?
11. Does any packaging or marketing copy make a durability, repairability or environmental claim?
12. Who is the actual reviewer and launch timeline the drafts should work backward from?

## The hand-over

| File | What it contains |
|---|---|
| [reply.md](reply.md) | The cover message to the client: the twelve questions, the assumptions made where an answer was missing, and the list of documents delivered. |
| [eula-desktop-app-and-firmware.md](eula-desktop-app-and-firmware.md) | The end user licence agreement for the desktop app and camera firmware, with EU consumer, EU business, German and US modules. |
| [scout-cloud-terms.md](scout-cloud-terms.md) | Subscription terms for the optional cloud storage plan, including acceptance, pricing, auto-renewal, withdrawal and liability modules. |
| [privacy-notice.md](privacy-notice.md) | The privacy notice covering diagnostic data, Scout Cloud account and photo data, and order data, with GDPR, German and US rights sections. |
| [impressum.md](impressum.md) | The German legal notice (Impressum) the Dutch company owes for selling into Germany, plus the dispute-resolution notice. |
| [annotations.md](annotations.md) | The applicability table showing which laws apply, do not apply or are undetermined, and the checklist tables run against each document. |
| [open-points.md](open-points.md) | Every undetermined fact, national-law gap, future-effective rule and decision left for counsel. |
| [implementation-requirements.md](implementation-requirements.md) | What packaging, first-run setup, checkout and the app actually have to do, handed to product and engineering. |

## Corrections

Three passages were corrected after review.

- California privacy law. The draft concluded that the CCPA applies because about 140,000 units will be registered
  to California addresses. The CCPA's volume test counts the consumers or households whose personal information a
  business buys, sells or shares each year, not units sold (Cal. Civ. Code § 1798.140(d)(1)(B)), and the drafts say
  the diagnostic data is not sold. CCPA applicability is now undetermined until the client gives its revenue and
  says whether any personal information is sold or shared. The CCPA module stays in the privacy notice, marked for
  use only if the CCPA applies, and no adjusted revenue figure is stated.
- Children's privacy. The draft carried a COPPA statement in the EULA and the privacy notice, although the product
  has no children's features and nothing aimed at a younger audience. COPPA does not attach to a service that is
  not directed to children when the operator has no actual knowledge of collecting from a child (16 C.F.R. § 312.3;
  § 312.2, "Website or online service directed to children"). The statements are gone, and the annotations record
  COPPA as not applying, with that reason.
- AI Act. The EULA told consumers that the species-suggestion feature avoids the practices prohibited by Article 5
  of the AI Act, and the annotations treated the Article 50 transparency duty as settled not to apply. The consumer
  statement is removed. Whether the species label is output that Article 50 reaches depends on how the feature
  behaves, so it is now an open point for counsel (Regulation (EU) 2024/1689, Art. 50(1) to (6)). The EULA still
  describes what the feature does.

The drafts are for review by a qualified lawyer. Law as of 20 October 2026.
