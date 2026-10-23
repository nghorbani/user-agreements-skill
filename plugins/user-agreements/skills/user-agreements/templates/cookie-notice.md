# Cookie notice

Law as of: 2026-10-20

A fill-in template for a cookie and tracking-technology notice: the first-layer banner text, the
per-purpose second layer, and the standing information page behind both. It implements the consent
standard of Art. 5(3) Directive 2002/58/EC and its German transposition, §§ 25, 26 TDDDG. Where a
cookie or similar item also triggers GDPR processing once placed, this notice covers the placement
step only; pair it with `references/checklists/privacy-notice-gdpr.md` and the privacy notice
template for the processing that follows.

## How to fill this in

- Build an inventory first: every item that stores or reads information on a user's device, not
  only items called cookies. Pixels, tracking links, client-side scripts that later send results
  off-device, locally cached identifiers, and IoT reporting are all in scope the moment information
  leaves the device or a derivation of it does (Art. 5(3) Directive 2002/58/EC; EDPB Guidelines
  2/2023, paras 47 to 63, cited in `references/eu/eprivacy-cookies.md`). Tag each item by what it
  actually does, not by a category name: a label such as analytics, personalisation, or security
  cookie is not itself a legal basis for anything (TDDDG guidance, cited in
  `references/de/tdddg.md`).
- For each item, decide first whether it is exempt from consent. Only two exemptions exist:
  technical storage or access for the sole purpose of carrying out a transmission, and storage or
  access strictly necessary for a service the user actually requested (Art. 5(3) Directive
  2002/58/EC). Claim an exemption only where every purpose the item serves independently meets this
  test; one non-qualifying purpose on an otherwise-exempt item defeats the exemption for the whole
  item (`references/de/tdddg.md`). A cart or payment cookie is not strictly necessary before the
  matching user action (placing an item in the cart, starting payment); mere browsing does not
  trigger it. A cookie carrying a unique identifier needs that individualisation to be checked too:
  storing a consent decision, load balancing, or a language preference needs only a non-identifying
  value.
- Before claiming the strictly-necessary exemption for any item, classify it against the base
  service the user is treated as requesting by the act of calling up the product, versus an
  additional function or service the user must actually and knowingly invoke, such as a shopping
  cart, a chat box, or a wish list. A general measurement or analysis function is not automatically
  part of the base service merely because it is bundled with it (`references/de/tdddg.md`).
- Put every non-exempt item behind consent, with its own control, starting unselected or off,
  requiring an affirmative action to turn on (Art. 5(3) Directive 2002/58/EC; Planet49, paras 52,
  57, 62, 63, cited in `references/eu/eprivacy-cookies.md`). One tick for one purpose never stands
  in for consent to a different purpose.
- Where several purposes exist, give each one its own layer-one disclosure, not a single bundled
  accept-all covering purposes the first layer never named. Where one button grants both the
  device-level storage consent and a later GDPR processing consent, say so and name the processing
  purposes at the point the button sits, rather than only on a deeper layer
  (`references/de/tdddg.md`).
- Name third parties individually wherever the notice discloses them; a general reference to
  partners does not meet the specificity the sources require.
- At the first layer, also state whether individual profiles are built and enriched with data from
  other sites, and how many controllers the data is disclosed to, alongside any statement on whether
  data is processed outside the EEA (`references/de/tdddg.md`).
- Keep the banner free of any non-essential script or third-party content loading while it is
  displayed and the user's consent is undecided, and keep the legal notice and the privacy notice
  reachable regardless of the banner's state (`references/de/tdddg.md`).
- Decide whether the first layer needs a reject control. Under the Directive and EDPB guidance, a
  reject option belongs on the same layer as any consent button, with comparable visual prominence
  (`references/eu/eprivacy-cookies.md`). Under the German guidance, a first-layer reject option is
  required wherever the banner blocks some or all site or app content pending the user's decision;
  where nothing is blocked and no action is needed to keep using the service, a first-layer reject
  control can be dispensable, subject to an individual-case check (`references/de/tdddg.md`). Pick
  the stricter reading, always include a first-layer reject, unless a drafter has confirmed the
  product's flow blocks nothing and documented that check. Where a reject control is offered, give
  it an unambiguous label of its own; a short, clear phrase is enough, and the label must not be
  folded into a combined settings-or-reject label that only leads to a further layer
  (`references/de/tdddg.md`).
- Where any purpose also rests on Art. 6(1)(f) GDPR legitimate interest for something beyond the
  placement step itself, for example personalised-content profiling or personalised advertising,
  give the objection to that legitimate-interest processing the same first-layer prominence as the
  reject control; do not push it to a deeper layer where a user could believe they must refuse
  twice (`references/eu/eprivacy-cookies.md`).
- Never condition access to the site or app on accepting anything beyond what is strictly
  necessary, and never let the service appear worse, redirect, or seem to require consent from the
  first layer onward.
- Keep the withdrawal control as easy to reach and as easy to use as the original consent action,
  through the same interface, at any time, from a centralised and clearly linked place.
- Fill the bracketed placeholders ([site or app name], [controller name and contact], [DPO contact
  if any], [list of purposes], [list of named third parties], [retention period per item]) from the
  actual inventory; do not ship a bracket in a live notice.
- No statute or guidance in these references prescribes exact banner, button, or toggle wording; the
  text below is drafting, not a quoted statutory model (`references/eu/eprivacy-cookies.md`;
  `references/de/tdddg.md`). Keep the substance: purpose-specific, affirmative, reversible,
  equally easy to decline as to accept.

## Module: first-layer banner

Use this layer for the first thing a user sees, before any non-essential storage or access happens.

[Site or app name] uses cookies and similar technologies on this device.

We use [strictly necessary items] to run this [site/app]. With your choice, we also use cookies and
similar technologies for [purpose 1, e.g. analytics], [purpose 2, e.g. personalised content], and
[purpose 3, e.g. advertising], including with [named third party 1] and [named third party 2]. You
can accept all of these, reject all of them, or choose which ones to allow.

[Accept all] [Reject all] [Choose settings]

No item beyond what [site or app name] needs to run the service is active until you choose. You can
change your choice at any time from [link or icon to the consent settings, described below].

## Module: second-layer settings

Use this layer once the user opens the settings control from the first layer. Give every
non-essential purpose its own toggle, each starting off.

### Strictly necessary

Always active. These keep the [site/app] working, for example remembering your session or your
cookie choice itself. They do not need your consent because they are strictly necessary for the
service you have asked for. [List each item: name, purpose, duration, who can read it.]

[ ] Always on (no toggle)

### [Purpose 1, e.g. analytics]

We use this to [state the concrete purpose in plain language, e.g. understand how visitors use this
site so we can improve it]. [Name the third party or parties, if any.] [State the duration of
the longest-lived item under this purpose.] [State whether data under this purpose leaves the EEA,
and to where, if applicable.]

[ ] Allow (off by default)

### [Purpose 2, e.g. personalisation]

[Same structure as above, repeated once per purpose.]

[ ] Allow (off by default)

### [Purpose 3, e.g. advertising]

[Same structure as above, repeated once per purpose.]

[ ] Allow (off by default)

[Save my choices] [Accept all] [Reject all]

## Module: standing cookie information page

Use this as the always-reachable page the banner and settings layer link to, kept separate from the
general privacy notice.

### What this page covers

This page explains the cookies and similar technologies [site or app name] uses, why, for how long,
and who else can read them. It does not replace our privacy notice, which explains what we do with
personal data once it is collected; see [link to privacy notice].

### Who is responsible

[Controller name], [postal address], [email address]. [DPO contact, if one is appointed.]

### What counts as a cookie here

We use this term for any cookie, tracking pixel, local storage item, device identifier, or similar
technology that stores information on your device or reads information already stored there. This
covers tools used on our own behalf and tools used by the third parties named below.

### The items we use

[Table or list, one row per item: name, strictly necessary or by purpose, what it does, how long it
lasts, who can read it (us only, or which named third party), whether it feeds an individual profile
enriched with data from other sites, and how many controllers the data is disclosed to.]

### Your choice

Nothing beyond what is strictly necessary to run the [site/app] is active until you choose. You can
accept all, reject all, or choose by purpose, through [the banner on first visit] and again at any
time through [link or icon to the settings layer]. Withdrawing your choice later takes you to the
same settings layer and the same number of steps it took to give it; nothing you have already
browsed is affected.

### What happens if you decline

[State plainly what, if anything, changes: reduced personalisation, no targeted advertising, and so
on. State it here even if the banner already states it. Do not state that declining blocks access to
the site or app unless that is actually true and strictly necessary items alone justify it.]

### How long we keep each choice

[State the duration your consent-management mechanism stores a recorded choice for, and that a new,
non-essential third party added later triggers a fresh choice rather than relying on an old one.]

## Open points to raise

- Whether a reject control is required on the first layer for this specific product depends on
  whether the banner blocks any content pending the user's decision; confirm the actual behaviour
  before relying on the dispensable-reject reading (`references/de/tdddg.md`).
- For any country other than Germany, the Directive sets the floor but national transposition sets
  the exact wording and enforcement; do not draft against the Directive text alone for another
  member state (`references/eu/eprivacy-cookies.md`).
- Whether any named third party processes data for its own purposes beyond what this notice
  describes needs a check against that party's actual role, not an assumption from its category
  (`references/de/tdddg.md`).
- Whether any item's data leaves the EEA needs a transfer-mechanism check under
  `references/eu/gdpr-processors-transfers.md` before the notice states a destination.
