---
title: "B2B SaaS for manufacturers: changing a sub-processor"
description: The internal mechanics for swapping a backend vendor, such as the support-ticketing system, without re-papering every customer contract.
---

*Fictional product, illustrative draft. Not legal advice.*

# Changing a backend service provider (sub-processor changes)

Law as of: 20 October 2026. This is a draft for a lawyer to review before use. It is not legal advice.

This memo answers the question: when Example Machines changes which company runs a backend service that touches
personal data, such as the support-ticketing system today or the cloud hosting provider in future, what
does Example Machines need to do, and under which document?

## The short answer

A change of backend vendor is a sub-processor change under the Data Processing Agreement, not a
change to the Master Subscription Terms. Because the DPA (`data-processing-agreement.md`) uses the
general-authorisation model (Clause 7.7, Option 2), Example Machines does not need a fresh signed approval from
every customer for each change. Example Machines needs to:

1. Keep a current, accurate sub-processor list (Annex IV of the DPA).
2. Give every affected customer written notice of the intended addition or replacement at least 30
   days before the new sub-processor is engaged.
3. Give the customer a real opportunity to object within that window.
4. Resolve an objection before the change goes ahead for that customer, or let the customer terminate
   if no resolution is reached.
5. Where the new sub-processor is outside the EEA, confirm the transfer mechanism before go-live, not
   after.

## Why the general-authorisation model, not specific authorisation

Clause 7.7 of the EU standard contractual clauses offers two options:

- **Option 1 (prior specific authorisation):** each new or replaced sub-processor needs its own
  signed approval from each customer before engagement.
- **Option 2 (general authorisation):** customers approve the DPA's sub-processor list once, at
  signing, and Example Machines can add or replace a sub-processor later by giving notice and an objection
  window, without a fresh signature each time.

Option 1 would mean that changing the ticketing vendor, or any other backend provider, requires
individually chasing a signed approval from every one of Example Machines' customers before the change can go
live - impractical for a SaaS business with many customers and an ordinary vendor-management cycle.
Option 2 is the standard choice for exactly this reason, and it is explicitly one of the two options
the official EU clauses offer, to be set out for the client to choose rather than picked unilaterally
(`references/eu/gdpr-processors-transfers.md`, EDPB Guidelines 07/2020 para. 155, 157, 158). The DPA
drafted for Example Machines states both options and records that the Customer chose Option 2; if a particular
customer insists on Option 1 during negotiation, that customer's copy of the DPA needs its own Annex
IV naming every sub-processor it specifically approves, and that customer's sub-processor changes then
do need a signed approval each time.

## The mechanics, step by step

**Step 1: identify the change as a sub-processor change.** A new backend vendor that will process
Account Data (or any other personal data processed under the DPA) on Example Machines' behalf is a
sub-processor under Clause 7.7(b): the vendor must be bound, by contract, to in-substance the same
data protection obligations Example Machines itself owes the customer, and Example Machines stays fully responsible to the
customer for that vendor's performance.

**Step 2: put the vendor contract in place first.** Before notifying customers, Example Machines needs its own
contract with the new vendor, covering: confidentiality, the Art. 32 GDPR security measures, the
customer's audit rights flowing down where applicable, deletion/return of data at the end of the
engagement, and a third-party-beneficiary clause letting the customer step in and instruct erasure or
return if Example Machines itself disappears or becomes insolvent (Clause 7.7(e)). This is Example Machines' own
sub-processor contract with the vendor, separate from the Example Machines-customer DPA.

**Step 3: update the sub-processor list and notify customers.** Add the new vendor to Annex IV (or a
public sub-processor page the DPA cross-refers to), and notify every affected customer in writing at
least 30 days before the vendor is actually engaged for that customer's data. The notice should name
the vendor, what it will process, where it is located, and the date the change takes effect.

**Step 4: hold the objection window open.** For 30 days from notice, a customer may object. The DPA
does not spell out what happens on an objection because the official clause text does not either; as a
matter of practice:

- If the objection can be resolved (for example, by offering that customer an opt-out from the
  specific feature the new vendor supports, or by using a different vendor for that customer), resolve
  it and confirm in writing.
- If it cannot be resolved and the customer insists on not having its data touched by the new vendor,
  the customer's options are to stay on the prior arrangement if Example Machines can still support it, or to
  treat this as grounds to terminate the engagement for that data under Clause 10(b) of the DPA if
  Example Machines cannot or will not accommodate the objection. Flag this to counsel before a real objection
  arises - this is a commercial as much as a legal decision, and the DPA leaves it open by design,
  consistent with how the EDPB guidance describes the choice (`references/eu/gdpr-processors-
  transfers.md` para. 155, 157, 158).

**Step 5: confirm the transfer mechanism before go-live, not after.** If the new vendor sits outside
the EEA (as the current US ticketing vendor does, and as a future US-based replacement would), confirm
before the 30-day notice period ends which transfer tier applies:

- **Tier 1 (adequacy):** if the vendor is certified under the EU-US Data Privacy Framework, the
  transfer can rely on the Commission's adequacy decision for DPF-certified US recipients.
- **Tier 2 (safeguards):** if not DPF-certified, use the Commission's Art. 46(2)(c) transfer clauses,
  selecting the Module that matches the data flow (ordinarily Module Two, controller to processor
  disguised as processor-to-sub-processor in substance, or Module Three for a processor-to-
  sub-processor transfer, since the customer is the controller and Example Machines is the processor transferring
  onward to its own sub-processor).
- Before relying on the transfer clauses, complete the Clause 14 warranty on the destination country's
  government-access laws and practices; do not promise the vendor will never comply with a lawful US
  government request, since Clause 15.2 requires legality review and minimisation instead of a blanket
  refusal (`references/eu/gdpr-processors-transfers.md`).

Do this confirmation before the change goes live, not retroactively, since the DPA's Clause 7.8(a)
only authorises an onward transfer that already complies with Chapter V GDPR at the time it happens.

## What does NOT need to change

- The Master Subscription Terms. The subscription agreement does not name specific sub-processors; it
  incorporates the DPA by reference, and the DPA's own Annex IV is the document that changes.
- Signed approval from each customer, provided the customer's DPA uses Option 2 (general
  authorisation) and no customer has objected within its window.
- The Order Form or pricing - a backend vendor change is operationally invisible to the customer unless
  it affects the service itself (for example, a different support channel).

## What DOES need to change

- Annex IV of the DPA (or the public sub-processor list it points to).
- Example Machines' own contract with the outgoing and incoming vendor (termination/transition terms with the
  outgoing vendor; onboarding terms, including the Clause 7.7(b) flow-down obligations, with the
  incoming vendor).
- The transfer-mechanism documentation in Annex II of the DPA, if the new vendor's location or
  certification status differs from the old one's.
- Internal records of: the notice sent, the date, which customers were notified, and the resolution of
  any objection received (`references/eu/gdpr-processors-transfers.md`, "Product behaviour it
  assumes" - a current register of sub-processors and the authorisation basis for each).

## If the change is to the cloud hosting provider itself, rather than a point-service like ticketing

The same mechanics apply, but hosting is a more sensitive change because it touches both Account Data
and Machine Data, and because the Master Subscription Terms' connected-product-data clause (Section 7)
and the sales pitch itself ("everything is hosted in a cloud region in Germany") depend on the hosting
location. Before changing the hosting provider or region:

- Confirm the new arrangement keeps data hosted in Germany, if that remains a commercial and
  contractual commitment Example Machines has made (the Master Subscription Terms do not currently promise this
  to the customer in binding language - see `open-points.md` on whether to make "hosted in Germany" a
  stated commitment rather than a background fact).
- If the new provider is itself outside the EEA, or if data will now leave the EEA even transiently,
  this is a materially bigger notice item than a support-vendor swap and should get its own,
  separately flagged customer communication, not just the standard 30-day sub-processor notice.
- Check whether the Data Act's cloud-switching regime (Art. 23 to 30) applies to Example Machines' own
  relationship with its outgoing cloud provider (not to Example Machines' relationship with its own
  customers) - this is a separate, one-directional duty that binds whichever provider the switch is
  happening away from, and it is a source-side duty Example Machines would benefit from on exit, not a duty
  Example Machines itself necessarily owes its customers for hosting changes (see `open-points.md`, Section 15
  of the Master Subscription Terms).

## Legal basis summary

`references/eu/gdpr-processors-transfers.md` (Art. 28(2), (4) GDPR; EDPB Guidelines 07/2020 para. 155,
157, 158, 160; the two Commission Decisions on standard contractual clauses); Clause 7.7, 7.8 of
Decision (EU) 2021/915, reproduced in `data-processing-agreement.md`.
