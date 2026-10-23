---
title: "B2B SaaS for manufacturers: implementation requirements"
description: The hand-over register telling product and engineering what to build so the drafts are true.
---

*Fictional product, illustrative draft. Not legal advice.*

# Implementation requirements - Example Machines GmbH / Spindlewise

Law as of: 20 October 2026. This is the hand-over register from the legal drafts to Example Machines' product,
engineering and operations teams. Each row names one thing the product or process must do, the rule it
rests on, who owns building and checking it, what evidence proves it is done, and its status. Fill in
Owner and Status; Requirement, Legal basis and Evidence come from the drafts and do not change without
a change to them.

Status values: not started, in progress, built, verified.

Scope note: this register is scoped to what the B2B subscription terms and the Data Processing
Agreement actually require. It does not carry the consumer-facing checkout, cancellation-button or
cookie-consent items the full template normally lists, since none of them apply to Spindlewise's
business-only customer base (see `annotations.md` applicability table).

## Sign-up and contract formation

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Online ordering flow records who at the Customer's purchasing department submitted the Order Form and confirms that person has (or appears to have) authority to bind the Customer | `master-subscription-terms.md` Section 2 | | | not started |
| Order Form and the Master Subscription Terms are kept storable and reproducible by the Customer after signing, not displayed once and gone | `master-subscription-terms.md` Section 2; Art. 10(3), (4) Directive 2000/31/EC | | | not started |
| Checkout or order flow gives the Customer a way to spot and correct an input error before submitting the Order Form | `master-subscription-terms.md` Section 2; Art. 11(2) Directive 2000/31/EC | | | not started |
| System sends an electronic order acknowledgment without undue delay once an Order Form is submitted online | `master-subscription-terms.md` Section 2; Art. 11(1) Directive 2000/31/EC | | | not started |

## Billing and price changes

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Invoicing process issues the annual invoice at the start of each term and tracks the 30-day payment window | `master-subscription-terms.md` Section 4 | | | not started |
| Suspension-for-non-payment process gives 14 days' written notice before suspending access | `master-subscription-terms.md` Section 4 | | | not started |
| Price-change and terms-change notices go out at least 60 days (or the figure Example Machines finally sets) before the change takes effect, in writing, to the Customer's contract contact | `master-subscription-terms.md` Sections 5, 6 | | | not started |
| Any mid-term change (new terms or price) is applied prospectively from the next renewal term, never retroactively to a term already running, unless the Customer expressly agrees otherwise | `master-subscription-terms.md` Section 6 | | | not started |

## Machine Data access (Data Act)

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Pre-contract disclosure page or Order Form annex states the actual type, format and estimated volume of Machine Data Spindlewise generates per connected machine, whether it is continuous/real-time, and the retention period | `master-subscription-terms.md` Section 7; Art. 3(2)(a) to (d) Regulation (EU) 2023/2854 | | | not started |
| Platform provides a self-service export function letting the Customer retrieve its own Machine Data in a structured, machine-readable format, free of charge | `master-subscription-terms.md` Section 7; Art. 3(1) Regulation (EU) 2023/2854 | | | not started |
| Where self-service export does not cover a specific data category, a support process exists to fulfil a manual access request without undue delay, free of charge | `master-subscription-terms.md` Section 7; Art. 4(1) Regulation (EU) 2023/2854 | | | not started |
| A documented process exists for a Customer to name a third party to receive its Machine Data, routed through the same export mechanism, with no more log data kept than necessary | `master-subscription-terms.md` Section 7; Art. 5(1), 4(5) Regulation (EU) 2023/2854 | | | not started |
| A written, reasoned refusal process exists for the rare case Example Machines restricts a sharing request on security or trade-secret grounds, naming the competent German Data Act authority once designated | `master-subscription-terms.md` Section 7; Art. 4(2), (3), (6) to (9) Regulation (EU) 2023/2854 | | | not started |
| Contract template for any named third-party data recipient includes the no-competing-product and no-gatekeeper-routing restrictions | `master-subscription-terms.md` Section 7; Art. 6(1), (2), 5(3) Regulation (EU) 2023/2854 | | | not started |

## Personal data (DPA)

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Current, accurate sub-processor register maintained (Annex IV of the DPA or a public sub-processor page it points to) | `data-processing-agreement.md` Clause 7.7; `backend-subprocessor-change-memo.md` | | | not started |
| 30-day advance-notice process exists for adding or replacing a sub-processor, with a logged objection window per customer | `data-processing-agreement.md` Clause 7.7, Option 2; `backend-subprocessor-change-memo.md` | | | not started |
| Breach-notification process notifies affected customers without undue delay after Example Machines becomes aware of a breach, with the Clause 9.2 minimum content (nature, contact point, consequences, measures) | `data-processing-agreement.md` Clause 9 | | | not started |
| Deletion/return-on-termination process executes within 30 days of contract end, for both Machine Data and Account Data, with a deletion certificate available on request | `master-subscription-terms.md` Section 9; `data-processing-agreement.md` Clause 10(d) | | | not started |
| Access controls restrict Account Data (login credentials, shift logs) to staff who need it, logged, under a confidentiality commitment | `data-processing-agreement.md` Clause 7.4(b); Annex III | | | not started |
| Access controls restrict the site contact's own controller data (name, job title, email address, phone number) the same way, on Example Machines' own account-management policy rather than the DPA, since this data is not processed under the Customer's instruction | `master-subscription-terms.md` Section 8; `data-processing-agreement.md` scope note; `open-points.md` item 9 | | | not started |
| Annex III (technical and organisational measures) is completed with Example Machines' actual security measures, not a generic restatement of the statutory list, before the DPA is signed with any customer | `data-processing-agreement.md` Annex III | | | not started |
| Support-ticket intake process flags and avoids recording sensitive data (health, etc.) in ticket free text where not operationally necessary | `data-processing-agreement.md` Clause 7.5 | | | not started |
| International-transfer mechanism (DPF adequacy or SCC Module) is confirmed and documented for the support-ticketing vendor before the DPA is finalized with any customer | `data-processing-agreement.md` Clause 7.8; `open-points.md` item 5 | | | not started |
| Audit-cooperation process (self-run assessment or independent assessor's report) is built as a real, workable process, with any cost allocation set so it does not deter a customer from exercising the right | `data-processing-agreement.md` Clause 7.6; Texas processor terms | | | not started |

## California CCPA (conditional - only if the threshold is met; see open-points.md)

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Confirm whether Example Machines crosses a CCPA threshold before building any CCPA-specific process | `open-points.md` item 1; Cal. Civ. Code 1798.140(d) | | | not started |
| If applicable: service-provider contract terms (purpose limitation, no sale/share, certification, annual monitoring) are in place with the US ticketing vendor for any California-resident Account Data it processes | `data-processing-agreement.md`, Part B California section | | | not started |

## Texas TDPSA

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Confirm whether Example Machines qualifies as an SBA small business (affects which TDPSA duties apply) | `open-points.md` item 2 | | | not started |
| Processor-contract terms (confidentiality, delete/return on direction, compliance information, audit cooperation, subcontractor flow-down) are in place with every processor and sub-processor touching Texas-resident Account Data | `data-processing-agreement.md`, Part B Texas section; Tex. Bus. and Com. Code 541.104(b), (c) | | | not started |

## Hosting and sub-processor changes

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Hosting provider and region confirmed and documented (currently: "a cloud region in Germany") | `open-points.md` item 4; `master-subscription-terms.md` Section 7 | | | not started |
| Process exists to flag a hosting-location change as a bigger-than-ordinary sub-processor change, with its own separate customer communication | `backend-subprocessor-change-memo.md` | | | not started |
| Vendor contract template for a new backend sub-processor includes the Clause 7.7(b) flow-down obligations and the Clause 7.7(e) third-party-beneficiary clause | `backend-subprocessor-change-memo.md`; `data-processing-agreement.md` Clause 7.7 | | | not started |

## Records

| Requirement | Legal basis | Owner | Evidence | Status |
| --- | --- | --- | --- | --- |
| Records show what pre-contract Data Act disclosures (Section 7) were given to a specific customer and when | `master-subscription-terms.md` Section 7; Art. 3(2), (3) Regulation (EU) 2023/2854 | | | not started |
| Records show every sub-processor notice sent, to which customers, on what date, and the resolution of any objection received | `backend-subprocessor-change-memo.md` | | | not started |
| Records show, for each cross-border transfer of Account Data, the destination, the mechanism relied on, and the Clause 14 warranty assessment where SCCs are used | `data-processing-agreement.md` Clause 7.8; `open-points.md` item 5 | | | not started |

## Open points to raise

- Whether the pre-contract Data Act disclosure (type, format, estimated volume and retention of Machine
  Data) is best delivered as a standing page linked from the Order Form, or as an annex to the Order
  Form itself; this is a product/legal design choice the drafts do not resolve.
- Whether Spindlewise's self-service export function already exists, or needs to be built; this
  determines whether Section 7's "by default" access paragraph is currently true or aspirational.
- Whether Example Machines' support-ticketing system already supports redacting or flagging sensitive content in
  ticket free text, or whether this needs a new feature or a staff-training control instead.
