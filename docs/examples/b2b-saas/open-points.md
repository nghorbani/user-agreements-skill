---
title: "B2B SaaS for manufacturers: open points"
description: The undetermined facts, national-law gaps and decisions counsel still has to make.
---

*Fictional product, illustrative draft. Not legal advice.*

# Open points

Law as of: 20 October 2026. These are the undetermined facts, national-law gaps, rules not yet in
effect, and decisions counsel has to make. A qualified lawyer must review the drafts before use.

## Undetermined facts (need the client's answer)

1. **CCPA threshold.** Has Example Machines (or an affiliate) crossed one of the three CCPA thresholds: over
   USD 25,000,000 in prior-year gross revenue; buying, selling or sharing 100,000 or more consumers'
   or households' personal information a year; or deriving 50% or more of annual revenue from selling
   or sharing personal information (Cal. Civ. Code 1798.140(d))? If not, the CCPA does not apply at
   all to Spindlewise, and the conditional CCPA section of the DPA should be removed. **Affects:**
   `data-processing-agreement.md`, Part B California section; `annotations.md` applicability table row
   for CCPA.
2. **SBA small-business status.** Does Example Machines meet the US Small Business Administration's
   small-business definition? If so, Texas's TDPSA does not apply to Example Machines except for the
   sensitive-data-sale consent duty (which is not triggered here since no sale of data occurs).
   **Affects:** `data-processing-agreement.md`, Part B Texas section.
3. **German großer Unternehmer / financial-sector status.** Is Example Machines, or is any given customer, a
   großer Unternehmer under § 310 Abs. 1a BGB (250+ employees, or EUR 50 million+ revenue, or EUR 43
   million+ balance sheet, in each of the last two years), or a named financial-sector business under
   § 310 Abs. 1 BGB? This affects only a narrow carve-out (VOB/B incorporation, banking-business
   contracts) that is not expected to be relevant to a predictive-maintenance SaaS contract, but should
   be confirmed before final sign-off. **Affects:** `annotations.md` applicability table.
4. **Exact hosting arrangement.** "A cloud region in Germany" - which provider, and is it a named
   hyperscaler's Frankfurt region, a German colocation provider, or Example Machines' own infrastructure? This
   decides who the sub-processor is for Annex IV of the DPA and whether the Data Act's cloud-switching
   regime (Chapter VI) could ever apply to Example Machines' own relationship with that provider. **Affects:**
   `data-processing-agreement.md` Annex IV; `master-subscription-terms.md` Section 15;
   `backend-subprocessor-change-memo.md`.
5. **Support-ticketing vendor identity and DPF certification.** Which US company, and is it certified
   under the EU-US Data Privacy Framework? If certified, the transfer relies on the Commission's
   adequacy decision (Tier 1); if not, the Art. 46(2)(c) transfer clauses are needed (Tier 2), with the
   Module selected and Annexes completed. Until this is known, the DPA's Clause 7.8 and Annex II leave
   the mechanism unnamed. **Affects:** `data-processing-agreement.md` Annex II, Clause 7.8 note;
   `backend-subprocessor-change-memo.md`.
6. **Microenterprise/small-enterprise status (Data Act Art. 7(1)).** Is Example Machines itself a microenterprise
   or small enterprise under Commission Recommendation 2003/361/EC? The carve-out in Art. 7(1) is
   framed around an enterprise generating data "for its own product or service," which reads awkwardly
   for a vendor selling a monitoring service to third parties rather than generating data about its own
   product; this is flagged rather than resolved, since the skill's rules bar estimating this ceiling
   from unrelated facts such as headcount guesses. **Affects:** `master-subscription-terms.md` Section
   7 drafting note.
7. **Whether Spindlewise itself is a "data processing service" for Data Act Chapter VI purposes**,
   separate from Example Machines' own upstream cloud relationship. Not resolved in the drafts; Section 15 of
   the subscription terms is left as an explicit open point rather than drafted as settled.
8. **Product Liability Directive timing.** Is Spindlewise (or a relevant version of it) placed on the
   market or put into service before or after 9 December 2026? The Directive's extended liability
   regime, including for software, applies from that date; if Spindlewise was placed on the market
   earlier, the predecessor Product Liability Directive 85/374/EEC framework may apply instead, which
   this skill's references do not separately state.
9. **Which site-contact fields, if any, Example Machines handles on the Customer's instruction.** The
   site contact's name, job title, email address and phone number are Example Machines' own controller
   data under Section 8 of the Master Subscription Terms (Art. 4(7) Regulation (EU) 2016/679), because
   Example Machines decides for itself why and how it uses them, to reach someone at the Customer's
   business. If the Customer in fact instructs Example Machines to process any site-contact field for a
   purpose the Customer sets, rather than one Example Machines sets for itself, for example routing an
   automated maintenance alert to that person on the Customer's behalf, that field becomes Account Data
   for that purpose and belongs in Annex II of the DPA as processor data, not controller data.
   **Affects:** `data-processing-agreement.md` scope note and Annex II; `master-subscription-terms.md`
   Section 8; `annotations.md` row for GDPR (processor/controller rules).

## National law to verify (member states other than Germany; US states beyond the three named)

- France and Italy: these references draft at EU directive level (UCTD, e-Commerce Directive, GDPR,
  Data Act) and the EU-directive floor applies in both markets, but neither country's own national
  transposition or case law was checked beyond Germany, which this skill treats as the reference member
  state. Since the contract is B2B only, the consumer-specific transpositions that would matter most
  (France's Code de la consommation protections, Italy's Codice del Consumo) are not expected to be
  triggered, but a France- or Italy-qualified lawyer should confirm there is no French or Italian
  national-law equivalent of German AGB control (§ 307 BGB) reaching a standard-form B2B contract more
  strictly than the EU floor.
- Ohio: no comprehensive state privacy statute is merged in this skill's references, and none appears
  to exist as of the law-as-of date; confirm this remains current before relying on "federal baseline
  only" for Ohio.
- No other US state beyond California, Texas and (for comparison) New York was checked, consistent
  with the three states the client actually named.

## Rules that take effect later, or depend on a pending decision

- **BGH ruling on the German cancellation-button login question** (hearing 5 November 2026, I ZR
  272/25 and I ZR 275/25): not relevant to this engagement, since no German consumer cancellation
  button applies to a B2B contract, but noted here in case Example Machines later adds any consumer-facing
  product.
- **Data Act switching-charge sunset** (no charge permitted from 12 January 2027): relevant only if
  Section 15 (cloud switching) is in fact drafted into a final version of the contract; flagged rather
  than resolved per open point 7 above.
- **Product Liability Directive 2024/2853**: the extended regime (covering software, with the
  three-year/ten-year/twenty-five-year limitation periods) reaches a product placed on the market or
  put into service after 9 December 2026; see open point 8.

## Decisions counsel or the client has to make

- **DPA sub-processor authorisation model (Clause 7.7).** Drafted as Option 2 (general authorisation)
  for operational reasons explained in `backend-subprocessor-change-memo.md`. This is the official
  model's own choice point, not something this skill resolves for the client: if a particular customer
  negotiates for Option 1 (specific authorisation per sub-processor), that customer's copy of the DPA
  needs a different Clause 7.7 and its own Annex IV.
- **Liability cap figure (Section 11 of the subscription terms).** Left as a bracket (for example,
  "twelve months' subscription fees"); this is a commercial negotiation point, not a legal floor the
  references state.
- **Whether to add a US-style arbitration clause for the US-market customers (Ohio, Texas,
  California).** Not included by default; Section 17 of the subscription terms notes this is available
  if Example Machines wants it, following the conflicts register's decision to keep US arbitration language only
  in the US business module where chosen, never import it into an EU-facing document
  (`references/conflicts.md` C-1).
- **Renewal term length and notice period (Section 5).** No statutory floor applies to a B2B contract
  in any of the five target jurisdictions, per the references read for this engagement; the 60-day
  figure in the draft is illustrative only and should be set to Example Machines' actual intended commercial
  term.
- **Whether "hosted in Germany" should become a binding contractual commitment** rather than a
  background fact stated only in sales material. Not drafted as a binding commitment in the current
  draft (Section 7 states what data is generated and accessible, not a binding hosting-location
  promise); flagged in `backend-subprocessor-change-memo.md` since a future hosting change would be a
  bigger deal if the location is contractually promised than if it is not.
- **Whether to draft a German-language parallel version** of the subscription terms and DPA. Not done
  here; English is the working language used throughout this engagement, but a Germany-incorporated
  counterparty relationship conducted only in English carries ordinary contract-formation
  considerations a German-qualified lawyer should confirm are acceptable for AGB inclusion under § 305
  Abs. 2 BGB (reasonable opportunity to learn the content - an English-only document to a German
  business counterparty is not expected to be a problem given German B2B commercial practice, but this
  is for counsel to confirm, not assumed settled here).

## Instruments checked and found not to apply (for completeness, not drafted into the documents)

- EU Consumer Rights Directive, Unfair Commercial Practices Directive, Sale of Goods Directive, Digital
  Content Directive (consumer-specific provisions), Right to Repair Directive, Geo-blocking Regulation
  (no differential pricing/access by customer nationality identified in the facts), Digital Services
  Act, P2B Regulation, AI Act, German BGB consumer-contract chapters (§§ 312 to 312m, 327 to 327u,
  474 to 479g), German cookie-consent rule (TDDDG - Spindlewise is an operator platform, not a
  consumer-facing website described as using cookies/tracking in the facts given; flag if Example Machines' own
  marketing site uses tracking technologies, which is outside this engagement's scope), US ROSCA /
  Negative Option Rule, California Automatic Renewal Law, New York GBL 527-a, COPPA (no children
  involved), Section 230 (no third-party content hosting), CAN-SPAM (no marketing email drafting was
  requested).
