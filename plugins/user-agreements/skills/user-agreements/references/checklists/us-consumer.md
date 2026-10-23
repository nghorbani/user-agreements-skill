# US consumer checklist

Law as of: 2026-10-20

For a consumer-facing product sold or offered in the United States: a checkout or signup flow, a
terms of service or EULA a click or continued use is meant to form, a subscription with automatic
renewal, a warranty on a tangible consumer product, and a predispute dispute-resolution clause.
Covers the federal floor (FTC Act section 5, ROSCA and the Negative Option Rule, ESIGN and the
online-assent case law, the Federal Arbitration Act, the Magnuson-Moss Warranty Act) plus
California's Civil Code baseline on exculpatory clauses, unconscionability and the Consumers Legal
Remedies Act. State-specific auto-renewal duties (California, New York) sit in the subscription and
auto-renewal checklist; state privacy statutes sit in their own files. Work the stages in order.

## Before drafting: classify the flow and the product

- [ ] Flow classified as clickwrap (explicit "I agree" after the terms are shown or linked),
      scrollwrap (the same, but scrolling through the terms is required before the control
      activates), sign-in-wrap (no explicit click on the terms, but linked text states that a named
      action will itself constitute agreement), or browsewrap (no click at all, assent said to
      follow from mere use); a browsewrap design is not relied on to form a contract (US federal:
      case law under online-assent.md, Nguyen v. Barnes & Noble, 763 F.3d 1171, slip op. at 16)
- [ ] Product sorted as a tangible consumer product normally used for personal, family or household
      purposes, or a pure digital service or software with no physical merchandise shipped, since
      the two trigger different warranty and negative-option regimes (US federal: 15 U.S.C.
      2301(1); 16 C.F.R. 700.1(a); 16 C.F.R. 425.1(a))
- [ ] Recurring-charge pattern identified: prenotification plan, continuity plan, automatic renewal,
      or free-to-pay/nominal-fee-to-pay conversion, since federal coverage differs by pattern and by
      whether the transaction is effected on the internet (US federal: negative-option.md; 15
      U.S.C. 8403)
- [ ] Transaction confirmed as in or affecting interstate, foreign, territorial or District of
      Columbia commerce for FTC Act and arbitration-clause purposes, and as a transaction in or
      affecting interstate or foreign commerce for ESIGN purposes (US federal: 15 U.S.C. 45(a)(1);
      9 U.S.C. 1, 2; 15 U.S.C. 7001(a))
- [ ] Any predispute arbitration clause or joint-action waiver checked against the chapter 4
      carve-out for sexual assault and sexual harassment disputes before it is treated as valid for
      any dispute of that kind (US federal: 9 U.S.C. 402(a))
- [ ] California consumers identified as a distinct group wherever a liability release, waiver,
      disclaimer, or arbitration clause is used, since California's Civil Code applies its own
      object-based and unconscionability tests on top of the federal floor (US (CA): Cal. Civ. Code
      § 1668; § 1670.5; § 1751)

## Offer and checkout page

- [ ] Checkout, signup, upgrade, or data-sharing flow reviewed as a whole sequence of screens for
      its net impression on a reasonable consumer, not clause by clause, before it ships and again
      after a material redesign (US federal: FTC Act § 45(n); Bringing Dark Patterns to Light,
      Introduction, Section II)
- [ ] Every mandatory charge included in the price shown at the point a consumer first sees it; no
      mandatory fee held back until later in the flow (drip pricing), and no fee represented as
      mandatory when it is not (US federal: Bringing Dark Patterns to Light, Section II)
- [ ] Any countdown timer, stock indicator, or activity message backed by a live, accurate value at
      the moment it displays, and removed or corrected rather than looping or resetting when the
      condition changes (US federal: Bringing Dark Patterns to Light, Section I)
- [ ] Advertising, rankings, or comparison content is never formatted to look like independent
      editorial content, a neutral comparison, or an unaffiliated recommendation when it is in fact
      paid for, ranked by payment, or otherwise influenced by a relationship the consumer is not told
      about (US federal: Bringing Dark Patterns to Light, Section I)
- [ ] A toggle, binary choice, or accept/reject pair gives both options comparable visual
      prominence and avoids a double negative that leaves it unclear which position stops which
      outcome (US federal: Bringing Dark Patterns to Light, Section IV)
- [ ] No item added to a cart, plan enrollment, or other cost-bearing action taken without the
      consumer's prior, unambiguous action to choose it; a pre-checked box or a default selection
      that benefits the business does not supply that choice (US federal: Bringing Dark Patterns to
      Light, Section III)
- [ ] A lead-generation, referral, or data-sharing feature does not share information collected for a
      stated purpose or named recipient with a different buyer, or use it for a different purpose,
      without the consumer's fresh consent; a false claim of affiliation with another organization to
      induce a consumer to submit information is a separate violation on its own (US federal: Bringing
      Dark Patterns to Light, Section IV)
- [ ] For a negative-option feature sold on the internet, text disclosing all material transaction
      terms shown clearly and conspicuously before the consumer's billing information is collected
      (US federal: 15 U.S.C. 8403(1))
- [ ] For a post-transaction third-party offer under ROSCA, the description of the goods or
      services, the fact of non-affiliation with the initial merchant, and the cost disclosed
      clearly and conspicuously before billing information is collected (US federal: 15 U.S.C.
      8402(a)(1)(A) to (C))
- [ ] A liability release, limitation, disclaimer, or waiver clause does not exempt a party, even
      indirectly, from its own fraud, from willful injury to another's person or property, or from
      a violation of law whether willful or negligent (US (CA): Cal. Civ. Code § 1668)

## Consent and the order button

- [ ] A conspicuous notice of the existence of contract terms sits on the same screen as the action
      that is meant to form the contract, in a font size and color comparably prominent to the
      surrounding text, placed directly next to, not merely somewhere on, the control that
      completes the action (US federal: online-assent.md; Berman v. Freedom Fin. Network, 30 F.4th
      849, slip op. at 12 to 13)
- [ ] The assent sentence names the exact label of the control the user is about to activate, not a
      generic "I agree" with no explanatory clause, and is updated whenever that control's label
      changes (US federal: Berman, 30 F.4th 849, slip op. at 13 to 14; Chabolla v. ClassPass, 129
      F.4th 1147, slip op. at 19)
- [ ] Any hyperlink to the terms rendered in a color that contrasts with surrounding plain text and
      distinguishable as clickable, not merely underlined in the same shade as the rest of the
      sentence (US federal: Berman, 30 F.4th 849, slip op. at 14; Nguyen, 763 F.3d 1171, slip op.
      at 15 to 16)
- [ ] No unrelated question, offer, or control placed between the assent notice and the button it
      governs (US federal: Chabolla, 129 F.4th 1147, slip op. at 19 to 20)
- [ ] A multi-screen sign-up flow carries its own notice-and-assent pairing on the one screen where
      the binding action happens, not a notice shown on an earlier screen assumed to carry forward
      (US federal: Chabolla, 129 F.4th 1147, slip op. at 21)
- [ ] Any affirmative-consent checkbox for a recurring charge or negative-option feature renders
      unchecked by default; the consumer's own click or tap is the act that checks it (US federal:
      15 U.S.C. 8403(2); FTC 2021 negative-option guidance, negative-option.md)
- [ ] Express, informed consent to the negative-option feature captured separately from consent to
      the rest of the transaction, and verifiable after the fact (US federal: FTC 2021 negative-
      option guidance, negative-option.md)
- [ ] An arbitration clause that requires individual, non-class arbitration and bars an arbitrator
      from awarding relief to anyone but the named parties states separately, for a California
      consumer, that it does not require arbitration of, and does not waive in any forum, a request
      for public injunctive relief under the CLRA, the UCL, or the false advertising law (US (CA):
      Cal. Civ. Code § 1751; McGill v. Citibank, 2 Cal.5th 945, slip op. at 2, 20)

## Confirmation after the order

- [ ] A retainable acknowledgment of the offer terms, cost, frequency, and how to cancel sent
      promptly after consent, through at least the medium used to sign up (US federal: FTC 2021
      negative-option guidance, negative-option.md)
- [ ] A required consumer disclosure substituted into electronic form only after the consumer
      affirmatively consented, having first seen the four-part ESIGN statement: the paper option,
      the withdrawal right with its conditions, fees and procedure, the scope of consent, the
      procedure to update contact information, the paper-copy procedure and fee, and the hardware
      and software requirements; and only after the consumer then consented electronically in a way
      that demonstrates access to that electronic form (US federal: 15 U.S.C. 7001(c)(1)(A) to (D))
- [ ] A retained record a business is legally required to keep stored in a format that stays
      accurately reproducible and accessible, for the required period, to everyone entitled to see
      it, not merely archived in a form only the business itself can read (US federal: 15 U.S.C.
      7001(d)(1), (e))

## Warranty disclosure, before and at the point of sale

- [ ] A written warranty on a consumer product priced above the Act's thresholds fully and
      conspicuously discloses, in simple language, the warrantor's name and address, who is covered,
      what is covered, what the warrantor will do and at whose expense and for how long, what the
      consumer must do and what it costs, exceptions and exclusions, the step-by-step claim
      procedure, any informal dispute mechanism, a brief description of legal remedies, and when the
      warrantor will perform (US federal: 15 U.S.C. 2302(a)(1) to (13); 16 C.F.R. 701.3(a)(1) to
      (9))
- [ ] Warranty text made available to a prospective buyer before sale, by physical display near the
      product, by furnishing it on request with signage noting availability, or by the website
      option (clear on-product notice of the URL plus a phone number or postal address, a free hard
      copy on request, terms kept posted and accessible, and enough information to identify which
      posted terms apply) (US federal: 16 C.F.R. 702.3(a), (b)(1), (b)(2); 15 U.S.C.
      2302(b)(4)(A), (B))
- [ ] Warranty conspicuously designated either "full (statement of duration) warranty" or "limited
      warranty", as a caption or prominent title clearly set apart from the warranty text, with no
      third designation used (US federal: 15 U.S.C. 2303(a)(1), (2); 16 C.F.R. 700.6(a); see
      PW-US-FED-4 in references/prescribed-wording.md)
- [ ] Implied-warranty duration limit, if disclosed on the warranty's face, carries the required
      state-variation statement (see PW-US-FED-1); any exclusion or limitation of incidental or
      consequential damages carries the required state-variation statement, which may be combined
      with the first (see PW-US-FED-2); every warranty covered by part 701 carries the legal-rights
      statement (see PW-US-FED-3) (US federal: 16 C.F.R. 701.3(a)(7), (a)(8), (a)(9))
- [ ] If return of a registration card is a condition precedent to coverage, the warranty states so;
      if it could reasonably appear to be a condition but is not, that is disclosed too, and a full
      warranty never makes card return an actual condition of coverage (US federal: 16 C.F.R.
      701.4; 700.7(a), (b))
- [ ] Warranty coverage is never conditioned, or made to appear conditioned, on using authorized
      repair service or branded replacement parts outside what the warranty actually covers, absent a
      Commission waiver granted on the statutory showing; the warrantor may still exclude liability
      for a defect it shows was actually caused by unauthorized parts or service (US federal: 16
      C.F.R. 700.10(a), (c); 15 U.S.C. 2302(c))

## Free trials and recurring-charge disclosures

- [ ] For a free trial, gift, or intro price, how and when the price changes stated clearly, in the
      same place as the headline offer, before the consumer commits (US federal: negative-
      option.md; FTC 2021 negative-option guidance)
- [ ] A disclosure tied to a negative-option feature sits immediately next to the control that
      records consent; in an interactive electronic medium the disclosure is unavoidable, not
      behind a link or an icon the consumer must click or hover over to see (US federal: 15 U.S.C.
      8403(1); FTC 2021 negative-option guidance)
- [ ] No contract term undermines the consumer's ability to give that consent (US federal: FTC 2021
      negative-option guidance, negative-option.md)
- [ ] The billing entity's name clearly disclosed to the consumer (US federal: FTC 2021 negative-
      option guidance, negative-option.md)

## Cancellation

- [ ] A cancellation mechanism exists through at least the same medium used to sign up, is at least
      as easy to use as the sign-up method, and is wired to actually stop recurring charges once
      invoked; the mere presence of a link or number does not settle whether it works (US federal:
      FTC 2021 negative-option guidance, negative-option.md; 15 U.S.C. 8403(3))
- [ ] Where a phone line is offered for cancellation, it is staffed during normal business hours,
      answers promptly, and any voicemail is resolved within a reasonable time (US federal: FTC
      2021 negative-option guidance, negative-option.md)
- [ ] A retention offer or discount pitch inserted before completing a cancellation is limited to a
      single offer; repeated requests to hear further offers, lengthy pitches, or ignoring a
      consumer's request to decline further offers are not built into the flow (US federal: FTC
      2021 negative-option guidance, negative-option.md)
- [ ] A retention-discount flow ("Saves") is not treated as settled lawful or unlawful practice in
      compliance documentation; the Commission has asked, without deciding, whether offering one
      instead of promptly honoring a cancellation request is itself unfair or deceptive (US
      federal: negative-option.md)
- [ ] A contract-complete subscriber's written cancellation request, for a prenotification plan, is
      processed promptly on identification, with no continued billing or additional purchase made a
      precondition (US federal: 16 C.F.R. 425.1(b)(4))
- [ ] A warranty, service contract, or dispute script never states that the company's own decision,
      a service contractor's decision, or a designated third party's decision is final or binding,
      and never states that the company alone decides what counts as a defect (US federal: 16
      C.F.R. 700.8; 15 U.S.C. 2310(d))
- [ ] A warranty dispute process gives the warrantor a reasonable opportunity to cure before an
      individual suit for breach of a written or implied warranty or service contract proceeds under
      15 U.S.C. 2310(d); a class action must still give that opportunity, through notice from the
      named plaintiffs that they act on the class's behalf, unless the warranty uses an informal
      dispute settlement mechanism incorporated under 15 U.S.C. 2310(a)(3) (US federal: 15 U.S.C.
      2310(e))

## Dispute resolution and governing terms

- [ ] An arbitration clause that requires individual, bilateral arbitration and bars classwide,
      consolidated, or representative proceedings does not purport to waive, in any forum, a
      consumer's right to seek public injunctive relief under a state consumer-protection statute
      that makes that relief a core remedy (US federal: AT&T Mobility v. Concepcion, 563 U.S. 333,
      at 352; US (CA): Cal. Civ. Code § 1751; McGill, 2 Cal.5th 945, slip op. at 1, 14 to 16)
- [ ] No predispute arbitration agreement or predispute joint-action waiver, whether inside an
      arbitration clause or standing alone in a court-only document, is applied to a sexual assault
      or sexual harassment dispute arising or accruing on or after March 3, 2022 (US federal: 9
      U.S.C. 401(2), 402(a))
- [ ] No delegation clause is drafted on the assumption that it removes a court's power to decide
      chapter 4 applicability, or the arbitration agreement's own validity, for a sexual assault or
      harassment dispute; that question stays with a court regardless of the delegation clause's
      wording (US federal: 9 U.S.C. 402(b))
- [ ] A mass-arbitration or claim-batching design, if used, gives every bound claimant timely notice
      of and a genuine opportunity to be heard on any bellwether or representative proceeding whose
      result will bind that claimant, and does not give only the drafting party notice of and
      participation in every such proceeding (US federal: Heckman v. Live Nation Entertainment, 120
      F.4th 670)
- [ ] Any rule-change mechanism for the arbitration clause applies prospectively only, to disputes
      accruing after the change, and is not applied to a person who only browsed the product without
      transacting (US federal: Heckman, 120 F.4th 670)
- [ ] No clause, however labeled (release, waiver, disclaimer, limitation of liability), relies on
      its label to escape the object-based test of California's exculpatory-clause statute; what the
      clause does, not what it calls itself, controls (US (CA): Cal. Civ. Code § 1668)
- [ ] No clause requires a California consumer to waive any right or remedy the Consumers Legal
      Remedies Act gives, however the clause is worded (US (CA): Cal. Civ. Code § 1751)
- [ ] No standard-form clause presented to a California consumer, or governing a California contract
      generally, carries a feature that could be found unconscionable as a matter of law at
      formation; an adverse finding exposes the whole contract, not only the clause, to
      nonenforcement at the court's choice (US (CA): Cal. Civ. Code § 1670.5(a))
- [ ] A severability clause is reviewed each time a public-injunctive-relief carve-out or similar
      limitation is added to an arbitration clause, since whether the rest of the clause survives a
      struck provision depends on exactly what the severability language says (US (CA): McGill, 2
      Cal.5th 945, slip op. at 20 to 21)

## Records and ongoing review

- [ ] A/B testing or other design-experimentation tooling on claims, defaults, or disclosures logs
      which variant a compliance reviewer cleared, so a variant that increases conversion through a
      false or misleading impression is not shipped on that basis alone (US federal: Bringing Dark
      Patterns to Light, Introduction)
- [ ] Toggle and accept/reject components in shared design-system or component-library code enforce
      equal visual prominence between options as a reusable rule, and reject double-negative labels
      in copy review, rather than leaving prominence to each feature team (US federal: Bringing Dark
      Patterns to Light, Section IV)
- [ ] Account and subscription cancellation, and any step a consumer takes to limit data collection,
      are monitored for the number of screens, clicks, or required actions against the signup flow
      for the same feature, so a cancellation path that has grown harder than signup is caught (US
      federal: Bringing Dark Patterns to Light, Section IV)
- [ ] A negative-option enrollment record keeps the sign-up medium (online, phone, in person) so a
      compliance review can confirm cancellation is offered through at least that same medium
      without manual reconstruction (US federal: FTC 2021 negative-option guidance,
      negative-option.md)
- [ ] Warranty and returns records classify each written assurance as a written warranty, a general
      policy statement, a free-trial or return-for-credit term, or a service contract before
      publication, since each carries different disclosure duties and labels (US federal: 16 C.F.R.
      700.3(a), (b); 700.5(a), (b))

## Open points to raise

- Whether a specific font size, color pairing, or placement distance is conspicuous enough for a
  given design is a fact-intensive question the online-assent case law decides case by case; there
  is no bright-line numeric threshold in references/us-federal/online-assent.md or in the case law
  it covers, so treat this as an open point for counsel (US federal: Chabolla, 129 F.4th 1147,
  slip op. at 12).
- Whether a particular digital-only subscription with no merchandise ever shipped falls within the
  Negative Option Rule's current goods-and-merchandise scope is not settled for every product type;
  references/us-federal/negative-option.md does not resolve it, so where a product is not clearly a
  physical-shipment plan, the safer target is ROSCA plus FTC Act section 5 (US federal:
  negative-option.md).
- Whether offering a retention discount ("Saves") before processing a cancellation is itself an unfair
  or deceptive practice is an open question the Commission is actively asking about as of a 2026
  advance notice of proposed rulemaking whose comment period closed April 13, 2026; the Commission had
  not announced a decision as of this file's date (US federal: negative-option.md).
- Whether a reissued negative-option rule will restore some or all of the 2024 amendment's
  misrepresentation, disclosure, consent, or cancellation mechanics is open as of this file's date; a
  drafter building for that possibility should track the proceeding directly (US federal:
  negative-option.md).
- Whether the specific relief an arbitration or class-waiver clause would foreclose for a California
  consumer actually qualifies as public injunctive relief, as opposed to private injunctive relief
  resolving only an individual dispute, is a merits question the clause's wording alone does not
  decide (US (CA): McGill, 2 Cal.5th 945, slip op. at 5 to 6).
- Whether a specific limitation-of-liability or release clause reaches, even indirectly, one of the
  three categories California's exculpatory-clause statute bars needs a case-by-case read against what
  the clause is meant to cover in practice; the statute's object-based test cannot be answered from
  the clause text alone (US (CA): Cal. Civ. Code § 1668).
