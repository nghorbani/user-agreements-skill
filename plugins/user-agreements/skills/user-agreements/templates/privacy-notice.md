# Privacy notice

Law as of: 2026-10-20

A fill-in template for the privacy notice (privacy policy) a controller publishes for GDPR,
German, and US state-law coverage together: one document with modules for the law each visitor
falls under, built on `references/checklists/privacy-notice-gdpr.md` and
`references/checklists/privacy-notice-us.md`. Where the two checklists cover a point
differently, this template keeps the stricter wording in the shared sections and splits a dedicated
module where the content genuinely diverges (notice timing, the rights list, the opt-out
mechanics). It does not cover the cookie banner itself; pair this notice with
`templates/cookie-notice.md` for the device-level consent flow that normally sits beside it.

## How to fill this in

- Classify every processing activity before drafting a line of text. List each purpose
  separately, with its own Art. 6(1) legal basis named by letter (consent, contract necessity,
  legal obligation, vital interest, public task, legitimate interest), and its own US category and
  purpose pairing; a blanket purpose covering several activities, or a basis picked because nothing
  else fits, fails both checklists (EU: Art. 5(1)(a), (b), 6(1) GDPR; CA: Cal. Civ. Code
  1798.100(a)(1)). Flag any Art. 9 special-category data and any sensitive-data category under the
  US state tests separately from this classification; they need their own ground, not a shared one
  with the ordinary processing around them (EU: Art. 9(1), (2) GDPR; CO: C.R.S. 6-1-1308(1),
  6-1-1303(24)(e)).
- Decide per activity whether the data came from the data subject or was obtained elsewhere; the
  EU content list and timing differ by source, and so does the German BDSG ground that can narrow
  the notice duty (EU: Art. 13(1), Art. 14(1) GDPR; DE: § 32 Abs. 1, § 33 Abs. 1 BDSG). Record the
  specific source, or, only where naming it genuinely proves impossible, its type and sector
  (EU: Art. 14(2)(f) GDPR).
- Check which US state thresholds the business actually crosses before filling the US module in
  full; every state duty in that module depends on the business's revenue, volume, or revenue-share
  figures, and CalOPPA's own trigger has no threshold at all (CA: Cal. Civ. Code 1798.140(d); Bus.
  and Prof. Code § 22575(a); VA: Va. Code § 59.1-576(A); CO: C.R.S. 6-1-1304(1)(a); CT: Sec. 42-516;
  TX: Sec. 541.002(a)). Where the product reaches a state beyond California, Virginia, Colorado,
  Connecticut, and Texas, check `references/us-states/state-matrix.md` for that state's own
  thresholds before relying on the Virginia-model wording below as a stand-in.
- Write every purpose, recipient, and retention statement in concrete terms. An open-ended
  qualifier is only usable where the controller can show why it could not be avoided (EU: Art.
  12(1), Art. 13(1)(c) GDPR). A bare line saying data is kept as long as necessary, with no further
  detail, does not meet the GDPR floor; give a period or the criteria that set one (EU: Art.
  13(2)(a) GDPR; CA: Cal. Civ. Code 1798.100(a)(3)).
- Layer the notice rather than publishing one long undifferentiated page. A first layer, reachable
  at the point of collection itself, rather than only inside a linked document, states the purposes, the
  controller's identity, the rights available, and whichever part of the processing would most
  surprise the person reading it; the full detail lives one layer down. Routine, expected processing
  belongs in the deeper layer, not the first one (EU: Art. 12(1) GDPR). A device with no screen
  needs its own notice channel, such as a URL printed on packaging or an audio alert where the
  device has audio output.
- Keep a real, working control attached to every practice the notice describes, rather than
  stopping at a statement of fact: a link to the rights-request channel next to the rights list, a
  link to the opt-out mechanism next to the sale or sharing disclosure, a link to the cookie
  settings next to the tracking-technology line. A notice that only describes a practice without a
  way to act on it does not meet the purpose the layering and control duties above serve.
- Give the right to lodge a complaint, the right to withdraw consent, and the direct-marketing
  objection their own visible lines; none of them may be folded into a general rights paragraph (EU:
  Art. 13(2)(c), (d), Art. 21(4) GDPR). Use the fixed heading at PW-EU-11 for the erasure-rights
  section, in the language the notice is written in.
- For the US module, use at minimum two designated request methods for delete, correct, or know
  requests in California, and a channel matching the business's primary consumer contact method for
  the Virginia-model states; building a new-account requirement in front of any request is not
  permitted anywhere in this module (CA: Cal. Civ. Code 1798.130(a)(1); 11 CCR 7020(a) to (c); VA:
  Va. Code § 59.1-578(E)).
- Post the California opt-out links using the exact titles at PW-US-CA-3, or the single
  alternative link at PW-US-CA-4 with its icon, only where the business actually sells, shares, or
  uses sensitive personal information beyond the statute's authorized purposes; where the business
  instead honors a compliant opt-out preference signal frictionlessly, state that in the notice in
  place of posting the links (CA: Cal. Civ. Code 1798.135(a), (b); 11 CCR 7025(e) to (g)). Pick one
  of the Colorado link-text examples at PW-US-CO-1 for the Colorado opt-out link, or reuse the
  California link text where it also satisfies Colorado's own clear-understanding-of-purpose test.
- Where the business sells sensitive personal data or biometric data under Texas law, post PW-US-TX-1
  or PW-US-TX-2 (or both together, where both apply) in the same location and the same manner as the
  rest of the privacy notice; a paraphrase of either sentence does not meet the statute even where it
  conveys the same substance (TX: Sec. 541.102(b), (c)).
- Where the product is directed to children, or the operator has actual knowledge of collecting
  from a child under 13, run the COPPA module alongside the GDPR Art. 8 and the state minor-data
  modules; none of the three displaces the others, and the directed-to-children classification runs
  per portion of the product, not as one whole-product flag (US: 16 C.F.R. § 312.2, 312.3; EU: Art.
  8(1), (2) GDPR).
- When a change to the processing itself is material (a new purpose, a wider recipient category, a
  new third-country transfer, a changed controller identity, or a changed rights-exercise process),
  send an active, dedicated notification well before the change takes effect, separate from any
  marketing content; a clause telling the reader to check back periodically for updates does not
  substitute for that notification (EU: Art. 12(1), Art. 5(1)(a), (b) GDPR). A typo fix or a
  stylistic correction is not a material change and needs no such notice. Refresh the notice's
  stated last-update date, and actually review the notice, at least every 12 months for the
  California module regardless of whether anything material changed (CA: Cal. Civ. Code
  1798.130(a)(5); 11 CCR 7011(e)(4)).
- Translate the notice for every language the product actually ships in; a notice available only in
  a language the audience does not use fails the plain-language standard as much as a notice written
  in dense legal prose would.
- Check every citation in this template against the cut legal text before relying on it; the
  citations above were checked at the time this template was written.

## Module: who we are and how to reach us

Who is responsible for your data: [controller legal name], [postal address], [email address],
[phone number, where the business primarily reaches consumers by phone].

Where a representative is designated under Art. 27 GDPR, name that representative and give their
contact details here as well.

Where a data protection officer is appointed, add a line naming how to reach them, and omit this
paragraph entirely where no DPO is appointed (EU: Art. 13(1)(b), Art. 14(1)(b) GDPR).

## Module: what we collect, why, and for how long (first layer)

Use this as the short, top-layer summary. Name only the purposes and any part of the processing
that would surprise the reader; push the full per-activity detail to the module below.

The short version: state the two or three purposes most visible to this audience or most likely to
surprise it, for example processing an order and payment, showing ads based on activity on other
sites, or building a behavioral profile for recommendations. State plainly any third-country
transfer, sale, or sharing that is not obvious from the product's own purpose. Point to the full
detail below, including every legal basis, every recipient, and how long each category is kept,
and link directly to the rights-request channel and to the opt-out or consent-withdrawal
mechanism, where either applies.

## Module: what we collect, why, and for how long (full detail)

Repeat this block once per distinct processing activity; do not group unrelated purposes under one
entry.

Name of the activity (for example, processing an order): state what is collected for this activity.

Where it comes from: the data subject directly, or, where obtained elsewhere, the specific source,
or its type and sector where naming it is genuinely not possible. Where obtained elsewhere, also
state the categories of personal data concerned, since the reader has no existing awareness of what
is held about them (EU: Art. 14(1)(d) GDPR).

Why: the specific purpose, stated concretely, not as an open-ended possibility.

Our legal basis: name the Art. 6(1) basis by letter; where the basis is legitimate interest, name
the specific interest pursued rather than citing the article alone (EU: Art. 13(1)(d) GDPR); where
the data is Art. 9 special-category, name the specific Art. 9(2) ground separately.

Who else sees it: named recipients or categories of recipients, as specific as possible (EU: Art.
13(1)(e) GDPR); for the US module, the categories of personal data shared and the categories of
third parties, or a statement that none are shared.

Sold or shared: state plainly whether this category is sold or shared, and to whom, or that none
is, and whether any part of it is sensitive personal information used outside the state's
authorized purposes (CA: Cal. Civ. Code 1798.130(a)(5); 11 CCR 7011(e)(1)(D), (E), (J)).

Transferred outside the EEA or your state: where applicable, name the adequacy decision or the Art.
46/47/49(1) safeguard relied on, and how to get a copy of it (EU: Art. 13(1)(f) GDPR).

How long we keep it: a period, or the criteria that set one, detailed enough that the reader can
work out roughly how long their data is kept.

Do you have to give us this: for data collected from the data subject only, state whether providing
it is a statutory or contractual requirement or needed to enter a contract, and the consequence of
not providing it (EU: Art. 13(2)(e) GDPR).

When this reaches the reader: for data collected from the data subject, give this notice at the
time of collection. For data obtained elsewhere, give it within a reasonable period and at the
latest within one month, brought forward to the first communication with the data subject or the
first disclosure to another recipient, whichever comes sooner (EU: Art. 13(1), Art. 14(3)(a) to (c)
GDPR). Where a new purpose arises beyond the one already disclosed, give the reader this same
information for that new purpose before the further processing on it starts (EU: Art. 13(3), Art.
14(4) GDPR).

Automated decisions: where this activity involves Art. 22(1) or (4) automated decision-making,
including profiling, describe the logic involved and the significance and envisaged consequences
for the data subject in plain language (EU: Art. 13(2)(f) GDPR). For the Colorado module, where the
decision carries a legal or similarly significant effect, also name the decision covered, the
categories of data processed for it, whether it has been evaluated for accuracy, fairness, or bias
and the outcome, the benefits and potential consequences, and how to opt out (CO: 4 CCR 904-3 Rule
9.03(A), (B)).

## Module: your rights (EU and Germany)

State that the reader can ask the controller to:

- confirm whether it processes their data and give them access to it (Art. 15 GDPR);
- correct inaccurate data (Art. 16 GDPR);
- erase their data in the situations the law sets out, under the heading at PW-EU-11 (Art. 17
  GDPR);
- restrict processing in specific situations (Art. 18 GDPR);
- receive the data they gave in a portable format, where the processing rests on their consent or
  on a contract and happens by automated means (Art. 20 GDPR);
- object to processing that rests on legitimate interest, including profiling based on it (Art.
  21(1) GDPR).

Direct marketing: state that the reader can object to marketing at any time, free of charge, with
no need to justify the objection, and that the controller stops using their data for that purpose
once they do (Art. 21(2), (3) GDPR).

Withdrawing consent: where processing rests on consent, state that it can be withdrawn at any time,
as easily as it was given, through the same channel, free of charge, with no effect on the
lawfulness of processing before withdrawal (Art. 7(3) GDPR).

Complaints: name the controller's lead supervisory authority where known, and state that the reader
can lodge a complaint with it, bring a judicial remedy against that authority, or bring a separate
judicial remedy directly against the controller; present these as three separate routes, with using
one never conditioned on having used another first (Art. 77, 78, 79 GDPR).

How to reach the controller about any of this: give the rights-request channel (contact details,
not an account requirement). State that requests are answered within one month, extendable by two
further months for complex or numerous requests, with the reader told within the first month and
given the reason for any extension (Art. 12(3) GDPR). State that a request the controller will not
act on is refused within one month, with reasons and the options above (Art. 12(4) GDPR). State
that the channel is free, with a fee or refusal only where a request is manifestly unfounded or
excessive, the burden of showing that resting on the controller (Art. 12(5) GDPR), and that identity
verification is only asked for on reasonable doubt (Art. 12(6) GDPR).

## Module: your rights (US states)

Use this module for a visitor the US checklist's threshold questions place under California,
Virginia, Colorado, Connecticut, or Texas law; confirm against
`references/checklists/privacy-notice-us.md` which of these actually apply to this business before
filling it in.

CalOPPA: this one applies on its own test, independent of the CCPA revenue and volume thresholds,
to any operator of a commercial website or online service that collects personally identifiable
information from a California resident (CA: Bus. and Prof. Code § 22575(a)). Where it applies,
whether or not the CCPA module below also does, state: how the business responds to a browser
do-not-track signal or a similar cross-site choice mechanism, if it engages in that collection (a
clear, conspicuous link to an explanation of the program or protocol it follows satisfies this in
place of writing it into the notice text); whether other parties may collect personal information
about the reader's activity over time and across sites through this product; the business's process,
if it has one, for a consumer to review and request changes to their own collected information; how
the business notifies consumers of a material change to this policy; and the policy's effective date
(CA: Bus. and Prof. Code § 22575(b)(1) to (7)).

Head this section with the applicable state law's name, then state that the reader can ask the
business to:

- tell them the categories of personal information collected or processed about them, and the
  purpose for each;
- correct inaccurate personal information;
- delete personal information held about them, subject to the exceptions the law allows;
- where applicable, receive a portable copy of the personal information they gave;
- opt out of the sale or sharing of their personal information, and of its use for targeted
  advertising or for profiling that produces a legal or similarly significant effect.

How to reach the business about any of this: give the request channel, matching how the business
normally interacts with its consumers (for California, at least two methods for delete, correct, or
know requests, and at least two for opt-out and limit requests). State that no new account is
required to use these rights, though an existing account may still be used. State the response
window: 45 days for Virginia, Colorado, Connecticut, and Texas, and 45 calendar days for
California after a 10-business-day acknowledgement, each extendable once by 45 more days with
notice. State that a declined request is explained, with appeal instructions, within the same
window.

Appeals: give the appeal channel, decided within 60 days with written reasons, and, on a denied
appeal, the route to the state attorney general, for Virginia, Colorado, Connecticut, and Texas.

Opting out of sale, sharing, or targeted advertising: for California, use the exact link titles at
PW-US-CA-3, or the PW-US-CA-4 alternative with its icon. For Virginia, Colorado, Connecticut, and
Texas, give a clear and conspicuous opt-out link, using one of the PW-US-CO-1 examples for
Colorado. State which universal opt-out preference signal the business honors, since California
requires any commonly recognized format, Colorado requires conformance with the attorney general's
technical specifications from 2024-07-01, and Connecticut requires conformance with the statute's
five listed conditions from 2025-01-01. Where Connecticut applies, state that a conflict between
this signal and a setting the reader already gave directly, or their loyalty-program participation,
is resolved in favor of the signal, with a confirmation choice offered but not waited on. Where
Colorado applies, state instead that the reader's own separately disclosed consent to targeted
advertising or sale, given through a page or app, takes precedence over a signal already in effect.

No discrimination: state that the business does not charge a different price, or give different
service or quality, because the reader exercised a right above, except where a difference is
reasonably related to the value their data provides, calculated in good faith; note that a
different price or quality tied to voluntary participation in a loyalty, rewards, or discount
program is not itself discrimination.

No private right of action: state plainly that nothing in this section gives the reader a right to
sue the business directly under the named state law, since enforcement is reserved to the state
attorney general, and, for California, the California Privacy Protection Agency as well.

## Module: sensitive data and consent

Sensitive data: list the categories that actually apply, matching the stricter of the GDPR Art. 9
list and the state's own sensitive-data definition, for example racial or ethnic origin, religious
belief, health data, sexual orientation, citizenship or immigration status, genetic or biometric
data used to identify the person, precise geolocation, or a known child's data.

Where the EU basis is consent, use the PW-EU-12 affirmative-consent sentence pattern, adapted to
the specific purpose, with its own opt-in separate from any other purpose (Art. 7(2), 9(2)(a)
GDPR).

For the state module, where applicable, state that opt-in consent is obtained before processing
this data (VA, CO, CT, TX), or, for California, that the reader can limit the business's use of
their sensitive personal information to the purposes the law allows (CA: Cal. Civ. Code 1798.121).
Where the business sells sensitive personal data, post PW-US-TX-1 verbatim, in the same place and
manner as the rest of this notice; where it sells biometric data, post PW-US-TX-2 verbatim under
the same condition.

State plainly that consent for this section is never built into a bundled general-terms checkbox,
into hovering, muting, pausing, or closing other content, or into any default the reader would have
to notice and change; consent here is always its own separate, affirmative step.

## Module: children's data

Use this module only where the product is, or a severable portion of it is, directed to children,
or the operator has actual knowledge of collecting from a child under 13.

State that, before collecting, using, or sharing a child's personal information, the business
obtains a parent's verifiable consent, including before any material change to how it already uses
that information (16 C.F.R. § 312.5(a)(1), (2)). Name every operator collecting the information, or
a designated contact operator, what is collected and why, who else sees it and why, and the written
retention policy for it (16 C.F.R. § 312.4(d)).

State that a parent can at any time ask what has been collected, ask the business to stop
collecting more, and ask for deletion, through a named parent-request channel, without an
unreasonable burden to prove they are the child's parent (16 C.F.R. § 312.6(a)).

Where California's under-16 rule applies, state that, for a known child under 13, their data is
sold or shared only with a parent's documented consent, and for a known consumer aged 13 to under
16, only after a two-step opt-in, with the parent or consumer told either way about their ongoing
right to opt out afterward (CA: Cal. Civ. Code 1798.120(c)).

Where a state minor-activity rule applies, state that there is no targeted advertising, sale, or
significant-effect profiling involving a known child's or minor's data without the required
consent, and no precise geolocation collection from a minor without a signal to them during
collection (VA, CO, CT). For a qualifying social media product, add Virginia's one-hour daily use
default for a minor under 16 absent a parent's consent to change it, and Connecticut's channel for a
minor, or a parent of a minor under 16, to ask for an account to be unpublished within 15 business
days or deleted within 45 business days.

## Open points to raise

- Which US states beyond California, Virginia, Colorado, Connecticut, and Texas the product
  actually reaches, since several of the others (Delaware, New Jersey, Montana, Maryland) use a
  materially different threshold or sensitive-data rule from the states this template covers in
  full; check `references/us-states/state-matrix.md` for each one before relying on this module
  alone.
- Whether any feature meets California's significant-decision test for automated decisionmaking
  technology, which would add the Pre-use Notice, opt-out, access, and risk-assessment duties on
  top of what this template covers.
- Whether the business actually knows, or willfully disregards, that a visitor is a minor or
  child under any of the state tests above; none of them draws a bright line in the statute text.
- Whether a specific product's content, audience evidence, and advertising mix cross COPPA's
  directed-to-children threshold; the Commission decides this case by case rather than against a
  fixed rule.
- Whether any processing activity above also needs a data protection impact assessment or a state
  data protection assessment before it starts, which this notice template does not itself cover;
  see `references/eu/gdpr-legal-bases.md` and the assessment duties in
  `references/checklists/privacy-notice-us.md`.
