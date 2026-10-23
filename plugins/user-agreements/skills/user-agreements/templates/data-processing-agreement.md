# Data processing agreement

Law as of: 2026-10-20

A fill-in template for the contract a controller and a processor (or a business and its service provider or
contractor) put in place for processing personal data on the controller's or business's behalf. The EU module
reproduces the Commission's Article 28(7) standard contractual clauses between controllers and processors in full
(Commission Implementing Decision (EU) 2021/915); the US module adds the processor-contract terms five state privacy
statutes require. Use the EU module alone for a purely EU engagement, the US module alone for a purely US one, or
both together (the clauses do not conflict; where a US statute asks for something the EU clauses already cover, the
module says so instead of duplicating the term).

## How to fill this in

- The EU clauses in Decision (EU) 2021/915 may be adopted in whole or in part, used alongside an individually
  negotiated contract, or folded into a broader services agreement; neither route is preferred by the GDPR, and
  either choice fulfils Art. 28(3) and (4) (Art. 28(6) Regulation (EU) 2016/679; Clause 2(a)). Do not rewrite the
  clause text itself beyond selecting the sub-processor option in Clause 7.7 and completing the Annexes; a party may
  add further clauses or safeguards only where they do not contradict the Clauses or detract from data subjects'
  fundamental rights or freedoms (Clause 2(a)). Where this agreement conflicts with a related agreement between the
  parties, existing now or made later, these Clauses prevail (Clause 4).
- Clause 7.7 offers two sub-processor options; set out both for the client and ask which one the agreement uses, rather than choosing one: Option 1 (prior specific written authorisation for each sub-processor,
  with a stated advance-notice period) or Option 2 (general written authorisation from an agreed list, with a stated
  advance-notice period and an objection window before a change takes effect). Fill in the bracketed time period in
  whichever option is used; the choice decides whether each new sub-processor needs its own signed approval or only
  advance notice the controller can object to.
- Annex I names the parties, Annex II describes the processing (including, where applicable, the sensitive-data
  categories and the safeguards applied to them), Annex III states the technical and organisational security
  measures concretely, not generically, and Annex IV (only needed under sub-processor Option 1) lists the sub-
  processors the controller has specifically authorised. Leave no Annex section blank; a generic restatement of the
  clause text in place of concrete detail does not meet Art. 28(3) (see `references/eu/gdpr-processors-transfers.md`).
- Sort the personal data by role before filling in Annex II: list only the categories the processor handles on the controller's documented instructions. Data the processor uses for its own purposes, such as the contact details of the customer's staff it deals with for its own account management and billing, is the processor's own controller data under Art. 4(7) Regulation (EU) 2016/679; keep it out of Annex II and cover it in the processor's own privacy notice, or raise the classification as an open point where the facts leave it unclear (see `references/eu/gdpr-processors-transfers.md`).
- If this agreement sits inside a broader contract (a master services agreement, a platform terms document), mark
  the clauses clearly as such, for example as a dedicated schedule or annex, rather than scattering their content
  through the surrounding text.
- The international-transfer clause in Clause 7.8(a) covers only an onward transfer the processor itself makes; it
  is not a substitute for the separate Art. 46(2)(c) transfer clauses (Commission Implementing Decision (EU)
  2021/914) that apply when the controller itself exports data to a processor or sub-processor outside the EEA. Where
  that applies, attach the transfer clauses as a further schedule and pick the Module that matches the parties'
  roles (Module Two for a controller exporting to a processor, Module Three for a processor exporting to a
  sub-processor); see `references/eu/gdpr-processors-transfers.md` for the tier structure and the Module choice.
- The US module is not a parallel contract: it adds the specific terms five state statutes require to whatever
  contract governs the processor or service-provider relationship, EU clauses or not. Where a term is already
  covered by the EU clauses above, the US module cross-refers to it rather than repeating it with different wording.
- Check every citation in this template against the cut legal text before relying on it; the citations above and
  below were checked at the time this template was written.
- Before using this template, check whether the relationship is in substance joint controllership rather than
  controller-processor: this template covers only the latter, and a contract that mislabels a genuinely joint
  arrangement as a controller-processor engagement does not fix the mismatch (see
  `references/eu/gdpr-processors-transfers.md`).
- Set any audit or inspection cost allocated to the controller under Clause 7.6 at a level that does not deter it
  from exercising that audit right; costs set clearly disproportionate or excessive to that end do not meet
  Art. 28(3)(h). Where the clauses are embedded in a broader set of standard terms, route any change the processor
  proposes to those terms through direct notice to, and approval by, the controller; publishing the change on the
  processor's website is not enough (see `references/eu/gdpr-processors-transfers.md`).

## Module: EU/EEA controller-to-processor clauses (Decision (EU) 2021/915)

Use this module whenever a controller subject to the GDPR engages a processor to handle personal data on its behalf,
whether or not the processor is itself established in the EEA. The clause numbering below follows the Decision; do
not renumber or reword the clauses themselves beyond completing the bracketed choices.

### Clause 1: purpose and scope

> (a) The purpose of these Standard Contractual Clauses (the Clauses) is to ensure compliance with [...] Article 28(3) and (4) of Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016 on the protection of natural persons with regard to the processing of personal data and on the free movement of such data, and repealing Directive 95/46/EC (General Data Protection Regulation)[...].
>
> (b) The controllers and processors listed in Annex I have agreed to these Clauses in order to ensure compliance with Article 28(3) and (4) of Regulation (EU) 2016/679 and/or Article 29(3) and (4) of Regulation (EU) 2018/1725.
>
> (c) These Clauses apply to the processing of personal data as specified in Annex II.
>
> (d) Annexes I to IV are an integral part of the Clauses.
>
> (e) These Clauses are without prejudice to obligations to which the controller is subject by virtue of Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725.
>
> (f) These Clauses do not by themselves ensure compliance with obligations related to international transfers in accordance with Chapter V of Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725.

[Point (a) lets the drafter choose which Regulation's Article 28(3)/(4) or Article 29(3)/(4) compliance the Clauses
serve; an ordinary commercial engagement with a private-sector controller selects the Regulation (EU) 2016/679
option, not the Regulation (EU) 2018/1725 option that applies only where a Union institution, body, office or
agency is a party. Points (b), (e) and (f) keep the official "and/or" wording naming both Regulations, since the
Decision's own clause text is not split by option at those points.]

### Clause 2: invariability of the Clauses

> (a) The Parties undertake not to modify the Clauses, except for adding information to the Annexes or updating information in them.
>
> (b) This does not prevent the Parties from including the standard contractual clauses laid down in these Clauses in a broader contract, or from adding other clauses or additional safeguards provided that they do not directly or indirectly contradict the Clauses or detract from the fundamental rights or freedoms of data subjects.

### Clause 3: interpretation

> (a) Where these Clauses use the terms defined in Regulation (EU) 2016/679 or Regulation (EU) 2018/1725 respectively, those terms shall have the same meaning as in that Regulation.
>
> (b) These Clauses shall be read and interpreted in the light of the provisions of Regulation (EU) 2016/679 or Regulation (EU) 2018/1725 respectively.
>
> (c) These Clauses shall not be interpreted in a way that runs counter to the rights and obligations provided for in Regulation (EU) 2016/679 / Regulation (EU) 2018/1725 or in a way that prejudices the fundamental rights or freedoms of the data subjects.

### Clause 4: hierarchy

> In the event of a contradiction between these Clauses and the provisions of related agreements between the Parties existing at the time when these Clauses are agreed or entered into thereafter, these Clauses shall prevail.

### Clause 5 (optional): docking clause

Include this clause only where a third entity may later join the agreement as a controller or processor.

> (a) Any entity that is not a Party to these Clauses may, with the agreement of all the Parties, accede to these Clauses at any time as a controller or a processor by completing the Annexes and signing Annex I.
>
> (b) Once the Annexes in (a) are completed and signed, the acceding entity shall be treated as a Party to these Clauses and have the rights and obligations of a controller or a processor, in accordance with its designation in Annex I.
>
> (c) The acceding entity shall have no rights or obligations resulting from these Clauses from the period prior to becoming a Party.

### Clause 6: description of processing

> The details of the processing operations, in particular the categories of personal data and the purposes of processing for which the personal data is processed on behalf of the controller, are specified in Annex II.

### Clause 7: obligations of the parties

**7.1 Instructions**

> (a) The processor shall process personal data only on documented instructions from the controller, unless required to do so by Union or Member State law to which the processor is subject. In this case, the processor shall inform the controller of that legal requirement before processing, unless the law prohibits this on important grounds of public interest. Subsequent instructions may also be given by the controller throughout the duration of the processing of personal data. These instructions shall always be documented.
>
> (b) The processor shall immediately inform the controller if, in the processor's opinion, instructions given by the controller infringe Regulation (EU) 2016/679 / Regulation (EU) 2018/1725 or the applicable Union or Member State data protection provisions.

**7.2 Purpose limitation**

> The processor shall process the personal data only for the specific purpose(s) of the processing, as set out in Annex II, unless it receives further instructions from the controller.

**7.3 Duration of the processing of personal data**

> Processing by the processor shall only take place for the duration specified in Annex II.

**7.4 Security of processing**

> (a) The processor shall at least implement the technical and organisational measures specified in Annex III to ensure the security of the personal data. This includes protecting the data against a breach of security leading to accidental or unlawful destruction, loss, alteration, unauthorised disclosure or access to the data (personal data breach). In assessing the appropriate level of security, the Parties shall take due account of the state of the art, the costs of implementation, the nature, scope, context and purposes of processing and the risks involved for the data subjects.
>
> (b) The processor shall grant access to the personal data undergoing processing to members of its personnel only to the extent strictly necessary for implementing, managing and monitoring of the contract. The processor shall ensure that persons authorised to process the personal data received have committed themselves to confidentiality or are under an appropriate statutory obligation of confidentiality.

**7.5 Sensitive data**

> If the processing involves personal data revealing racial or ethnic origin, political opinions, religious or philosophical beliefs, or trade union membership, genetic data or biometric data for the purpose of uniquely identifying a natural person, data concerning health or a person's sex life or sexual orientation, or data relating to criminal convictions and offences ("sensitive data"), the processor shall apply specific restrictions and/or additional safeguards.

**7.6 Documentation and compliance**

> (a) The Parties shall be able to demonstrate compliance with these Clauses.
>
> (b) The processor shall deal promptly and adequately with inquiries from the controller about the processing of data in accordance with these Clauses.
>
> (c) The processor shall make available to the controller all information necessary to demonstrate compliance with the obligations that are set out in these Clauses and stem directly from Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725. At the controller's request, the processor shall also permit and contribute to audits of the processing activities covered by these Clauses, at reasonable intervals or if there are indications of non-compliance. In deciding on a review or an audit, the controller may take into account relevant certifications held by the processor.
>
> (d) The controller may choose to conduct the audit by itself or mandate an independent auditor. Audits may also include inspections at the premises or physical facilities of the processor and shall, where appropriate, be carried out with reasonable notice.
>
> (e) The Parties shall make the information referred to in this Clause, including the results of any audits, available to the competent supervisory authority/ies on request.

**7.7 Use of sub-processors**

Pick exactly one option and delete the other; fill in the bracketed time period in whichever is kept.

> (a) OPTION 1: PRIOR SPECIFIC AUTHORISATION: The processor shall not subcontract any of its processing operations performed on behalf of the controller in accordance with these Clauses to a sub-processor, without the controller's prior specific written authorisation. The processor shall submit the request for specific authorisation at least [specify time period] prior to the engagement of the sub-processor in question, together with the information necessary to enable the controller to decide on the authorisation. The list of sub-processors authorised by the controller can be found in Annex IV. The Parties shall keep Annex IV up to date.

> OPTION 2: GENERAL WRITTEN AUTHORISATION: The processor has the controller's general authorisation for the engagement of sub-processors from an agreed list. The processor shall specifically inform in writing the controller of any intended changes of that list through the addition or replacement of sub-processors at least [specify time period] in advance, thereby giving the controller sufficient time to be able to object to such changes prior to the engagement of the concerned sub-processor(s). The processor shall provide the controller with the information necessary to enable the controller to exercise the right to object.

> (b) Where the processor engages a sub-processor for carrying out specific processing activities (on behalf of the controller), it shall do so by way of a contract which imposes on the sub-processor, in substance, the same data protection obligations as the ones imposed on the data processor in accordance with these Clauses. The processor shall ensure that the sub-processor complies with the obligations to which the processor is subject pursuant to these Clauses and to Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725.
>
> (c) At the controller's request, the processor shall provide a copy of such a sub-processor agreement and any subsequent amendments to the controller. To the extent necessary to protect business secret or other confidential information, including personal data, the processor may redact the text of the agreement prior to sharing the copy.
>
> (d) The processor shall remain fully responsible to the controller for the performance of the sub-processor's obligations in accordance with its contract with the processor. The processor shall notify the controller of any failure by the sub-processor to fulfil its contractual obligations.
>
> (e) The processor shall agree a third party beneficiary clause with the sub-processor whereby - in the event the processor has factually disappeared, ceased to exist in law or has become insolvent - the controller shall have the right to terminate the sub-processor contract and to instruct the sub-processor to erase or return the personal data.

**7.8 International transfers**

> (a) Any transfer of data to a third country or an international organisation by the processor shall be done only on the basis of documented instructions from the controller or in order to fulfil a specific requirement under Union or Member State law to which the processor is subject and shall take place in compliance with Chapter V of Regulation (EU) 2016/679 or Regulation (EU) 2018/1725.
>
> (b) The controller agrees that where the processor engages a sub-processor in accordance with Clause 7.7. for carrying out specific processing activities (on behalf of the controller) and those processing activities involve a transfer of personal data within the meaning of Chapter V of Regulation (EU) 2016/679, the processor and the sub-processor can ensure compliance with Chapter V of Regulation (EU) 2016/679 by using standard contractual clauses adopted by the Commission in accordance with of Article 46(2) of Regulation (EU) 2016/679, provided the conditions for the use of those standard contractual clauses are met.

### Clause 8: assistance to the controller

> (a) The processor shall promptly notify the controller of any request it has received from the data subject. It shall not respond to the request itself, unless authorised to do so by the controller.
>
> (b) The processor shall assist the controller in fulfilling its obligations to respond to data subjects' requests to exercise their rights, taking into account the nature of the processing. In fulfilling its obligations in accordance with (a) and (b), the processor shall comply with the controller's instructions
>
> (c) In addition to the processor's obligation to assist the controller pursuant to Clause 8(b), the processor shall furthermore assist the controller in ensuring compliance with the following obligations, taking into account the nature of the data processing and the information available to the processor:
>
> (1) the obligation to carry out an assessment of the impact of the envisaged processing operations on the protection of personal data (a 'data protection impact assessment') where a type of processing is likely to result in a high risk to the rights and freedoms of natural persons;
>
> (2) the obligation to consult the competent supervisory authority/ies prior to processing where a data protection impact assessment indicates that the processing would result in a high risk in the absence of measures taken by the controller to mitigate the risk;
>
> (3) the obligation to ensure that personal data is accurate and up to date, by informing the controller without delay if the processor becomes aware that the personal data it is processing is inaccurate or has become outdated;
>
> (4) the obligations in [...] Article 32 of Regulation (EU) 2016/679[...].
>
> (d) The Parties shall set out in Annex III the appropriate technical and organisational measures by which the processor is required to assist the controller in the application of this Clause as well as the scope and the extent of the assistance required.

### Clause 9: notification of personal data breach

> In the event of a personal data breach, the processor shall cooperate with and assist the controller for the controller to comply with its obligations under Articles 33 and 34 of Regulation (EU) 2016/679 or under Articles 34 and 35 of Regulation (EU) 2018/1725, where applicable, taking into account the nature of processing and the information available to the processor.

**9.1 Data breach concerning data processed by the controller**

> In the event of a personal data breach concerning data processed by the controller, the processor shall assist the controller:
>
> (a) in notifying the personal data breach to the competent supervisory authority/ies, without undue delay after the controller has become aware of it, where relevant/(unless the personal data breach is unlikely to result in a risk to the rights and freedoms of natural persons);
>
> (b) in obtaining the following information which, pursuant to [...]Article 33(3) of Regulation (EU) 2016/679[...] shall be stated in the controller's notification, and must at least include:
>
> (1) the nature of the personal data including where possible, the categories and approximate number of data subjects concerned and the categories and approximate number of personal data records concerned;
>
> (2) the likely consequences of the personal data breach;
>
> (3) the measures taken or proposed to be taken by the controller to address the personal data breach, including, where appropriate, measures to mitigate its possible adverse effects.
>
> Where, and insofar as, it is not possible to provide all this information at the same time, the initial notification shall contain the information then available and further information shall, as it becomes available, subsequently be provided without undue delay.
>
> (c) in complying, pursuant to [...]Article 34 of Regulation (EU) 2016/679[...] with the obligation to communicate without undue delay the personal data breach to the data subject, when the personal data breach is likely to result in a high risk to the rights and freedoms of natural persons.

**9.2 Data breach concerning data processed by the processor**

> In the event of a personal data breach concerning data processed by the processor, the processor shall notify the controller without undue delay after the processor having become aware of the breach. Such notification shall contain, at least:
>
> (a) a description of the nature of the breach (including, where possible, the categories and approximate number of data subjects and data records concerned);
>
> (b) the details of a contact point where more information concerning the personal data breach can be obtained;
>
> (c) its likely consequences and the measures taken or proposed to be taken to address the breach, including to mitigate its possible adverse effects.
>
> Where, and insofar as, it is not possible to provide all this information at the same time, the initial notification shall contain the information then available and further information shall, as it becomes available, subsequently be provided without undue delay.
>
> The Parties shall set out in Annex III all other elements to be provided by the processor when assisting the controller in the compliance with the controller's obligations under [...]Articles 33 and 34 of Regulation (EU) 2016/679[...].

### Clause 10: non-compliance with the Clauses and termination

> (a) Without prejudice to any provisions of Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725, in the event that the processor is in breach of its obligations under these Clauses, the controller may instruct the processor to suspend the processing of personal data until the latter complies with these Clauses or the contract is terminated. The processor shall promptly inform the controller in case it is unable to comply with these Clauses, for whatever reason.
>
> (b) The controller shall be entitled to terminate the contract insofar as it concerns processing of personal data in accordance with these Clauses if:
>
> (1) the processing of personal data by the processor has been suspended by the controller pursuant to point (a) and if compliance with these Clauses is not restored within a reasonable time and in any event within one month following suspension;
>
> (2) the processor is in substantial or persistent breach of these Clauses or its obligations under Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725;
>
> (3) the processor fails to comply with a binding decision of a competent court or the competent supervisory authority/ies regarding its obligations pursuant to these Clauses or to Regulation (EU) 2016/679 and/or Regulation (EU) 2018/1725.
>
> (c) The processor shall be entitled to terminate the contract insofar as it concerns processing of personal data under these Clauses where, after having informed the controller that its instructions infringe applicable legal requirements in accordance with Clause 7.1 (b), the controller insists on compliance with the instructions.
>
> (d) Following termination of the contract, the processor shall, at the choice of the controller, delete all personal data processed on behalf of the controller and certify to the controller that it has done so, or, return all the personal data to the controller and delete existing copies unless Union or Member State law requires storage of the personal data. Until the data is deleted or returned, the processor shall continue to ensure compliance with these Clauses.

### Annex I: list of parties

Controller(s): [identity and contact details of the controller(s), and, where applicable, of the controller's data
protection officer]

1. Name: [ ]
   Address: [ ]
   Contact person's name, position and contact details: [ ]
   Signature and accession date: [ ]

Processor(s): [identity and contact details of the processor(s) and, where applicable, of the processor's data
protection officer]

1. Name: [ ]
   Address: [ ]
   Contact person's name, position and contact details: [ ]
   Signature and accession date: [ ]

### Annex II: description of the processing

- Categories of data subjects whose personal data is processed: [ ]
- Categories of personal data processed: [ ]
- Sensitive data processed, if applicable, and the applied restrictions or safeguards that fully take into
  consideration the nature of the data and the risks involved, such as strict purpose limitation, access
  restrictions (including access only for staff having followed specialised training), keeping a record of access to
  the data, restrictions for onward transfers, or additional security measures: [ ]
- Nature of the processing: [ ]
- Purpose(s) for which the personal data is processed on behalf of the controller: [ ]
- Duration of the processing: [ ]
- For processing by (sub-)processors, also specify subject matter, nature and duration of the processing: [ ]

### Annex III: technical and organisational measures, including measures to ensure the security of the data

Describe the measures concretely for this engagement; a generic restatement of the statutory list does not meet
Art. 28(3). Possible measures to describe where they apply: pseudonymisation and encryption of personal data;
ensuring ongoing confidentiality, integrity, availability and resilience of processing systems and services;
restoring availability and access to personal data in a timely manner after a physical or technical incident;
regularly testing, assessing and evaluating the effectiveness of these measures; user identification and
authorisation; protection of data in transit and at rest; physical security of processing locations; event logging;
secure system configuration including default configuration; internal IT and IT security governance; certification
or assurance of processes and products; data minimisation; data quality; limited data retention; accountability; and
support for data portability and erasure.

- [ ]

For a transfer to a sub-processor, also describe the specific technical and organisational measures the
sub-processor will take to be able to provide assistance to the controller: [ ]

### Annex IV: list of sub-processors

Complete only where Clause 7.7(a) Option 1 (prior specific authorisation) is used.

The controller has authorised the use of the following sub-processors:

1. Name: [ ]
   Address: [ ]
   Contact person's name, position and contact details: [ ]
   Description of the processing, including a clear delimitation of responsibilities where several sub-processors
   are authorised: [ ]

## Module: US state service-provider and processor terms

Use this module alongside, or instead of, the EU module when the engagement also or only involves personal data
covered by a US state privacy law. Five states currently require specific processor-contract content; each entry
below names its own trigger and citation, so check which statutes apply to this engagement before including a
subsection.

### California: CCPA service-provider and contractor contract

Triggers whenever a CCPA-covered business discloses personal information to a vendor for a business purpose and
wants that vendor treated as a service provider or contractor rather than a third party (Cal. Civ. Code
1798.140(ag), (j)). Without a contract meeting every point below, the vendor is not a service provider, contractor,
or authorized third party, and the disclosure to it may itself be a sale or sharing that triggers the consumer's
opt-out rights (7 CCR 7050(e)).

The contract:

- Names the limited and specific business purposes for which the recipient may retain, use, or disclose the data
  (Cal. Civ. Code 1798.140(ag), (j); 1798.100(d)(1)).
- Prohibits the recipient from selling or sharing the personal information (Cal. Civ. Code 1798.140(ag)(1), (j)(1)).
- Prohibits the recipient from retaining, using, or disclosing the personal information for any purpose other than
  the business purposes specified in the contract, or outside the direct business relationship between the business
  and the recipient, including combining it with personal information the recipient receives from or on behalf of
  another source, except as the CCPA allows (Cal. Civ. Code 1798.140(ag)(1), (j)(1); 7 CCR 7051(a)).
- Requires the recipient to certify that it understands the restrictions above and will comply with them (Cal. Civ.
  Code 1798.140(ag)(1), (j)(1)).
- Lets the business monitor the recipient's compliance at least annually, not merely take reasonable steps with no
  stated cadence (Cal. Civ. Code 1798.140(ag), (j)), and separately lets the business take reasonable steps to check
  the recipient's compliance with its obligations (Cal. Civ. Code 1798.100(d)(3)).
- Requires the recipient to notify the business if it can no longer meet its obligations under the contract (Cal.
  Civ. Code 1798.100(d)(4)).
- Lets the business, upon notice of the recipient's unauthorized use of the personal information, take reasonable
  steps to stop and remediate that unauthorized use (Cal. Civ. Code 1798.100(d)(5)).
- Flows the same restrictions and requirements down to any subcontractor the recipient engages, through a written
  contract (7 CCR 7051(a)).

A service provider or contractor that is itself a business, and that collects, maintains, or sells personal
information outside its contracted role for the disclosing business, must comply with the CCPA directly for that
outside-role data; this contract does not change that (7 CCR 7050(d)). See `references/us-states/ca-ccpa.md`.

### Virginia, Colorado, Connecticut: the common processor-contract core

The VCDPA, the Colorado Privacy Act, and the CTDPA each require a written, binding processor contract with a largely
parallel set of terms; state the common content once, then note the one difference below.

The contract:

- Clearly sets out processing instructions, the nature and purpose of the processing, the type of data subject to
  processing, the duration of the processing, and the rights and obligations of both parties (Va. Code
  59.1-579(B); C.R.S. 6-1-1305(5); Conn. Gen. Stat. Sec. 42-521(b)).
- Binds every person processing the data under a duty of confidentiality, whether contractual or under an
  appropriate statutory obligation (Va. Code 59.1-579(B); C.R.S. 6-1-1305(3)(a); Conn. Gen. Stat. Sec. 42-521(b)).
- Requires the processor, at the controller's direction, to delete or return all personal data to the controller at
  the end of the provision of services, unless retention of the personal data is required by law (Va. Code
  59.1-579(B); C.R.S. 6-1-1305(5); Conn. Gen. Stat. Sec. 42-521(b)).
- Requires the processor to make available to the controller, on reasonable request, all information in its
  possession necessary to demonstrate the processor's compliance with its obligations (Va. Code 59.1-579(B); C.R.S.
  6-1-1305(5); Conn. Gen. Stat. Sec. 42-521(b)).
- Requires the processor to allow for, and cooperate with, reasonable assessments by the controller or the
  controller's designated assessor; or, at the processor's choice, to arrange for a qualified and independent
  assessor to conduct an assessment of the processor's policies and technical and organisational measures in support
  of the obligations under this contract, using an appropriate and accepted control standard or framework and
  assessment procedure, with the processor providing a report of that assessment to the controller on request
  (Va. Code 59.1-579(B); C.R.S. 6-1-1305(5); Conn. Gen. Stat. Sec. 42-521(b)). Colorado requires that, where the
  processor chooses the independent-assessor route instead of the controller's own audit, the assessment is
  conducted at least annually and at the processor's expense; Virginia and Connecticut state the same independent-
  assessor alternative without an annual-frequency or cost-allocation term of their own (C.R.S. 6-1-1305(5)(d)(II)(B)).
- Requires a written contract with each subcontractor the processor engages, binding the subcontractor to the
  processor's own obligations with respect to the personal data, and gives the controller a chance to object before
  the subcontractor is engaged (Va. Code 59.1-579(B); C.R.S. 6-1-1305(3)(b), (4); Conn. Gen. Stat. Sec. 42-521(b)).
- States that neither party's liability for its own role is reduced by this division of duties, and that whether a
  party is acting as a controller or a processor for a given activity is a question of fact rather than of
  contractual label (Va. Code 59.1-579(C), (D); C.R.S. 6-1-1305(6), (7); Conn. Gen. Stat. Sec. 42-521(d)).

See `references/us-states/va-vcdpa.md`, `references/us-states/co-cpa.md`, and `references/us-states/ct-ctdpa.md` for
each statute's own scope, thresholds, and exemptions; the three contract-term lists above are drawn from the same
subsections of the model text that all three states adopted, each kept as that state's own citation.

### Texas: TDPSA processor contract

Largely the same core terms, with two differences from the Virginia/Colorado/Connecticut model: the Texas statute
states the audit-cooperation duty as an explicit either/or choice for the processor, and does not include an express
non-reduction-of-liability sentence of its own.

The contract:

- States clear processing instructions, the nature and purpose of processing, the type of data processed, the
  duration of processing, and the rights and obligations of both parties (Tex. Bus. and Com. Code 541.104(b)).
- Binds every person who processes the data under a duty of confidentiality (Tex. Bus. and Com. Code 541.104(c)(1)).
- Requires the processor, at the controller's direction, to delete or return all personal data once the service ends,
  unless law requires retention (Tex. Bus. and Com. Code 541.104(c)(2)).
- Requires the processor to make compliance information available to the controller on reasonable request (Tex. Bus.
  and Com. Code 541.104(c)(3)).
- Requires the processor to allow and cooperate with reasonable assessments by the controller or its designated
  assessor, or, at the processor's choice, to instead arrange for a qualified independent assessor's report on
  request (Tex. Bus. and Com. Code 541.104(c)(4)).
- Binds any subcontractor the processor engages, by written contract, to the processor's own requirements under this
  contract (Tex. Bus. and Com. Code 541.104(c)(5)).

See `references/us-states/tx-tdpsa.md`.

### Picking the right combination

- A processor engagement touching California, Virginia, Colorado, Connecticut, and Texas personal data at once uses
  the CCPA section for the California-covered data and the common VCDPA/CPA/CTDPA core plus the Texas variant for
  the rest; the terms are compatible (none contradicts another), so one combined schedule can state all of them
  rather than running separate contracts per state.
- Where the EU module above also applies to the same processor relationship, the EU Clause 7.6(c) audit-and-
  information duty and the US states' assessment-cooperation duty cover materially the same ground; state both
  citations against the single audit and compliance-information clause rather than drafting two separate audit
  regimes for the same engagement.
