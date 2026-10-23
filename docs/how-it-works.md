---
title: How the skill works
description: The six steps the user-agreements skill follows, from intake questions to a hand-over with annotations, open points and an implementation register.
---

# How the skill works

The skill is a set of Markdown files that Claude Code reads when your request is about user agreements: one
instruction file, reference files on the law, checklists, a clause library and document templates. It has no code of
its own and calls no service. Every request runs through six steps.

## 1. Intake

The skill asks for the facts it needs and you have not given yet, in one message:

1. the seller: legal entity, seat, contact, and whether it sells to consumers, businesses or both;
2. the product: web service, app, desktop software, firmware on a device, or a platform hosting user content;
3. markets: countries, US states, user or household counts where privacy laws have thresholds, annual revenue;
4. money: one-off price, subscription, free trial, freemium or in-app purchases, renewal and price changes;
5. personal data: categories, sensitive data, children or teenagers, controller or processor role, data leaving the
   EU;
6. cookies, SDKs, analytics and advertising tools;
7. AI features that users see or that decide about them;
8. user content and moderation;
9. open source components and third-party licences;
10. warranty, support, update promises and hardware;
11. existing documents and the current checkout, renewal and cancellation flows;
12. who reviews the drafts, and by when.

If two answers contradict each other, the skill points that out before it goes on. If you want drafts in the same
turn, it lists the open questions at the top, drafts on assumptions it states, and records what each answer would
change.

## 2. Applicability

For every law in its references the skill decides one of three states:

| State | What happens |
|---|---|
| applies | its clause rules go into the drafts and its product duties into the implementation register |
| does not apply | it gets a line in the table with the reason, and nothing in the drafts |
| undetermined | the skill names the missing fact and the question that settles it; the dependent clauses go to the open points, not into the drafts |

Thresholds and factual tests are decided only from facts you gave. A count of devices sold is not a count of
consumers whose data is sold or shared, and a total of US users is not a count per state, so the skill does not
estimate one from the other. The controller or processor role is decided per category of personal data, not once
for the whole contract.

## 3. Document set

The skill picks the documents the applicable law requires and the product needs. An EU consumer subscription
typically gets terms with subscription terms, withdrawal information with the model withdrawal form, a privacy notice,
a cookie notice and, for Germany, an Impressum. A US set typically has terms of service, subscription terms with the
state renewal disclosures, and a privacy notice with state supplements. Business customers get their own track
without the consumer-only rules.

## 4. Drafting

Drafts start from the templates and the clause library. Where one text can serve all markets, it has a common core
with marked modules for EU consumers, EU business customers and the US. Where the rules cannot share one text, for
example an arbitration clause with a class action waiver for US consumers against the jurisdiction rules for EU
consumers, the skill splits the document into versions. Citations and drafting notes stay out of the agreement text
and go into the annotations.

Prescribed wording is quoted exactly: the German order button "zahlungspflichtig bestellen", the cancellation button
"Verträge hier kündigen", the withdrawal function, the model withdrawal information and form. The skill does not
paraphrase or translate these texts.

## 5. Conflict check

Every draft is checked against a list of known conflicts between US and EU drafting and against each checklist that
fits the deal: one per document type plus the EU consumer, EU business, German standard terms and US consumer
checklists. The result is a checklist table in the annotations, with every item marked met, not applicable or open.
A draft is fixed before hand-over wherever an item is neither met nor an open point.

## 6. Hand-over

You receive the drafts, `annotations.md`, `open-points.md`, `implementation-requirements.md` and the law-as-of date.
The [examples](examples/index.md) show four complete hand-overs.

## Rules the skill keeps

- Every legal statement in the annotations carries a citation from a reference file. Where the references are
  silent, the point goes to the open points instead of being filled from memory.
- Numbers such as thresholds, caps and amounts appear only if a reference file states them.
- A court case or pending proceeding is named only with the citation a reference file gives, and a pending case is
  never presented as decided.
- Where an official model offers options, the skill sets out the options and asks which one you want.
- Rules that take effect after the law-as-of date, or before your launch date, go into the open points with their
  date.
- Facts about your business are never invented. The skill asks.
