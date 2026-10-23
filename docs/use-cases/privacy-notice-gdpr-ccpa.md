---
title: Privacy notice under GDPR and CCPA
description: Draft a privacy notice for a product used in the EU and the US, with the GDPR Article 13 and 14 content, a cookie notice under the TDDDG and state supplements for California and other US states.
---

# Privacy notice under GDPR and CCPA

For a product that collects personal data from users in the EU and the US and needs one privacy notice with the EU
content and the US state supplements, plus a cookie notice.

## Example request

```text
Our app is used in Germany and across the US. We collect account data, usage analytics through a US SDK and
heart rate from a connected wearable. We show personalised ads to adults. Please draft our privacy notice and
cookie notice for the EU and the US.
```

## What the skill does

- **GDPR content.** The notice follows Articles 13 and 14: controller and contact, purposes with their legal basis,
  recipients, transfers, storage periods, the data subject rights and the right to complain. Each purpose gets its
  own legal basis; the skill does not put several purposes under one.
- **Sensitive data.** Health-related data such as heart rate is flagged for Article 9 treatment.
- **Consent for tracking.** Reading or storing information on a user's device needs consent under § 25 TDDDG unless
  an exception applies. Personalised advertising rests on consent, in line with the EDPB guidance the reference files
  cite.
- **California.** The CCPA notice at collection and privacy policy content, the opt-out of sale and sharing, and the
  CalOPPA duties, once the thresholds are known.
- **Other US states.** Virginia, Colorado, Connecticut and Texas from their own statutes, the remaining state laws
  from the matrix. Each state is read from its own thresholds and its own consumer definition; a total of US users
  does not tell the skill how many live in each state, so it asks.
- **Children.** If children or teenagers are in the audience, the GDPR consent age rules and COPPA come in; if not,
  they stay out.

## Documents

Privacy notice with EU core and US state supplements, cookie notice, annotations, open points and an implementation
register (consent banner behaviour, opt-out links, records of consent, response process for rights requests).

Related: [subscription app terms](subscription-app-terms.md), [SaaS terms for the EU and the US](saas-terms-eu-us.md).
