---
title: "Fitness app subscription: implementation requirements"
description: The build-and-sign-off register for the checkout, renewal, cancellation and withdrawal flows, one row per requirement with its legal basis.
---

*Fictional product, illustrative draft. Not legal advice.*

# Implementation requirements: Stridewell Plus checkout, renewal and cancellation

Drafting aid for counsel and product review. Not legal advice. Law as of 2026-10-20.

This is the hand-over register from the legal references to Example Fitness GmbH's product and engineering teams for the Stridewell Plus web checkout and in-app purchase flows. Each row names one thing the product must do, the rule it rests on, and what evidence proves it is done. Fill in Owner and Status for your own team; Requirement, Legal basis and Evidence come from the reference files and do not change without a reference-file change.

Status values: not started, in progress, built, verified.

Scope note: this register covers only the checkout, renewal, cancellation and withdrawal flows your message asked about. It does not cover cookie consent, account-deletion-for-privacy-reasons, or health-data-specific access/erasure flows, which belong to the (separately drafted) privacy notice.

## Offer and checkout

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Order button for a German direct paid sign-up (no trial) carries exactly "zahlungspflichtig bestellen" and nothing else | § 312j Abs. 3 Satz 2 BGB; Case C-249/21 Fuhrmann-2 | | | not started |
| Order button for every other EU market carries "order with obligation to pay" or an equally unambiguous equivalent naming the payment obligation itself | Art. 8(2) CRD | | | not started |
| Where sign-up is framed as "start free trial," the screen still discloses, next to that control, that continuing after 7 days creates a payment obligation the user must act to avoid | Art. 8(2) CRD; § 312j Abs. 3 BGB (applied to the point payment obligation actually attaches); open point on exact phrasing, see subscription-terms.md section 2 | | | not started |
| Price (EUR 9.99 or USD 9.99/month), plan characteristics, one-month term and renewal mechanism shown directly before the order button, not behind a link | Art. 6(1)(e), (o), (p) CRD; § 312j Abs. 2 BGB | | | not started |
| Checkout gives an edit step for plan and payment method before submission | § 312i Abs. 1 Nr. 1 BGB | | | not started |
| Checkout discloses accepted payment methods and any delivery/access restriction no later than the start of the ordering process | § 312j Abs. 1 BGB | | | not started |
| No extra paid option (e.g., an add-on tier) is pre-ticked by default | § 312a Abs. 3 Satz 2 BGB; Art. 22 CRD | | | not started |
| A customary, reasonable, free payment option remains available alongside any surcharged method, for German users | § 312a Abs. 4 BGB | | | not started |
| Before billing information is collected for the free trial, a clear, conspicuous, unavoidable text disclosure of the trial's material terms (conversion, price, timing, cancellation) is shown | 15 U.S.C. § 8403(1) (ROSCA) | | | not started |
| Consent checkbox for the trial/negative-option feature, where used, renders unchecked by default | 15 U.S.C. § 8403(2); FTC 2021 guidance | | | not started |
| California checkout: renewal offer terms shown clear and conspicuously next to the consent request | Cal. Bus. & Prof. Code § 17602(a)(1) | | | not started |
| New York checkout: offer's material terms shown clear and conspicuously before consent or billing information is requested | N.Y. GBL § 527-a(1)(a) | | | not started |
| A single Impressum page (separate document, not part of this delivery) is linked from the checkout | § 5 Abs. 1 DDG | | | not started |
| US checkout: assent notice sits on the same screen as the control it governs, comparably prominent to surrounding text, visible without scrolling, with no unrelated control between the notice and the button | Meyer v. Uber; Berman v. Freedom Financial Network; Chabolla v. ClassPass | | | not started |
| App-store (Apple/Google) in-app purchase flow: confirm which of the above duties the app store's own purchase flow satisfies on Example Fitness GmbH's behalf, and which still need a parallel path on the web checkout | Open point: see open-points.md | | | not started |

## Confirmation after the order

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Durable-medium order/trial-start confirmation sent within a reasonable time, at the latest before the service starts | Art. 8(7) CRD; § 312f Abs. 2 BGB | | | not started |
| Confirmation email (not a bare account-page link) is a genuine durable medium: storable, reproducible, not alterable by Example Fitness GmbH after sending | Art. 2(10) CRD; Case C-49/11 Content Services | | | not started |
| Withdrawal information (the complete Muster-Widerrufsbelehrung, correctly filled in) is attached to or linked from the order/trial confirmation for EU users | Art. 246a § 1 Abs. 2 EGBGB | | | not started |
| US post-consent notice sent promptly, in retainable form, covering the offer terms, cancellation policy, and how to cancel, including how to cancel the trial before being charged | Cal. Bus. & Prof. Code § 17602(a)(3); N.Y. GBL § 527-a(1)(c) | | | not started |

## Trial conversion and renewal reminders

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Because the trial runs 7 days (31 days or fewer), the California 3-to-21-day pre-trial-end reminder duty does not apply on these facts; confirm trial length has not changed before relying on this | Cal. Bus. & Prof. Code § 17602(b)(1)(A) | | | not started |
| Because the trial runs 7 days (one month or less), the New York 3-to-21-day reminder duty for a trial over one month does not apply on these facts; confirm trial length has not changed before relying on this | N.Y. GBL § 527-a(1)(h) | | | not started |
| Because each renewal term is one month (not one year or more), the California 15-to-45-day annual-term reminder and the New York 15-to-45-day reminder for a one-year-plus term do not apply | Cal. Bus. & Prof. Code § 17602(b)(2); N.Y. GBL § 527-a(1)(f) | | | not started |
| Trial sign-up discloses the post-trial price and exact charge date clearly, at sign-up, since no later pre-billing reminder is separately owed on a 7-day trial | Cal. Bus. & Prof. Code § 17602(a)(1); N.Y. GBL § 527-a(1)(a) | | | not started |
| Record of consent to the trial/renewal offer kept at least 3 years, or 1 year past termination, whichever is longer | Cal. Bus. & Prof. Code § 17602(a)(4), (a)(6) | | | not started |
| Record of when the German withdrawal period started for a given consumer, since a disputed start date is resolved against the trader absent proof | § 361 Abs. 3 BGB | | | not started |

## Price and material changes

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Any mechanism to change ongoing subscription terms, including price, uses an actual offer the user must accept, never a silence-as-acceptance design | BGH, 27 April 2021, XI ZR 26/20 | | | not started |
| On a price increase, California/New York users get clear, conspicuous, retainable notice with cancellation instructions before the change takes effect | Cal. Bus. & Prof. Code § 17602(g)(1), (g)(2); N.Y. GBL § 527-a(1)(g) | | | not started |
| New York: on a price increase (or a price higher than disclosed at offer stage), the system captures affirmative consent to the new price before charging it, or lets the user cancel within at least 14 days after the charge with a pro rata refund | N.Y. GBL § 527-a(1)(b-1) | | | not started |
| EU/German users: a disadvantageous price or feature change is disclosed on a durable medium with reasonable advance notice and a free termination right (at least 30 days) | Art. 19 DCD; § 327r Abs. 2, 3 BGB | | | not started |

## Cancellation

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| All five German prescribed labels checked together as one set before launch: "zahlungspflichtig bestellen," "Verträge hier kündigen," "jetzt kündigen," "Vertrag widerrufen," "Widerruf bestätigen" | § 312j, § 312k, § 356a BGB | | | not started |
| A permanently available German cancellation button ("Verträge hier kündigen") sits on the site/app, leading directly to a confirmation page asking only for: cancellation type and reason (if extraordinary), identification, contract designation, optional end date, and a confirmation channel | § 312k Abs. 1, 2 BGB | | | not started |
| No login step between the German cancellation button and the confirmation page, and no password field on it (pending the 5 November 2026 BGH ruling: design without a login step until that ruling is checked) | § 312k Abs. 2 Satz 3, 4 BGB; KG 5 UKl 10/25, 5 U 6/25; BGH I ZR 272/25, I ZR 275/25 | | | not started |
| German confirmation page ends with a second "jetzt kündigen" button; the user can store the dated declaration on a durable medium | § 312k Abs. 2 Satz 3 Nr. 2, Abs. 3 BGB | | | not started |
| German confirmation page shows nothing beyond the statutory fields and that button: no retention offer, no pause option, no other content | § 312k Abs. 2 Satz 3 BGB; BGH, 16 July 2026, I ZR 200/25 | | | not started |
| German confirmation page does not force an end-date entry; the field lets the user state one but does not require it | § 312k Abs. 2 Satz 3 Nr. 1 Buchst. d, Abs. 5 BGB | | | not started |
| A missing or non-compliant German cancellation button/confirmation page lets the user cancel at any time with no notice period while the defect lasts | § 312k Abs. 6 BGB | | | not started |
| California: online-only cancellation works at will, no obstructing step beyond permitted account authentication | Cal. Bus. & Prof. Code § 17602(d) | | | not started |
| California: a phone, email or other easy cancellation channel exists; calls answered promptly; voicemail resolved within 1 business day if a phone channel is offered | Cal. Bus. & Prof. Code § 17602(c) | | | not started |
| California: retention offer or discount appears only together with the fixed "click to cancel" control (online) or after disclosing the fixed trigger word "cancel" (phone), never instead of or ahead of either | Cal. Bus. & Prof. Code § 17602(e) | | | not started |
| California: cancellation reachable through at least the same medium used to sign up | Cal. Bus. & Prof. Code § 17602(f) | | | not started |
| New York: cancellation offered at any time, as easily as, and through every medium used for, consent | N.Y. GBL § 527-a(1)(d), (d-1) | | | not started |
| New York: no unreasonable condition on cancellation; never refused, obstructed or delayed; a retention offer never blocks it | N.Y. GBL § 527-a(1)(e) | | | not started |
| Cancellation mechanism is at least as easy to use as sign-up and reachable through at least the same medium used to sign up (US federal baseline) | 15 U.S.C. § 8403(3); FTC 2021 guidance | | | not started |
| Subscription-management/billing system records, for each enrollment, the sign-up medium (web checkout vs. app-store IAP), so cancellation can be shown to run through at least that same medium | 16 C.F.R. part 425 practice; FTC 2021 guidance | | | not started |
| App-store (Apple/Google) IAP cancellations: confirm whether the app store's own cancellation path can stand in for the same-medium-as-consent duty, or whether a parallel web cancellation path is also required | Open point: see open-points.md | | | not started |

## Withdrawal (EU and Germany)

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Withdrawal function and confirmation control ("Vertrag widerrufen" / "Widerruf bestätigen," PW-DE-4/PW-DE-5, or PW-EU-2/PW-EU-3 for other EU markets) sit in the app/website interface, permanently available, reachable from every subpage, without a login or registration gate | Art. 11a(1), (3) CRD; § 356a Abs. 1 to 3 BGB | | | not started |
| A user already logged in is not asked to re-identify themselves or the contract to withdraw | § 356a Abs. 2 BGB | | | not started |
| On activation of the confirmation control, an immediate durable-medium acknowledgment states only that the declaration, its content, date and time were received, without implying the withdrawal's validity was already reviewed | § 356a Abs. 4 BGB | | | not started |
| Refund processing uses the original payment method by default, completes within 14 days of being told of the withdrawal, with no fee | Art. 13(1), (2) CRD; § 357 Abs. 2, 3 BGB | | | not started |
| If Stridewell Plus features are made available during the 7-day trial or before the 14-day withdrawal period runs, the flow captures the user's express request and your prior acknowledgment before granting early access, so the proportional-payment paragraph in withdrawal-information.md applies correctly | § 356 Abs. 5 Nr. 2 BGB; § 357a Abs. 2 BGB | | | not started |
| System computes the withdrawal-period start as the date of contract conclusion (services/digital-service rule), and withholds any statement that the period has started until the required EGBGB information was actually given | § 356 Abs. 2, 3 BGB | | | not started |
| For Austria and other non-Germany EU markets, the withdrawal-function and confirmation controls still apply under the directive-level Art. 11a CRD floor; the exact national wording needs country-specific legal verification (Austria's FAGG is not covered by this skill's references) | Art. 11a CRD; open point: see open-points.md | | | not started |

## Records

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Records capture what pre-contractual information was shown to a given user and when, since the trader carries the burden of proof | Art. 6(9) CRD; § 312m Abs. 2 BGB | | | not started |
| Records capture when the German withdrawal period actually started for a given user; a disputed start date is resolved against Example Fitness GmbH absent proof | § 361 Abs. 3 BGB | | | not started |
| Consent records for the US trial/renewal offer kept at least 3 years, or 1 year post-termination, whichever is longer | Cal. Bus. & Prof. Code § 17602(a)(4), (a)(6) | | | not started |

## Open points carried from this register

- Whether the Apple App Store / Google Play in-app purchase flow satisfies the California/New York same-medium cancellation duty and the German cancellation-button duty on Example Fitness GmbH's behalf, or whether a parallel web-based path is also required, is unresolved (see open-points.md).
- Whether Stridewell Plus features are made available before the 14-day EU withdrawal period runs (affecting the proportional-payment mechanics) is unresolved (see open-points.md).
- Whether a login step may sit between the German cancellation button and its confirmation page is pending the 5 November 2026 BGH ruling; design without a login step until that ruling is checked.
- Austria's national transposition of the Consumer Rights Directive withdrawal model is not covered by this skill's references and needs independent verification before the withdrawal-information document ships to Austrian users.

---

*Drafting aid, not legal advice. Law as of 2026-10-20. A qualified lawyer must review this register before Example Fitness GmbH relies on it.*
