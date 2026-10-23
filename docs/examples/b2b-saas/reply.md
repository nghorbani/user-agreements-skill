---
title: "Example Machines GmbH: questions back to the client"
description: The questions the skill asked back before drafting, and the list of files handed over.
---

*Fictional product, illustrative draft. Not legal advice.*

# Reply to Example Machines GmbH

Before the drafts: a few facts I don't have yet. I drafted around reasonable assumptions anyway, and
I've marked in `open-points.md` exactly what each answer would change.

1. **Revenue and data volume, for US state privacy law.** Does Example Machines (or an affiliate) have gross
   revenue over USD 25 million, or does it buy/sell/share personal information of 100,000 or more
   consumers/households a year, or does 50% or more of its revenue come from selling or sharing
   personal information? This decides whether the CCPA applies to Spindlewise at all. Texas's
   TDPSA has no revenue threshold, so it applies regardless unless Example Machines is an SBA-defined small
   business (also needed: employee count / receipts, to check that).
2. **Ohio.** Ohio has no comprehensive consumer privacy statute yet, so nothing beyond general US
   federal law (FTC Act, COPPA if relevant, CAN-SPAM) reaches an Ohio-only customer footprint. Is
   Ohio actually a significant market, or mostly incidental? This doesn't block drafting, just
   confirms there is no Ohio-specific privacy clause to add.
3. **Company size (EU side).** Is Example Machines, or is a given customer, a "großer Unternehmer" under
   German law (250+ employees, or EUR 50 million+ revenue, or EUR 43 million+ balance sheet, in
   each of the last two years)? This affects whether German AGB law's §§ 308, 309 apply at all to a
   given customer contract (they already fall away for an ordinary business customer, but a few
   special-sector carve-outs in § 310 BGB only bite for named financial-sector or large-enterprise
   counterparties, which I assume do not apply here).
4. **Hosting location detail.** "A cloud region in Germany" - is this AWS/Azure/GCP's Frankfurt
   region, a German colocation provider, or Example Machines' own data center? This decides who the
   sub-processor is for hosting and what the DPA's sub-processor list needs to name.
5. **Support ticketing vendor.** Name of the US company running the ticketing system, and whether it
   has an EU entity or an EU-US Data Privacy Framework certification. Without this I can't confirm
   which transfer tier (adequacy under the DPF, or standard contractual clauses) actually applies;
   I've drafted the DPA to require Example Machines to name the mechanism per transfer rather than assuming one.
6. **Microenterprise/SME status.** Is Example Machines itself a microenterprise or small enterprise under
   Commission Recommendation 2003/361/EC? If so, a narrow EU Data Act carve-out (Art. 7(1)) could
   remove some of the product-data access duties for data the product generates about Example Machines' own
   product, though this carve-out is aimed at the party generating data for its own product, which
   reads awkwardly for a vendor like Example Machines - flagged as an open point rather than assumed either way.
7. **Who actually signs.** You said the signing party is always someone in the customer's purchasing
   department acting for their employer, which I've taken as confirmation this is pure B2B with no
   natural-person counterparties acting outside a trade or employment context in any of the three
   jurisdictions. If any customer could in fact be a sole proprietor buying for mixed personal/business
   use, consumer law would re-enter the picture; I have assumed this does not happen.

## What I drafted

- `master-subscription-terms.md` - the business-facing subscription agreement: formation, price and
  payment, term/renewal/cancellation, change-of-terms, warranty, liability, the connected-product
  data clause for the sensor data your machines generate, IP, confidentiality, governing law and
  dispute resolution, for Germany/France/Italy and for Ohio/Texas/California. No consumer-law
  machinery (withdrawal right, cancellation button, auto-renewal consumer disclosures) is in this
  document - none of it applies to a trader-to-trader contract, under any of the five jurisdictions'
  own tests. I flagged where German AGB content control (§ 307 BGB) still reaches a B2B clause even
  though §§ 308, 309 themselves do not.
- `data-processing-agreement.md` - built on the EU Commission's Article 28(7) standard contractual
  clauses in full (unmodified except the bracketed choices and the Annexes), plus the specific
  processor-contract terms Texas's TDPSA requires (the only one of your three US states with its own
  statutory processor-contract content; Ohio and California do not add anything beyond TDPSA and, if
  CCPA turns out to apply, the CCPA service-provider contract terms in a conditional appendix).
- `backend-subprocessor-change-memo.md` - your third question, on changing which company runs a
  backend service like the ticketing system. This isn't a document you hand to a customer; it's the
  internal procedure and the contract mechanics (sub-processor list, advance notice, objection
  window) that let you make that change without re-papering every customer contract or breaching the
  DPA.
- `annotations.md` - applicability table, clause-by-clause legal basis, and the checklist results.
- `open-points.md` - the six items above plus the law's own open points (data transfer mechanism for
  the ticketing vendor, the Ohio and other-US-state flag, the microenterprise question).
- `implementation-requirements.md` - what your product and process need to build or keep doing for
  these documents to be true: a sub-processor register, a way to export sensor data to a named third
  party on a customer's request, breach-notification timing, and the change-notice mechanics for
  contract updates.

## The quick version of your third question

Changing a backend vendor (the ticketing system today, or hosting tomorrow) is a sub-processor
change under the DPA, not a terms-of-service change. The DPA I drafted uses the general-authorisation
model: you keep a public sub-processor list, you notify customers a stated number of days before
adding or replacing one, and they get a real window to object. You do not need customer-by-customer
consent for each swap, and you do not need to amend the master subscription terms at all - only the
sub-processor list changes. See `backend-subprocessor-change-memo.md` for the full mechanics,
including what happens if a customer actually objects.

Law as of 20 October 2026. These are drafts for a lawyer to review before you use them: this is not
legal advice, and a few of the open points above (particularly the US state threshold question and
the transfer mechanism for the ticketing vendor) need an answer before the documents can be called
final.
