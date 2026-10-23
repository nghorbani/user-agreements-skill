---
title: "Subscription app terms: Germany, California, New York"
description: Draft subscription and auto-renewal terms for a consumer app sold in Germany, California and New York, with the withdrawal information, the German order and cancellation buttons and the state renewal rules.
---

# Subscription app terms: Germany, California, New York

For a consumer app or web service with a monthly or annual plan, a free trial or both, sold in Germany and other EU
countries and in US states with automatic renewal laws.

## Example request

```text
We sell a fitness app to consumers in Germany, Austria, California and New York. There is a free tier and a
monthly plan with a 7-day free trial that turns into the paid plan unless cancelled. People buy on our website
and through in-app purchase. Please draft our subscription terms and the withdrawal information, and tell us
what our checkout, renewal and cancellation flows must do.
```

## What the skill does

- **Withdrawal information.** The German text follows the statutory model of EGBGB Anlage 1 word for word, with your
  details filled in, plus the model withdrawal form of Anlage 2. For a subscription the period runs from the
  conclusion of the contract; the skill handles the consumer's request for the service to start during the
  withdrawal period.
- **German buttons.** The checkout requirements name the order button "zahlungspflichtig bestellen" (§ 312j Abs. 3
  BGB). The cancellation requirements name the button "Verträge hier kündigen", the confirmation button
  "jetzt kündigen" and what the confirmation page must collect (§ 312k BGB). The electronic withdrawal function uses
  "Vertrag widerrufen" and "Widerruf bestätigen" (§ 356a BGB).
- **California.** The Automatic Renewal Law: clear and conspicuous offer terms before consent, affirmative consent,
  the acknowledgment, online cancellation, the click-to-cancel rule where a retention offer is shown, trial reminders
  and notice of price changes.
- **New York.** General Business Law § 527-a: disclosures before consent, affirmative consent, the notice after
  consent, cancellation through every medium consent was taken in, notice of material changes and the rule for price
  increases.
- **App stores.** When the purchase runs through an app store, the store controls parts of the checkout, the renewal
  notices and the cancellation path. The skill flags which duties stay with you.
- **Other EU countries.** Austria and other member states are drafted at directive level, with the national rules
  listed as open points.
- **No arbitration for EU consumers.** An arbitration clause or class action waiver, if you want one for US
  consumers, stays in the US module.

## Documents

Subscription terms with EU and US modules, German withdrawal information with the model form, annotations, open
points and an implementation register covering checkout, trial, renewal, price change and cancellation flows.

See the full [fitness app example](../examples/fitness-app/index.md).
