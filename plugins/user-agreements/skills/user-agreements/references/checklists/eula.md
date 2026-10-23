# EULA checklist

Law as of: 2026-10-20

For a software licence document: a shrink-wrap or click-wrap EULA, a SaaS or cloud terms of
service that licenses rather than sells access, or a mixed goods-plus-software product. Covers the
EU Software Directive and its German transposition, the Digital Content Directive, the Sale of
Goods Directive and its repair amendments, the Data Act where the product is a connected device,
and the two US federal regimes (copyright's section 117 and the DMCA safe harbor, and the
Magnuson-Moss Warranty Act) that bear on a licence or warranty document. Work the stages in order;
where a check depends on a factual classification (licence versus sale, goods versus digital
content versus digital service, consumer versus commercial end user), classify first.

## Before drafting: classify the product and the transaction

- [ ] Transaction classified as a licence or a sale: a one-off fee paired with an unlimited-duration
      right to use the copy is a sale under EU law whatever the document calls it, and exhausts the
      distribution right for that copy in the Union; a genuinely time-limited or recurring-payment
      structure is not (EU: Software Directive Art. 4(2); CJEU C-128/11 UsedSoft, paras. 45 to 49,
      61, 77)
- [ ] Whether the product is delivered as a copy the end user receives (desktop software, a
      downloaded app, firmware) or as hosted access with no copy transferred (SaaS, cloud):
      exhaustion and the end user's own-copy exceptions attach to a transferred copy under Art.
      4(2) and 5(1) (EU: Software Directive Art. 4(2), 5(1)); whether and how those provisions
      reach hosted access with no copy transferred is not covered by the references here and is
      listed under Open points to raise
- [ ] Where German law governs: whether the program was created by an employee or contractor in the
      course of their duties, which shifts the economic rights to the employer by default absent a
      contrary agreement (DE: § 69b Abs. 1, 2 UrhG)
- [ ] Goods, digital content (a single act of supply) or digital service (continuous access) sorted
      for any product that bundles software with hardware or a subscription, since each carries a
      different conformity and liability regime (EU: DCD Art. 3; SGD Art. 3(3))
- [ ] Software or firmware a device needs to perform its functions treated as a digital element of goods with digital elements: the sales contract covers it, including the seller's duty to supply conformity and security updates, not a separate digital-content contract (EU: SGD Art. 2(5)(b), 3(3), 7(3); DE: § 327a Abs. 3 BGB)
- [ ] Whether the product is a "connected product" under the Data Act (it obtains, generates or
      collects data about its use or environment and communicates that data) or a "related service"
      connected to one, since that status alone triggers a separate set of data-access and
      data-sharing duties on top of the licence itself (EU: Data Act Art. 2(5), (6))
- [ ] End user classified as a consumer (tangible personal property normally used for personal,
      family or household purposes) or a commercial buyer for Magnuson-Moss purposes, since parts
      701 and 702 of its implementing rules exclude products bought solely for commercial or
      industrial use (US: 15 U.S.C. 2301(1); 16 C.F.R. 701.1(b), 702.1(b))
- [ ] Whether any written statement in the flow (a durability claim, an uptime promise, a specified
      performance level over a stated time) crosses into a Magnuson-Moss "written warranty"; a
      statement with no tied time period, or a trade-in or free-trial policy, is not one and should
      not be labelled one (US: 15 U.S.C. 2301(6); 16 C.F.R. 700.3(a), (b))

## Licence grant

- [ ] The licence enumerates the four acts reserved to the rightholder under German law
      (reproduction, including incidental reproduction from loading, running or storing;
      translation, adaptation and alteration; distribution including rental; and public
      communication), rather than a different list (DE: § 69c Nr. 1 to 4 UrhG; EU: Software
      Directive Art. 4(1)(a) to (c) for the EU-law equivalent of the first three)
- [ ] Where the licence is drafted to avoid EU exhaustion, it relies on the deal's actual structure
      (a genuinely time-limited term or recurring payment) and not on a "non-transferable" label
      alone layered on top of a one-off fee and unlimited duration, since the label does not change
      the sale classification (EU: CJEU C-128/11 UsedSoft, paras. 49, 77, 82 to 83)
- [ ] Group or volume licensing states its minimum resellable unit clearly, since a licensee cannot
      split a group licence below its own contracted unit and resell only part of it once exhaustion
      applies (EU: CJEU C-128/11 UsedSoft, paras. 69 to 71, 86)
- [ ] Where maintenance, updates or patches are bundled, the document is clear on whether they stay
      under a severable service contract or merge permanently into the licensed copy, since merging
      extends exhaustion to the updated copy even after the maintenance term lapses (EU: CJEU
      C-128/11 UsedSoft, paras. 66 to 68)
- [ ] A reseller or licence-transfer flow provides, or technically supports, a way for the
      transferring party to render its own retained copy unusable at the time of transfer, matching
      any exhaustion the licence structure in fact triggers (EU: CJEU C-128/11 UsedSoft, paras. 70,
      78 to 79, 87)

## User exceptions the licence cannot remove

- [ ] A back-up copy necessary to secure the program's future use is not blocked by any licence term;
      such a term is void regardless of the parties' agreement (EU: Software Directive Art. 5(2),
      Art. 8 second paragraph; DE: § 69d Abs. 2, § 69g Abs. 2 UrhG)
- [ ] Observing, studying or testing the program's functioning, through acts the licensee is
      otherwise entitled to perform, to work out the underlying ideas and principles, is not blocked
      by any no-reverse-engineering or no-study clause reaching that conduct (EU: Software Directive
      Art. 5(3), Art. 8 second paragraph; DE: § 69d Abs. 3, § 69g Abs. 2 UrhG)
- [ ] Decompilation for interoperability is not blocked by the licence once the three statutory
      conditions hold together: the acts are done by a person entitled to use a copy or someone they
      authorise; the interoperability information was not already readily available; and the acts
      stay confined to the parts necessary for interoperability (EU: Software Directive Art. 6(1);
      DE: § 69e Abs. 1 Nr. 1 to 3 UrhG)
- [ ] Information obtained through decompilation is restricted, in the licence's own description of
      the exception, to achieving interoperability, passing it on only where necessary for that
      purpose, and never using it to build or market a substantially similar program (EU: Software
      Directive Art. 6(2); DE: § 69e Abs. 2 Nr. 1 to 3 UrhG)
- [ ] Only the one exception German and EU law leave open to contractual override, intended-use and
      error-correction reproduction and alteration, is narrowed or conditioned by the licence; every
      other listed exception (back-up, study and testing, decompilation, and, under German law,
      teaching and cultural-heritage uses) is left untouched, since a term reaching those is void by
      operation of the statute itself (EU: Software Directive Art. 5(1); DE: § 69d Abs. 1, 5, 7,
      § 69g Abs. 2 UrhG)
- [ ] Where the product is US-facing, a section 117 clause tracks the statute's own conditions: an
      archival copy is destroyed once possession stops being rightful, a copy made under section 117
      travels only with the original copy and only as part of a transfer of all rights, and a
      machine-repair copy is used in no other way and destroyed immediately after the work finishes
      (US: 17 U.S.C. § 117(a)(2), (b), (c)(1))

## Conformity and the quality promise

- [ ] The document states both the subjective (what the contract specifically promises) and the
      objective (what is normal for that type of good, digital content or digital service) layers of
      conformity; a clause naming only the subjective layer misstates the floor (EU: DCD Art. 6 to 8;
      SGD Art. 5 to 7)
- [ ] A deviation from objective conformity (a known limitation, a feature flag, a display or
      refurbished item) is disclosed as its own, specific item before conclusion, with its own
      express, separate acceptance distinct from general terms acceptance; a general sold-as-seen
      line does not meet this (EU: DCD Art. 8(5); SGD Art. 7(5))
- [ ] Updates, including security updates, needed to keep the product in conformity are promised for
      the contract's whole term on continuous supply, or for a reasonable expected period otherwise;
      where the end user can decline an update, the consequence of declining is disclosed first (EU:
      DCD Art. 8(2), (3); SGD Art. 7(3), (4))
- [ ] For any sale-of-goods contract concluded on or after 31 July 2026, repairability sits inside
      the objective conformity test alongside durability, functionality, compatibility and security,
      whether or not the goods are a Data Act "connected product" (EU: SGD Art. 7(1)(d) as amended)
- [ ] Continuous-supply interruptions are tracked as a conformity question: an interruption of more
      than negligible length, or one that recurs, is itself a lack of conformity; a total outage
      is not the only trigger (EU: DCD Art. 8(4) and Recital 51)
- [ ] Liability for a lack of conformity runs for at least two years from delivery, or, on
      continuous supply, for two years or the whole supply period if that runs longer (EU: DCD
      Art. 11, 12; SGD Art. 10(1), (2))
- [ ] A lack of conformity apparent within one year of delivery (or two years where the Member
      State opted in) is presumed to have existed at delivery unless the trader disproves it or the
      presumption does not fit the goods or the defect; only for continuous-supply goods with
      digital elements does the trader carry the burden of proving conformity throughout the whole
      supply period (EU: SGD Art. 11(1) to (3))
- [ ] Where the end user chooses repair as the remedy for a sale-of-goods contract concluded on or
      after 31 July 2026, the document discloses the resulting 12-month liability extension and the
      choice between repair and replacement before the remedy is provided (EU: SGD Art. 10(2a),
      13(2a))
- [ ] For US-facing warranty language, any statement meeting the Magnuson-Moss definition of a
      written warranty is captioned "full (statement of duration) warranty" or "limited warranty",
      the only two permitted designations, set apart as a prominent caption from the warranty text
      (US: 15 U.S.C. 2303(a)(1), (2); 16 C.F.R. 700.6(a))
- [ ] Where the document labels a warranty "full", it in fact meets the federal minimum standards:
      remedy within a reasonable time and without charge; no cap on implied-warranty duration; a
      consequential-damages exclusion appearing on the warranty's own face, not elsewhere; and a
      refund-or-replacement election once a reasonable number of repair attempts has failed, since
      the "full" label is deemed by law to carry these minimums whatever the drafted text says (US:
      15 U.S.C. 2304(a)(1) to (4), 2304(e))
- [ ] No written warranty is voided, or made to appear voided, for use of an unauthorised repair
      service or unauthorised parts outside what the warranty actually covers, unless the warrantor
      shows the specific defect was caused by that use (US: 16 C.F.R. 700.10(a), (c))
- [ ] No clause states that the company's own decision, a service contractor's decision or a
      designated third party's decision is final or binding in a warranty dispute, and no clause
      states that the company alone decides what counts as a defect (US: 16 C.F.R. 700.8; 15 U.S.C.
      2310(d))

## Modification, suspension and term

- [ ] A modification clause beyond what conformity requires carries no extra cost to the end user,
      states a valid reason in the contract itself, and is disclosed in clear and comprehensible
      language; where the negative effect on access or use is more than minor, advance durable-medium
      notice of the change's features and timing, plus a termination right, is given unless a
      genuine no-cost unmodified option is also offered (EU: DCD Art. 19)

## Connected-product and data duties

- [ ] Before a contract for a connected product, the document discloses, clearly and comprehensibly,
      the type, format and estimated volume of product data the product can generate, whether it
      generates data continuously and in real time, whether and for how long it stores data on-device
      or remotely, and how the user can access, retrieve or erase that data (EU: Data Act Art. 3(2)(a)
      to (d))
- [ ] Before a contract for a related service connected to the product, the provider separately
      discloses the nine Art. 3(3) items (the data it expects to collect, its own planned use and
      third-party sharing, its identity and contact point, how the user can start and stop sharing,
      the complaint right, trade-secret status, and contract duration and termination), as nine
      distinct disclosures, not one bundled notice (EU: Data Act Art. 3(3)(a) to (i))
- [ ] The product and service are designed so product data and related-service data, with
      interpreting metadata, are by default easily, securely, free of charge, and in a structured,
      machine-readable format accessible to the user, or, where direct access is not built in, made
      available on simple request without undue delay and free of charge (EU: Data Act Art. 3(1),
      4(1))
- [ ] No licence or terms clause makes it unduly difficult for the user to exercise a Data Act
      access or sharing choice, whether through non-neutral framing or through interface design that
      subverts the user's decision-making (EU: Data Act Art. 4(4))
- [ ] No clause purports to exclude, derogate from or vary, to the user's detriment, a right the
      user holds under the Data Act's access and sharing chapter; such a clause does not bind the
      user even with the user's express agreement (EU: Data Act Art. 7(2))
- [ ] A B2B data-sharing term that one enterprise unilaterally imposes on another is checked against
      the three-tier unfairness test (per-se unfair terms, presumptively unfair terms, and the
      general good-faith standard) before it is used, since an unfair term simply does not bind the
      other enterprise (EU: Data Act Art. 13(1), (3), (4), (5))
- [ ] Where the product is itself a data-processing or cloud service, the terms include the nine
      Art. 25(2) switching-contract items (a switching and porting right within the 30-day
      transitional period, exit-strategy support, termination on completed switching, a capped
      two-month notice period, the exportable-data list, any trade-secret exemption from it, a
      30-day retrieval window, a full-erasure guarantee, and the permitted switching charges), made
      available to the customer before signing (EU: Data Act Art. 25(1), (2))
- [ ] From 12 January 2027, no switching charge is imposed on a customer for switching between data
      processing services; a capped charge is permitted only up to that date (EU: Data Act Art. 29(1)
      to (3))

## Liability, remedies and dispute handling

- [ ] Annotations record that software and firmware are products under the Product Liability Directive, and that a manufacturer that keeps the ability to supply updates is not exempt for a defect caused by a software update or by a missing security update within its control; no clause limits that liability towards an injured person (EU: Directive (EU) 2024/2853 Art. 4(1), 11(2)(c), 15)
- [ ] No clause claims the DMCA safe harbor for user-stored content or linked material where the
      provider has designated an agent only on its own service, without also filing the same
      details with the Copyright Office, or the reverse; both steps are required together (US: 17
      U.S.C. § 512(c)(2))
- [ ] No clause ties a payout, revenue share or premium placement to specific user uploads the
      platform can control, where that payout would be directly attributable to infringing activity,
      since that risks forfeiting the hosting or linking safe harbor (US: 17 U.S.C. § 512(c)(1)(B),
      (d)(2))
- [ ] No clause conditions the safe harbors on the provider monitoring the service or affirmatively
      seeking facts of infringement, beyond what a consensus standard technical measure requires
      (US: 17 U.S.C. § 512(m)(1), (2))
- [ ] The notice-and-takedown and counter-notice workflow in the document states the statutory
      element lists (the six notice elements, the four counter-notice elements) and the 10-to-14
      business day restoration window, rather than a shorter or different timeline (US: 17 U.S.C.
      § 512(c)(3)(A), (g)(2), (g)(3))
- [ ] For a Magnuson-Moss informal dispute settlement mechanism named in the document, the required
      disclosures are present: the mechanism's availability, name and contact channel, whether
      resort to it is a precondition to suit, and a statement that resort is not required for
      remedies arising outside the Act (US: 16 C.F.R. 703.2(b)(1) to (4))
- [ ] A federal-court Magnuson-Moss suit threshold is not misstated as applying to a state-court
      claim: the individual and aggregate dollar floors and the 100-named-plaintiff class floor
      apply only to the federal-court route (US: 15 U.S.C. 2310(d)(3)(A) to (C))
- [ ] No individual Magnuson-Moss claim proceeds without first giving the warrantor or service
      contractor a reasonable opportunity to cure, except a class action or a claim concerning a
      warranty that uses an informal dispute mechanism already incorporated under the Act (US: 15
      U.S.C. 2310(e))

## Open points to raise

- Whether, and how, the Software Directive's exhaustion rule (Art. 4(2)) and the end user's own
  Art. 5(1) exceptions reach a hosted-access product (SaaS, cloud) with no copy transferred to the
  end user; the Software Directive text covered in references/eu/software-directive.md sets out
  the distribution right and the end-user exceptions for a transferred copy and does not address
  hosted access, so a product delivered that way needs its own legal check rather than an assumed
  answer from this file.
- Whether a no-hosting or anti-service-bureau restriction, stopping a desktop licensee from
  redeploying the software as its own hosted offering, needs to be stated as an explicit contract
  term to be enforceable, or follows from the licence grant itself; this is not covered by the
  references here and should be treated as an open point for counsel.

## Not covered here

Germany's digital-contract transposition for the Digital Content Directive beyond the UrhG software
chapter, the EU and German rules on standard contract terms control generally (see the de-agb and
eu-b2c checklists), the US DMCA transitory-communications and system-caching safe harbors beyond
what bears on a licence document, and any jurisdiction's consumer sales law for the physical-goods
side of a mixed hardware-plus-software product beyond the conformity points stated above.
