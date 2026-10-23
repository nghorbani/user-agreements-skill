---
title: Fitness app subscription
description: A fitness app with a free tier and a monthly plan with a 7-day trial, sold to consumers in Germany, Austria, California and New York.
---

*Fictional product, illustrative draft. Not legal advice.*

# Fitness app subscription

## The request

```text
We are Example Fitness GmbH, Hauptstrasse 1, 89073 Ulm, Germany, support@example-fitness.test, managing
director Jana Beispiel, registered at Amtsgericht Ulm HRB 000000. We sell Stridewell, a mobile fitness app for
iOS and Android, to consumers only. There is a free tier and Stridewell Plus at EUR 9.99 or USD 9.99 per
month, renewing automatically every month, with a 7-day free trial that turns into the paid plan unless
cancelled. People buy through our own web checkout and through in-app purchase on the app stores. Markets:
Germany, Austria, California and New York. About 40,000 users, 3,000 of them in California; annual revenue
about EUR 2 million. The app records workouts, heart rate from a connected wearable and body weight. Minimum
age 16. Data is hosted in Frankfurt; we use a US analytics SDK. No AI features, no user content, and we ship
open source libraries. Please draft our subscription terms and the withdrawal information for consumers, and
tell us exactly what our checkout, renewal and cancellation flows must do. Our external counsel reviews the
drafts next month.
```

## What the skill asked back

1. The VAT ID for the Impressum, and whether email-only contact is acceptable.
2. Whether Example Fitness GmbH itself sells the EU subscription, or an app store acts as merchant of record for in-app purchases.
3. Whether Stridewell uses workout, heart-rate and body-weight data only to run the subscription, or also for its own purposes such as analytics.
4. Whether heart-rate or body-weight data is ever treated as health data, or kept as ordinary fitness data.
5. Whether the minimum age of 16 is a product policy choice or a belief about Germany's GDPR floor.
6. Whether billing details are collected when the free trial starts, or only once it ends.
7. Whether the contracting party for California and New York sales is the German company itself or a US affiliate.
8. Whether to ship one combined subscription-terms document or three separate ones by market.

## The hand-over

| File | What it contains |
|---|---|
| [reply.md](reply.md) | The cover reply: the questions above with the assumption drafted against each one, and a summary of what was and was not drafted. |
| [subscription-terms.md](subscription-terms.md) | The subscription terms themselves, with a shared core and separate EU, Germany and US modules. |
| [withdrawal-information.md](withdrawal-information.md) | The German withdrawal notice and model form, plus an English courtesy version for other EU markets. |
| [implementation-requirements.md](implementation-requirements.md) | The build register for checkout, renewal, cancellation and withdrawal, one row per requirement with its legal basis. |
| [annotations.md](annotations.md) | The applicability table, the clause-by-clause legal basis, and the checklist and conflict results behind the drafts. |
| [open-points.md](open-points.md) | The facts still missing, the national law still to verify, and the decisions left for counsel. |

## Corrections

None: the hand-over is shown as produced.

---

The drafts are for review by a qualified lawyer. Law as of 20 October 2026.
