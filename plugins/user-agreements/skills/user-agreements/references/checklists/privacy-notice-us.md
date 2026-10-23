# US privacy notice checklist

Law as of: 2026-10-20

For a privacy notice (or privacy policy) a business posts for US consumers, covering the
California statutes, the Virginia-model state privacy laws in this skill's scope (Virginia,
Colorado, Connecticut, Texas), the state matrix's summary of the other enacted or enrolled
states, and the federal children's privacy regime. Work the checks in order: which laws
apply, then notice content, then the mechanisms the notice must point to, then the children's
layer, then upkeep. A product that triggers more than one law states each duty once per
jurisdiction; where two states share a duty with different numbers (a response deadline, a cure
period), each state keeps its own line.

## Before drafting: which laws apply

- [ ] Every US state the client sells into is listed: either it has a file in these references (California, Virginia, Colorado, Connecticut, Texas, the states in `references/us-states/state-matrix.md`, and the health and biometric statutes of Washington and Illinois), or the gap is an open point for counsel; New York, for example, has no comprehensive consumer privacy statute in these references, so its privacy duties are an open point, not drafted
- [ ] California CCPA business thresholds checked: over $25,000,000 prior-year gross revenue, or
      buying, selling, or sharing 100,000 or more consumers' or households' personal information a
      year, or deriving 50% or more of revenue from selling or sharing personal information (CA:
      Cal. Civ. Code 1798.140(d))
- [ ] California CalOPPA trigger checked separately from the CCPA: it attaches to any operator of a
      commercial website or online service that collects personally identifiable information from
      a California resident, with no revenue or volume threshold of its own (CA: Bus. and Prof.
      Code § 22575(a))
- [ ] Virginia VCDPA thresholds checked: 100,000 or more consumers' personal data controlled or
      processed in a calendar year, or 25,000 or more consumers' personal data with over 50% of
      revenue from selling personal data (VA: Va. Code § 59.1-576(A))
- [ ] Colorado CPA thresholds checked: 100,000 or more consumers' personal data in a calendar year,
      or 25,000 or more consumers' personal data with revenue or a price discount from selling
      personal data; any volume of biometric identifiers or biometric data is covered for that
      processing regardless of the general threshold (CO: C.R.S. 6-1-1304(1)(a)(I), (II))
- [ ] Connecticut CTDPA thresholds checked: 100,000 or more consumers' personal data in the
      preceding calendar year, or 25,000 or more consumers' personal data with over 25% of revenue
      from selling personal data; the consumer health data rules and the two minors regimes carry
      no volume threshold (CT: Sec. 42-516, 42-526(a)(2))
- [ ] Texas TDPSA checked on its own test: it applies to any processor or seller of personal data
      that is not an SBA-defined small business, with no consumer-count or revenue threshold; a
      small business still owes the sensitive-data-sale consent duty (TX: Sec. 541.002(a),
      541.107(a))
- [ ] Other enacted or enrolled state laws screened against references/us-states/state-matrix.md
      for any additional state the product reaches; each has its own thresholds, and several (Rhode
      Island's information-sharing section, New Jersey, Delaware, Montana's minors sections) use a
      different test from the Virginia-model 100,000/25,000 pair
- [ ] Federal COPPA coverage checked independently of every state threshold above: it attaches
      where the product, or a severable portion of it, is "directed to children," or the operator
      has actual knowledge of collecting personal information from a child under 13, regardless of
      revenue or consumer count (US: 16 C.F.R. § 312.3)
- [ ] Entity- and data-level exemptions checked before applying any duty below: each statute carries
      its own exemption list (financial institutions and GLBA data, HIPAA-covered entities,
      nonprofits in most but not all states, higher-education institutions, FCRA consumer-report
      data, FERPA education records, employment-context data), and a business relying on one should
      be able to name the specific ground rather than assert a blanket exemption (CA: Cal. Civ. Code
      1798.145; VA: Va. Code § 59.1-576(B), (C); CO: C.R.S. 6-1-1304(2); CT: Sec. 42-517; TX: Sec.
      541.002(b), 541.003)

## Notice content: what every covered notice states

- [ ] Categories of personal data (or personal information) processed or collected, paired with the
      purpose for each category rather than one catch-all purpose (CA: Cal. Civ. Code
      1798.100(a)(1); CA: 11 CCR 7011(e)(1)(A); VA: Va. Code § 59.1-578(C); CO: C.R.S. 6-1-1308(1)(a); CT:
      Sec. 42-520(c); TX: Sec. 541.102(a))
- [ ] Retention period for each category, or the criteria used to set it (CA: Cal. Civ. Code
      1798.100(a)(3))
- [ ] Categories of sources the data comes from (CA: 11 CCR 7011(e)(1)(B))
- [ ] Categories of third parties, or specific third-party recipients and the purpose of each
      disclosure, that personal data is shared with, or a statement that none are (CA: Cal. Civ.
      Code 1798.130(a)(5); 11 CCR 7011(e)(1)(D), (E), (H); VA: Va. Code § 59.1-578(C); CO: C.R.S. 6-1-1308(1)(a); CT:
      Sec. 42-520(c); TX: Sec. 541.102(a))
- [ ] Whether, and to whom, personal data is sold or shared, or a statement that none is (CA: Cal.
      Civ. Code 1798.130(a)(5); 11 CCR 7011(e)(1)(D), (E))
- [ ] Whether sensitive personal information is used or disclosed outside the statutorily listed
      authorized purposes (CA: 11 CCR 7011(e)(1)(J))
- [ ] Sensitive-data category list, including precise geolocation data where collected, matching the
      state's own sensitive-data definition (CO: C.R.S. 6-1-1308(1), 6-1-1303(24)(e); TX: Sec.
      541.102(a))
- [ ] Explanation of each consumer right and how to exercise it, including the appeal process for a
      declined request, with contact information for the request channel (CA: Cal. Civ. Code
      1798.130(a)(5); 11 CCR 7011(e)(2), (3); VA: Va. Code § 59.1-578(C), (E); CO: C.R.S. 6-1-1308(1)(a); CT:
      Sec. 42-520(c); TX: Sec. 541.102(a))
- [ ] A contact channel matching how the business primarily interacts with consumers, or an active
      email address or other online contact mechanism (CA: 11 CCR 7011(e)(3)(J); CT: Sec. 42-520(c))
- [ ] Date of the notice's last update, and a schedule to update at least every 12 months (CA: Cal.
      Civ. Code 1798.130(a)(5); 11 CCR 7011(e)(4))
- [ ] CalOPPA's own content items, additive to the CCPA items above: how the operator responds to
      browser do-not-track signals or similar cross-site choice mechanisms (only if the operator
      engages in that collection; a clear, conspicuous hyperlink to an explanation of the program or
      protocol satisfies this in place of writing it into the policy text), whether other parties
      may collect personal data about a consumer's activity over time and across sites through the
      operator's product, the operator's process (if any) for a consumer to review and request
      changes to their own collected data, how the operator notifies consumers of material policy
      changes, and the policy's effective date (CA: Bus. and Prof. Code § 22575(b)(1) to (7))
- [ ] Virginia-model baseline content: categories of personal data processed, purpose of
      processing, how to exercise and appeal rights, categories of personal data shared with third
      parties if any, categories of those third parties if any (VA: Va. Code § 59.1-578(C); CO:
      C.R.S. 6-1-1308(1)(a); CT: Sec. 42-520(c); TX: Sec. 541.102(a))
- [ ] Where personal data is sold to third parties, or processed for targeted advertising: a clear
      and conspicuous disclosure of that processing and how to opt out, both inside the notice and,
      for California and Colorado, in a separate, readily accessible location outside it too (CA:
      Cal. Civ. Code 1798.135(a); VA: Va. Code § 59.1-578(D); CO: C.R.S. 6-1-1308(1)(b),
      6-1-1306(1)(a)(III); CT: Sec. 42-520(d); TX: Sec. 541.103)
- [ ] Texas-specific point-of-sale notices, verbatim and posted in the same location and manner as
      the privacy notice itself, not merely referenced from it: see references/prescribed-wording.md
      (TX: Sec. 541.102(b), (c))
- [ ] Colorado's granular content list under its rules: processing practices described by data
      category and purpose at the granular level the rule requires (with worked examples such as
      "contact information" or "medical data"), whether data for each purpose is sold, used for
      targeted advertising, or used for significant-effect profiling, granular third-party category
      descriptions, the authentication process used, and, where sensitive-data inferences are
      deleted within 24 hours instead of gated by consent, a description of that practice and its
      retention and deletion timeline (CO: 4 CCR 904-3 Rule 6.03(A))
- [ ] Colorado's automated-decision disclosure where the business profiles consumers toward a
      decision with legal or similarly significant effects: which decisions are covered, the
      categories of data processed for it, a plain-language explanation of the profiling logic and
      of how it feeds the decision including human involvement, whether it has been evaluated for
      accuracy, fairness, or bias and the outcome, the benefits and potential consequences, and how
      to opt out (CO: 4 CCR 904-3 Rule 9.03(A), (B))

## Rights the notice points to, and the mechanisms behind them

- [ ] At least two designated request methods for delete, correct, or know requests (minimum a
      toll-free number, or an email address alone for a qualifying online-only business), and at
      least two for opt-out and limit requests with one matching the business's primary channel (CA:
      Cal. Civ. Code 1798.130(a)(1); 11 CCR 7020(a) to (c), 7026(a), 7027(b) to (c))
- [ ] A named, secure request channel fitted to how consumers normally interact with the business,
      for the Virginia-model rights: confirm and access, correct, delete, portability, and opt out
      of targeted advertising, sale, and significant-effect profiling (VA: Va. Code §
      59.1-577(A), 59.1-578(E); CO: C.R.S. 6-1-1306(1); CT: Sec. 42-518(a), (b), 42-520(e)(1); TX:
      Sec. 541.051(b), 541.055(a))
- [ ] No new account required to exercise any right; use of an existing account may still be
      required (VA: Va. Code § 59.1-578(E); CO: C.R.S. 6-1-1306(1); CT: Sec. 42-520(e)(1); TX: Sec.
      541.055(b); CA: Cal. Civ. Code 1798.130(a)(2)(A); 11 CCR 7026(c), 7027(d))
- [ ] Response deadline stated or built into the pipeline: California acknowledges within 10
      business days and substantively responds within 45 calendar days (extendable once by 45 more
      days with notice); Virginia, Colorado, Connecticut, and Texas each respond within 45 days of
      receipt, extendable once by 45 more days with notice and reason given within the initial
      window (CA: Cal. Civ. Code 1798.130(a)(2)(A); 11 CCR 7021(a) to (b); VA: Va. Code §
      59.1-577(B)(1); CO: C.R.S. 6-1-1306(2); CT: Sec. 42-518(c)(1); TX: Sec. 541.052(b))
- [ ] A decline notice, within the same response window, stating the reason and the appeal
      instructions (VA: Va. Code § 59.1-577(B)(2); CO: C.R.S. 6-1-1306(2); CT: Sec. 42-518(c)(2); TX:
      Sec. 541.052(c))
- [ ] Requests free of charge: at least twice a year per consumer in California, once per 12 months
      in Virginia, Colorado, Connecticut, and Texas, each with a manifestly unfounded, excessive, or
      repetitive exception the business bears the burden of showing (CA: Cal. Civ. Code
      1798.130(a)(1); VA: Va. Code § 59.1-577(B)(3); CO: C.R.S. 6-1-1306(2); CT: Sec. 42-518(c)(3);
      TX: Sec. 541.052(d))
- [ ] No fee charged for authenticating a request in Colorado (CO: 4 CCR 904-3 Rule 4.08(E))
- [ ] An appeal process for a declined request: conspicuous, similar in form to the request channel,
      decided within 60 days with written reasons, and, on a denied appeal, a route to the state
      attorney general (VA: Va. Code § 59.1-577(C); CO: C.R.S. 6-1-1306(3) (extendable by 60 more
      days with notice); CT: Sec. 42-518(d); TX: Sec. 541.053)
- [ ] A California homepage link titled exactly "Do Not Sell or Share My Personal Information" and
      one titled exactly "Limit the Use of My Sensitive Personal Information," or a single
      Alternative Opt-out Link with the prescribed title and icon in their place; a business need
      not post either if it honors a compliant opt-out preference signal frictionlessly instead and
      discloses that in the privacy policy (CA: Cal. Civ. Code 1798.135(a)(1) to (3), 1798.135(b);
      11 CCR 7013(c), 7014(c), 7015(a) to (b), 7025(e) to (g))
- [ ] A clear and conspicuous opt-out link or page for targeted advertising and sale in Virginia,
      Colorado, Connecticut, and Texas; Colorado's attorney general accepts specific link-text
      examples, see references/prescribed-wording.md (VA: Va. Code § 59.1-578(D); CO: C.R.S.
      6-1-1306(1)(a)(III); 4 CCR 904-3 Rule 4.03(B)(3); CT: Sec. 42-520(e)(1)(A)(i); TX: Sec.
      541.055(e), (f), 541.103)
- [ ] Opt-out and limit requests, and California's opt-out of sale/sharing, honored within the
      statutory window and cascaded to every third party, service provider, or contractor already
      holding the data (CA: 11 CCR 7022(b) to (c), 7026(f), 7027(g); VA: Va. Code § 59.1-577(A); CO:
      C.R.S. 6-1-1306(1)(a); CT: Sec. 42-518(a); TX: Sec. 541.051(b))
- [ ] Universal opt-out preference signal recognized: required in California (any commonly
      recognized format), Colorado (from 2024-07-01, to attorney general technical specifications),
      and Connecticut (from 2025-01-01, meeting five listed conditions); Virginia and Texas carry no
      statutory signal-recognition duty, though Texas bars a default-based opt-out mechanism (CA:
      Cal. Civ. Code 1798.135(b); 11 CCR 7025(c) to (g); CO: C.R.S. 6-1-1306(1)(a)(IV)(B); 4 CCR
      904-3 Rule 5.08(A)(1); CT: Sec. 42-520(e)(1)(A)(ii); TX: Sec. 541.055(f))
- [ ] Connecticut: a conflict between a universal opt-out signal and a consumer's existing
      controller-specific setting, or loyalty-program participation, is resolved in favor of
      honoring the signal; the business may flag the conflict and offer a confirmation choice, but
      compliance with the signal does not wait on that confirmation (CT: Sec. 42-520(e)(1)(B)).
      Colorado's closest analogue runs the other way: a consumer's affirmative, separately
      disclosed consent to targeted advertising or sale, given through a web page or app, takes
      precedence over a universal opt-out signal already in effect; Colorado states no flag-and-
      confirm step (CO: C.R.S. 6-1-1306(1)(a)(IV)(C))
- [ ] Authorized-agent opt-out requests recognized where the business can verify, with commercially
      reasonable effort, the consumer's identity and the agent's authority (CT: Sec. 42-519; TX:
      Sec. 541.055(e); CA: 11 CCR 7063)
- [ ] Identity verification tiered to request sensitivity in California: no verification for
      opt-out, limit, or ADMT opt-out requests; a reasonable degree of certainty for requests to know
      categories; a reasonably high degree of certainty, including a signed declaration, for
      requests to know specific pieces or access ADMT (CA: 11 CCR 7060(b), 7062(b), (c))
- [ ] No price, service, or quality difference tied to exercising a right unless reasonably related
      to the value the consumer's data provides, documented and calculated in good faith; a
      different price or quality tied to voluntary participation in a bona fide loyalty, rewards, or
      discount program is not itself discrimination (CA: Cal. Civ. Code 1798.125(a); 11 CCR
      7080(a) to (c); VA: Va. Code § 59.1-578(A)(4); CO: C.R.S. 6-1-1306(1), 1308(1)(d); CT: Sec.
      42-520(a), (b); TX: Sec. 541.101(b)(3), (c))

## Sensitive data and consent

- [ ] Sensitive data category list matches the state's own definition; most of this skill's states
      treat racial or ethnic origin, religious belief, health diagnosis, sexual orientation,
      citizenship or immigration status, genetic or uniquely-identifying biometric data, precise
      geolocation, and a known child's data as sensitive (CA: Cal. Civ. Code 1798.140(ae); VA: Va.
      Code § 59.1-575; CO: C.R.S. 6-1-1303(24); CT: Sec. 42-515(38); TX: Sec. 541.001(29))
- [ ] Consent gate for sensitive data: opt-in consent required before processing in Virginia,
      Colorado, Connecticut, and Texas; California instead gives consumers a right to limit use of
      sensitive personal information to specified purposes rather than a general consent gate (CA:
      Cal. Civ. Code 1798.121; VA: Va. Code § 59.1-578(A)(5); CO: C.R.S. 6-1-1308(7); CT: Sec.
      42-520(a)(4); TX: Sec. 541.101(b)(4))
- [ ] Consent required before selling sensitive data specifically in Colorado (from the amendment
      approved 2025-05-23) and in Connecticut's consumer health data rules; no sale of sensitive
      personal information without complying with the general CCPA consumer-rights framework in
      California (CO: C.R.S. 6-1-1308(7), as amended; CT: Sec. 42-526(a)(1)(D))
- [ ] No sale or offer of precise geolocation data at all in Virginia (VA: Va. Code § 59.1-578(A)(6))
- [ ] Before collecting a biometric identifier in Colorado: a clear, reasonably accessible
      disclosure that collection is occurring, the specific purpose and retention length, and
      whether and why the identifier will be disclosed to a processor (CO: C.R.S. 6-1-1314(4)(a))
- [ ] A written, public biometric retention policy in Colorado, setting a retention schedule and
      deletion guidelines, separate from the pre-collection disclosure above (CO: C.R.S.
      6-1-1314(2))
- [ ] No consent built on a bundled general terms-of-use or privacy-policy checkbox covering
      unrelated processing, on hovering, muting, pausing, or closing content, or on a dark pattern;
      none of these meets the statutory definition of consent in any of these states (CA: Cal. Civ.
      Code 1798.140(h); 11 CCR 7004(a)(4)(B) to (C); VA: inherited through the Virginia-model
      definition structure; CO: C.R.S. 6-1-1303(5)(a) to (c); CT: Sec. 42-515(7); TX: Sec.
      541.001(6)(A) to (C))
- [ ] No choice architecture that confuses or impairs the consumer's choice: unequal size or
      prominence between options, an "Accept All" easier than "Decline All", an extra step placed
      only on the privacy-protective path, a pre-selected default, or treating silence or continued
      use as consent (CA: 11 CCR 7004(a)(2) to (3), (b) to (c); CO: 4 CCR 904-3 Rule 7.03(B)(2),
      7.10(A))

## Children's data: COPPA and the state age gates

- [ ] Directed-to-children classification run per portion of the product, not as one whole-product
      flag, plus an actual-knowledge check for collecting from a known children's site (US: 16
      C.F.R. § 312.2, 312.3)
- [ ] Direct notice to the parent precedes any collection, use, or disclosure of a child's personal
      information, in the variant matching the purpose (general consent-seeking, voluntary
      participation, repeated contact, or child safety), each carrying a hyperlink to the online
      notice (US: 16 C.F.R. § 312.4(c)(1) to (4))
- [ ] Posted online notice sits on the home or landing page and at every point of collection, naming
      every operator or a designated contact operator, what is collected and why, third-party
      recipients by name or category and the purpose of disclosure, and the written retention policy
      (US: 16 C.F.R. § 312.4(d))
- [ ] Verifiable parental consent obtained before collecting, using, or disclosing a child's
      personal information, including before a material change to practices already consented to;
      separate consent for non-integral third-party disclosure (consideration, advertising, or AI
      training or development are never integral) (US: 16 C.F.R. § 312.5(a)(1), (2))
- [ ] Parent-facing standing rights built in: a description of data categories collected, an ongoing
      opt-out and deletion control, and a means to review collected information that is not unduly
      burdensome, each conditioned on confirming the requestor is the child's parent (US: 16 C.F.R.
      § 312.6(a))
- [ ] Written, public data retention policy stating the purpose, business need, and deletion
      timeframe for each category of children's data (US: 16 C.F.R. § 312.10)
- [ ] California's under-16 consent chain for selling or sharing a minor's data layered on top of
      COPPA: documented parental consent for a known under-13 consumer, a two-step opt-in for a
      known 13-to-under-16 consumer, each followed by telling the parent or consumer about the
      ongoing opt-out right (CA: Cal. Civ. Code 1798.120(c); 11 CCR 7070(a) to (b), 7071(a) to (b))
- [ ] State known-child and minor activity limits layered on top of COPPA where the product reaches
      a known child or minor: no targeted advertising, sale, or significant-effect profiling absent
      consent (the child's parent's, or, for an older minor in several states, the minor's own); no
      processing beyond the disclosed or compatible purpose; limits on precise geolocation
      collection with a signal to the minor during collection (VA: Va. Code § 59.1-578(F),
      59.1-577.1; CO: C.R.S. 6-1-1308.5; CT: Sec. 42-529a)
- [ ] Virginia's and Connecticut's social-media-specific minor duties checked separately if the
      product is a qualifying social media platform: Virginia's one-hour daily use cap for a minor
      under 16 absent parental consent to adjust it; Connecticut's account unpublish (15 business
      days) and delete (45 business days) request channel for a minor or a parent of a minor under
      16 (VA: Va. Code § 59.1-577.1(B) to (D); CT: Sec. 42-528(b))

## Upkeep and records

- [ ] Privacy policy updated, and its stated last-update date refreshed, at least every 12 months in
      California (CA: Cal. Civ. Code 1798.130(a)(5); 11 CCR 7011(e))
- [ ] Notice of a material change given through a channel the business regularly uses, for Colorado;
      where a material change amounts to a secondary use of already-collected data, fresh consent is
      obtained for that secondary use before the change applies to that data (CO: 4 CCR 904-3 Rule
      6.04)
- [ ] A fresh California Notice at Collection given whenever collection expands to a new category or
      an incompatible new purpose, at the point of collection; if no such notice is given, the
      business does not collect the information (CA: 11 CCR 7012(c), (d))
- [ ] A California Notice of Financial Incentive wherever a price or service difference is tied to
      data, covering the incentive, its material terms, how to opt in, the right to withdraw, and
      the value calculation (CA: Cal. Civ. Code 1798.125(b)(1) to (2); 11 CCR 7016(d))
- [ ] A California Pre-use Notice before using automated decisionmaking technology for a significant
      decision (financial or lending services, housing, education, employment or contracting
      opportunities, or healthcare), covering the specific purpose, the opt-out or appeal route, the
      access right, a non-retaliation statement, and, at least behind a link, how the technology
      reaches its output (CA: 11 CCR 7220(b) to (d))
- [ ] Request-handling records kept: at least 24 months in California and Colorado, covering the
      request date, nature, submission method, response date and nature, the basis for any denial,
      and, in Colorado, the existence and resolution of any appeal (CA: 11 CCR 7101(a) to (d); CO: 4
      CCR 904-3 Rule 6.11(A))
- [ ] COPPA written information security program maintained, with a designated coordinator, an
      at-least-annual risk assessment, sized safeguards, and vendor onboarding checks before another
      party collects or maintains children's data on the product's behalf (US: 16 C.F.R. § 312.8(b),
      (c))
- [ ] Data protection assessment conducted and kept, before or during the processing, for targeted
      advertising, sale, risky profiling, sensitive-data processing, or any other heightened-risk
      processing, in Virginia, Colorado, Connecticut, and Texas (VA: Va. Code § 59.1-580(A), (C); CO:
      C.R.S. 6-1-1309; CT: Sec. 42-522; TX: Sec. 541.105(a), (b))
- [ ] California's heightened-risk-processing businesses run the annual cybersecurity audit and
      risk-assessment duties on the revenue-tiered phase-in schedule, with the Agency submission and
      signed attestation; see references/us-states/ca-ccpa.md Dates for the exact deadlines (CA: 11
      CCR 7120 to 7157)
- [ ] De-identified or anonymized data described as such only where the three-part test is met in
      every state checked: reasonable measures against re-association, a public commitment not to
      re-identify, and a contractual flow-down to recipients binding them to the same (CA: Cal. Civ.
      Code 1798.140(m); VA: Va. Code § 59.1-581(A); CO: C.R.S. 6-1-1303(11); CT: Sec. 42-523(a); TX:
      Sec. 541.106(a))
- [ ] Processor or service-provider contracts in place wherever personal data is sold, shared, or
      disclosed, each with the subdivision's own required terms (purpose limits, confidentiality,
      end-of-service deletion or return, audit cooperation, subcontractor flow-down) (CA: Cal. Civ.
      Code 1798.100(d); VA: Va. Code § 59.1-579(B); CO: C.R.S. 6-1-1305(3) to (5); CT: Sec.
      42-521(b); TX: Sec. 541.104(b), (c))

## What the notice must not say

- [ ] No clause waiving or limiting a consumer right, remedy, or enforcement mechanism under any of
      these state laws, including a representative-action or arbitration clause reaching them; each
      state declares such a clause void and against public policy (CA: Cal. Civ. Code 1798.192; VA:
      Va. Code § 59.1-578(B); TX: Sec. 541.054)
- [ ] No claim of a private right of action under the Virginia-model statutes: none exists under
      Virginia, Colorado, Connecticut, or Texas law, or under any other law on that account (VA: Va.
      Code § 59.1-584; CO: C.R.S. 6-1-1310(1), 6-1-1311(1)(b); CT: Sec. 42-525(d), 42-528(d),
      42-529e(a); TX: Sec. 541.156)
- [ ] No local-ordinance compliance clause for a topic these state laws preempt: California preempts
      local privacy-policy-posting rules under CalOPPA, Colorado preempts local privacy ordinances,
      Texas preempts local ordinances adding processing duties (CA: Bus. and Prof. Code § 22578; CO:
      C.R.S. 6-1-1312; TX: Sec. 541.205)
- [ ] No describing a biometric identifier's use as saleable in Colorado: a clause permitting sale,
      lease, or trade of a biometric identifier with any entity is absolute and cannot be waived by
      consent (CO: C.R.S. 6-1-1314(4)(b)(I))
- [ ] No paraphrase in place of Texas's exact sensitive- and biometric-data-sale notices; a looser
      description does not meet the statute even if it conveys the same substance (TX: Sec.
      541.102(b), (c))

## Open points to raise

- Whether the product has crossed any applicable state's volume, revenue, or revenue-share
  threshold, since every state duty in this file depends on that answer, and the tests differ by
  state (CA: Cal. Civ. Code 1798.140(d); VA: Va. Code § 59.1-576(A); CO: C.R.S. 6-1-1304(1)(a);
  CT: Sec. 42-516; TX: Sec. 541.002(a)).
- Whether any feature meets California's "significant decision" test for automated decisionmaking
  technology, which triggers the Pre-use Notice, opt-out, access, and risk-assessment duties (CA:
  11 CCR 7001(ddd), 7200(a)).
- Whether the business actually knows, or willfully disregards, that a consumer is a minor or
  child under any of these states' tests, since several duties turn on that knowledge standard
  without a bright line in the statute text (VA, CO, CT state matrix rows).
- Whether a specific product's content, audience evidence, and advertising mix cross COPPA's
  "directed to children" multi-factor threshold; the Commission decides this case by case (US: 16
  C.F.R. § 312.2 "Website or online service directed to children").
- Whether a given third-party disclosure to a minor's data recipient is "integral to the website or
  online service" for COPPA's separate-consent requirement, a line the Commission draws case by
  case beyond confirming consideration, advertising, and AI training are never integral (US: 90 FR
  16918, discussing 16 C.F.R. § 312.5(a)(2)).
- Whether the product reaches any additional state beyond California, Virginia, Colorado,
  Connecticut, and Texas; references/us-states/state-matrix.md lists the thresholds and notable
  duties for the other enacted or enrolled states, several of which (Delaware, New Jersey, Montana,
  Maryland) use a materially different threshold or sensitive-data rule from the Virginia-model
  states covered in full here.

## Not covered here

The US federal baseline outside COPPA (the FTC Act's unfairness and deception authority over dark
patterns, the FTC's dot-com disclosures guidance), state laws other than California, Virginia,
Colorado, Connecticut, and Texas beyond the summary in references/us-states/state-matrix.md, and
EU or German notice duties under the GDPR. Those come from separate files in this skill.
