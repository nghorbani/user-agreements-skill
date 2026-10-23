---
title: User Agreements Skill for Claude Code
description: Draft terms of service, EULAs, subscription terms, privacy and cookie notices, acceptable use policies and data processing agreements for software sold in the EU and the US, ready for review by counsel.
---

# User Agreements Skill

A skill for Claude Code that drafts the agreements a software product needs in the EU and the US, and hands them to
your lawyer with the legal basis of every clause.

## How to use it

1. [Install the skill](install.md) and restart Claude Code.
2. Describe your business and product in a normal message: who sells, what, to whom, in which countries, how people
   pay and which data you collect. Say which documents you want.
3. Answer the questions the skill asks back. It needs about a dozen facts (seller details, markets, pricing, data,
   cookies, user content, warranty and update promises) and asks only for the ones your message left out. If you
   want drafts right away, say so: it drafts on stated assumptions and marks what each missing answer would change.
4. Read the hand-over and send it to your lawyer.

A first message can be as short as this:

```text
We are Example Fitness GmbH in Ulm. We sell a fitness app with a monthly subscription and a 7-day free trial
to consumers in Germany, Austria, California and New York. Please draft our subscription terms and the
withdrawal information, and tell us what our checkout and cancellation flows must do.
```

## What to expect

The skill works through the same steps for every request: it collects the facts, decides which laws apply, picks the
documents, drafts them, checks them against its checklists and hands them over. You get a folder of Markdown files:

- **The drafts.** One common text with marked modules for EU consumers, EU business customers and the US, or
  separate versions where the two cannot share one text. Statutory button labels and model forms appear word for
  word.
- **`annotations.md`.** The statute, regulation or judgment behind each clause, a table of every law the skill
  considered with applies, does not apply or undetermined, and a checklist table with every item marked met, not
  applicable or open.
- **`open-points.md`.** Facts the skill did not have, national rules to verify, rules that take effect later, and
  the choices your lawyer has to make.
- **`implementation-requirements.md`.** What your product has to do for the documents to hold: order button
  wording, cancellation path, withdrawal function, consent banner, reminders, records to keep. Each row has owner and
  evidence columns.
- **The law-as-of date.** The references follow the law as of 20 October 2026.

What it does not do: decide facts it was not given, fill gaps from general knowledge, or replace your lawyer. Where
the law turns on a number you did not provide (revenue, users per state), the instrument stays undetermined and the
dependent clauses go to the open points instead of the draft. See [how it works](how-it-works.md) for the details
and the [examples](examples/index.md) for four complete hand-overs.

## What it drafts

- Terms of service and platform terms
- End user license agreements (EULAs)
- Subscription and auto-renewal terms
- Privacy notices and cookie notices
- Acceptable use policies
- Data processing agreements between businesses
- The EU consumer add-ons: withdrawal information with the model withdrawal form, and the German Impressum

## Markets

Germany is the reference EU member state, with the EU directives and regulations behind it. In the United States the
skill covers federal law, California and New York in full, and the other states as a matrix of flags. The
[coverage page](coverage.md) shows which topic is covered where.

## Typical requests

- [SaaS terms for the EU and the US](use-cases/saas-terms-eu-us.md)
- [Subscription app terms for Germany, California and New York](use-cases/subscription-app-terms.md)
- [EULA for software shipped with hardware](use-cases/eula-software-with-hardware.md)
- [Privacy notice under GDPR and CCPA](use-cases/privacy-notice-gdpr-ccpa.md)
- [Platform terms under the Digital Services Act](use-cases/platform-terms-dsa.md)

The drafts are for review by a lawyer and are not legal advice; see the [disclaimer](disclaimer.md).
