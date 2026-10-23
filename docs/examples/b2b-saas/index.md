---
title: "B2B SaaS for manufacturers"
description: A predictive-maintenance SaaS vendor's subscription terms, data processing agreement and sub-processor change memo for customers in the EU and three US states.
---

*Fictional product, illustrative draft. Not legal advice.*

# B2B SaaS for manufacturers

## The request

```text
We are Example Machines GmbH, Werkstrasse 14, 70173 Stuttgart, Germany, legal@example-machines.test, managing
director Lukas Vogt, registered at Amtsgericht Stuttgart HRB 900000. We sell Spindlewise, a cloud platform for
predictive maintenance of factory machines, to manufacturers only, never to consumers. Customers sign an
annual subscription online, and the signing party is always someone from the customer's purchasing department
acting for their employer. Markets: Germany, France, Italy, and the US states of Ohio, Texas, and California.
The platform ingests sensor data streamed from the customer's machines and also holds personal data about the
customer's own staff who use the platform day to day: operator login accounts, shift logs tied to those
logins, and the contact details of the site contact we deal with. Everything is hosted in a cloud region in
Germany. For customer support we use a ticketing system run by a company in the United States, which sees the
content of support tickets, including anything a customer's staff member writes into one. No AI features, no
user content beyond the support tickets, no marketplace or hosting of third-party content, and no consumer-
facing parts at all. Please draft our master subscription terms for business customers, a data processing
agreement, and tell us how to handle it when we change which company runs a backend service like the support
ticketing system.
```

## What the skill asked back

1. Whether Example Machines crosses a US state privacy-law revenue or data-volume threshold, and whether it
   qualifies as an SBA small business.
2. Whether Ohio is a significant market or only incidental, since Ohio has no general consumer privacy
   statute to draft against.
3. Whether Example Machines, or a given customer, counts as a "großer Unternehmer" under German law, which
   would open a narrow set of AGB carve-outs.
4. The exact hosting arrangement behind "a cloud region in Germany": which provider, and whether it is
   a named hyperscaler region, a colocation provider, or Example Machines' own infrastructure.
5. The identity of the US support-ticketing vendor and whether it holds an EU-US Data Privacy
   Framework certification, to fix the international-transfer mechanism.
6. Whether Example Machines itself is a microenterprise or small enterprise under the EU recommendation that
   sets those categories, which bears on a narrow Data Act carve-out.
7. Confirmation that every customer signs through staff acting for their employer, with no sole
   proprietor buying for mixed personal and business use.

## The hand-over

| File | What it contains |
|---|---|
| [reply.md](reply.md) | The questions above, the list of drafts, and the short answer on changing a backend vendor. |
| [master-subscription-terms.md](master-subscription-terms.md) | The business-facing subscription agreement: formation, price, term and renewal, change of terms, the connected-machine data clause under the EU Data Act, personal data, warranty, liability, governing law and dispute resolution. |
| [data-processing-agreement.md](data-processing-agreement.md) | The GDPR Article 28 data processing agreement, built on the EU standard contractual clauses in full, plus the Texas and conditional California processor-contract terms. |
| [backend-subprocessor-change-memo.md](backend-subprocessor-change-memo.md) | The internal procedure for swapping a backend vendor, such as the ticketing system, under the general-authorisation sub-processor model. |
| [annotations.md](annotations.md) | The applicability table, the clause-by-clause legal basis, and the checklist results. |
| [open-points.md](open-points.md) | The undetermined facts, national-law gaps, and the decisions counsel or the client still has to make. |
| [implementation-requirements.md](implementation-requirements.md) | What Example Machines' product and operations teams need to build or keep doing for the drafts to hold true. |

## Corrections

One inconsistency was corrected after review. The data processing agreement listed the contact details of the
customer's site contact as data Example Machines processes on the customer's instructions, while the master
subscription terms treated the same details as Example Machines' own controller data. Example Machines decides why
and how it uses that contact for account management and support, so it is the controller for those details: the
controller is whoever decides the purposes and means of processing (Art. 4(7) Regulation (EU) 2016/679).

- The data processing agreement's scope note and Annex II no longer list the site contact's details as processor
  data and point to Section 8 of the master subscription terms instead.
- The definition of Account Data and the opening of Section 8 in the master subscription terms match that treatment.
- The implementation register lists access controls for the site contact's details separately from the Account Data
  controls, since the two rest on different legal grounds.
- A new open point asks which site-contact fields, if any, Example Machines handles on the customer's instructions.
  Those fields would go back into the data processing agreement.

The drafts are for review by a qualified lawyer. Law as of 20 October 2026.
