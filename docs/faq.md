---
title: FAQ
description: Common questions about the user-agreements skill for Claude Code, including whether it is legal advice, which markets it covers and what you get back.
faq:
  - q: Is this legal advice?
    a: No. The skill writes drafts for review by a qualified lawyer. Every hand-over says so and states the date of the law it follows, 20 October 2026.
  - q: Which countries does it cover?
    a: The EU directives and regulations with Germany as the reference member state, US federal law, California and New York in full, and the other US state privacy laws as a matrix of flags. Other EU member states are drafted at directive level with the national rules listed as open points.
  - q: What do I get back?
    a: A folder of Markdown files with the drafts, annotations giving the legal basis of each clause, a list of open points for your lawyer, an implementation register of what your product flows must do, and the law-as-of date.
  - q: Does the skill send my data anywhere?
    a: The skill itself is a folder of Markdown files with no scripts and no network calls. Your requests are handled by Claude Code under its own terms.
  - q: Why does it ask so many questions?
    a: Whether a law applies often turns on a fact such as revenue, users per state or whether you sell to consumers. The skill does not guess those facts. If you want drafts right away, it drafts on stated assumptions and marks what each answer would change.
  - q: Can I use it for a UK business?
    a: UK law is not covered. The skill says so and continues with the EU and US parts of the request.
---

# FAQ

## Is this legal advice?

No. The skill writes drafts for review by a qualified lawyer. Every hand-over says so and states the date of the law
it follows, 20 October 2026. See the [disclaimer](disclaimer.md).

## Which countries does it cover?

The EU directives and regulations with Germany as the reference member state, US federal law, California and New York
in full, and the other US state privacy laws as a matrix of flags. For another EU member state, such as Austria or
France, the skill drafts at directive level and lists the national rules to verify as open points. The
[coverage page](coverage.md) has the topic-by-jurisdiction table.

## What do I get back?

A folder of Markdown files: the drafts, `annotations.md` with the legal basis of each clause and the checklist
results, `open-points.md` for your lawyer, `implementation-requirements.md` with what your product flows must do, and
the law-as-of date. The [examples](examples/index.md) show four complete hand-overs.

## Does the skill send my data anywhere?

The skill itself is a folder of Markdown files with no scripts and no network calls. Your requests are handled by
Claude Code under its own terms.

## Why does it ask so many questions?

Whether a law applies often turns on a fact: annual revenue, the number of consumers per US state, whether you sell
to consumers or businesses, who mainly uses your platform. The skill does not guess those facts. If you want drafts
right away, say so: it opens with the questions, drafts on assumptions it states, and marks in the open points what
each answer would change.

## Can it review my existing terms?

Yes. Give it the current text and the facts about your business. It runs the same applicability step, conflict list
and checklists against your text, so the checklist table shows which items your terms meet and which they miss,
with the legal basis of each.

## Does it check my checkout and cancellation flows?

It tells you what they must do. The implementation register lists every button label, notice, reminder, consent
step and record the documents assume, with owner and evidence columns for your team to fill in. It cannot see your
product, so checking the flows against the register is your team's job.

## Can I use it for a UK business?

UK law is not covered. The skill says so and continues with the EU and US parts of the request. The same holds for
sector rules such as HIPAA or financial services law, employment, tax and export control.

## Will the drafts be in German?

The drafts are in English unless you ask for German. Statutory German texts, such as the model withdrawal
information, the model withdrawal form and the button labels, always stay in German, because the law prescribes
them in that wording. An English working translation can go into the annotations, marked as unofficial.

## How current is the law?

The references follow the law as of 20 October 2026, and rules that take effect later are listed with their date.
Law made after that date is not in the skill; check what changed before you rely on a draft.
