# EU Artificial Intelligence Act

Citation: Regulation (EU) 2024/1689 of the European Parliament and of the Council of 13 June 2024
laying down harmonised rules on artificial intelligence and amending Regulations (EC) No 300/2008,
(EU) No 167/2013, (EU) No 168/2013, (EU) 2018/858, (EU) 2018/1139 and (EU) 2019/2144 and Directives
2014/90/EU, (EU) 2016/797 and (EU) 2020/1828
Version: consolidated 2026-07-27
Official text: https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02024R1689-20260727
Law as of: 2026-10-20

This file covers the parts of the Regulation that change what a terms document, privacy notice or
product has to say or do: who the Regulation reaches, the roles it assigns, the AI-literacy duty,
the prohibited practices, the transparency and disclosure duties, and the conditional permission to
process special-category data for bias work. It does not cover the high-risk AI system
classification and requirements regime (Chapter III, Sections 1 to 3), the general-purpose AI model
rules, or the governance, market-surveillance and penalty provisions; those sit outside the source
this file is built from.

## When it applies

- The Regulation reaches a provider placing an AI system or a general-purpose AI model on the Union
  market, wherever that provider is established; a deployer established or located in the Union; a
  provider or deployer established in a third country whose AI system's output is used in the
  Union; an importer or distributor of an AI system; a product manufacturer placing an AI system on
  the market under its own name together with its product; an authorised representative of a
  provider not established in the Union; and an affected person located in the Union (Art. 2(1),
  points (a) to (g)).
- An AI feature offered to people in the Union from outside the Union is in scope on the strength of
  where its output is used, not where the company offering it sits (Art. 2(1)(c)).
- The Regulation does not reach areas outside the scope of Union law, Member State competence over
  national security, or an AI system placed on the market, put into service or used exclusively for
  military, defence or national-security purposes (Art. 2(3)).
- It does not reach research, testing or development of an AI system or AI model before that system
  or model is placed on the market or put into service; testing in real-world conditions is not
  covered by that exclusion and stays in scope (Art. 2(8)).
- A second, separate exclusion removes "AI systems or AI models, including their output,
  specifically developed and put into service for the sole purpose of scientific research and
  development" from scope outright. Unlike the Art. 2(8) exclusion, this one carries no
  before-market-placement limit, so it can cover a system that is already live as long as its sole
  purpose stays scientific research and development; a research-only product should rely on both
  exclusions together, not on Art. 2(8) alone, since they cover different stretches of its life
  (Art. 2(6)).
- It does not reach the obligations of a deployer who is a natural person using an AI system in the
  course of a purely personal, non-professional activity (Art. 2(10)).
- It does not reach an AI system released under a free and open-source licence, unless that system
  is placed on the market or put into service as a high-risk AI system or as a system falling under
  Art. 5 (prohibited practices) or Art. 50 (transparency obligations); an open-source component used
  that way still carries those clauses (Art. 2(12)).
- The Regulation does not affect Regulation (EU) 2016/679 (GDPR), Regulation (EU) 2018/1725,
  Directive 2002/58/EC or Directive (EU) 2016/680, other than through the specific carve-outs this
  Regulation makes in Art. 4a and Art. 59; personal-data law keeps applying underneath it (Art.
  2(7)).
- It does not affect Union consumer-protection or product-safety law, or Chapter II of Regulation
  (EU) 2022/2065 on the liability of providers of intermediary services (Art. 2(5), 2(9)).
- It does not stop the Union or a Member State from keeping or introducing worker-protection rules
  more favourable than this Regulation for the use of AI systems by employers, or from encouraging
  more favourable collective agreements; a terms document for an employee-facing deployment should
  not assume this Regulation sets the ceiling (Art. 2(11)).

## What the documents must say

### Roles

- Use provider, deployer and downstream provider as the Regulation defines them, not as generic
  labels such as customer or user: a provider develops an AI system or general-purpose AI model, or
  has one developed, and places it on the market or puts it into service under its own name or
  trademark, paid or free (Art. 3, point 3); a deployer uses an AI system under its own authority,
  except where that use is a purely personal, non-professional activity (Art. 3, point 4); a
  downstream provider is a provider of an AI system, including a general-purpose AI system, that
  integrates an AI model, whether that model is its own vertically integrated model or supplied by
  another entity under contract (Art. 3, point 68).
- A product built on a third-party foundation model is itself a downstream provider and carries its
  own provider-side duties for its own AI system, even while depending on another party's model
  (Art. 3, point 68).
- The AI-literacy duty, the prohibited-practices duty and the transparency duties each attach to a
  specific role defined this way, not to a generic customer or user label (Art. 4(1); Art. 5(1); Art.
  50(1) to (4)).

### AI literacy

- Describe, or build into an onboarding flow, measures to support the AI literacy of staff and other
  people who operate or use the AI system on the provider's or deployer's behalf, taking into account
  that person's technical knowledge, experience, education and training, the context of use, and the
  people or groups the system will be used on. This is a duty to take measures, not to guarantee any
  individual reaches a specific literacy level (Art. 4(1)).
- The duty falls on both providers and deployers; a terms or partner agreement between a provider
  and a business deployer should not shift the whole burden to one side, since each role carries it
  for its own staff and representatives (Art. 4(1)).

### AI-interaction disclosure

- Where a feature lets a natural person interact directly with an AI system, state at the latest at
  the first interaction, clearly and distinguishably, that the person is interacting with an AI
  system, unless this is obvious from the circumstances and context of use to a natural person who
  is reasonably well-informed, observant and circumspect (Art. 50(1), first sentence; Art. 50(5)).
- This duty does not apply to an AI system authorised by law to detect, prevent, investigate or
  prosecute criminal offences, subject to appropriate safeguards for third parties' rights and
  freedoms, unless that system is available for the public to report a criminal offence; a
  consumer-facing product cannot rely on this carve-out (Art. 50(1), second sentence).

### Synthetic-content marking

- Where a feature, including one built on a general-purpose AI system, generates synthetic audio,
  image, video or text content, mark the output in a machine-readable format, detectable as
  artificially generated or manipulated, using technical solutions that work reliably, hold up over
  time and interoperate across systems, as far as this is technically feasible, taking into account
  the type of content, the cost of implementation and the state of the art (Art. 50(2), first and
  second sentences).
- This duty does not apply to the extent the AI system performs an assistive function for standard
  editing, or does not substantially alter the input data the deployer provided or its semantics, or
  where the system is authorised by law for the criminal-offence purposes above; whether the
  assistive-function or no-substantial-alteration carve-out applies is a question about what the
  feature actually does, not something a clause can assert on its own (Art. 50(2), third sentence).

### Emotion-recognition and biometric-categorisation notice

- Where a feature exposes natural persons to an emotion recognition system or a biometric
  categorisation system, inform the exposed persons of the system's operation, and process any
  personal data under the GDPR, Regulation (EU) 2018/1725 or Directive (EU) 2016/680, as applicable
  (Art. 50(3), first sentence).
- This duty does not apply to a system used for biometric categorisation or emotion recognition that
  is permitted by law to detect, prevent or investigate criminal offences, subject to appropriate
  safeguards for third parties' rights and freedoms and in accordance with Union law (Art. 50(3),
  second sentence).
- Check the Art. 5(1)(f) and (g) prohibitions first: this notice duty applies only to a feature that
  is itself lawful under Art. 5; disclosure under Art. 50(3) does not cure a practice Art. 5
  prohibits outright (Art. 5(1)(f), (g); Art. 50(3)).

### Deep-fake and AI-generated public-interest text disclosure

- Where a feature generates or manipulates image, audio or video content that is a deep fake,
  disclose that the content has been artificially generated or manipulated (Art. 50(4), first
  paragraph, first sentence).
- Where the content forms part of an evidently artistic, creative, satirical, fictional or similar
  work or programme, this disclosure narrows to noting the existence of such generated or
  manipulated content in a way that does not hamper displaying or enjoying the work (Art. 50(4),
  first paragraph, third sentence).
- This duty does not apply where the use is authorised by law to detect, prevent, investigate or
  prosecute a criminal offence (Art. 50(4), first paragraph, second sentence).
- Where a feature generates or manipulates text published with the purpose of informing the public
  on matters of public interest, disclose that the text has been artificially generated or
  manipulated (Art. 50(4), second paragraph, first sentence).
- This text-disclosure duty does not apply where the use is authorised by law for the same
  criminal-offence purposes, or where the AI-generated content underwent human review or editorial
  control and a natural or legal person holds editorial responsibility for publishing it; relying on
  this carve-out needs an actual editorial-responsibility structure behind the product, not a
  disclaimer alone (Art. 50(4), second paragraph, second sentence).

### Timing and form of every Art. 50 disclosure

- Give all information required by Art. 50(1) to (4) to the natural persons concerned clearly and
  distinguishably, at the latest at the time of the first interaction or exposure, conforming to
  applicable accessibility requirements; a late or buried notice does not meet this standard (Art.
  50(5)).
- These transparency duties sit alongside, not instead of, the high-risk requirements in Chapter III
  and any other transparency obligation under Union or national law for deployers of AI systems
  (Art. 50(6)).

### Special-category data for bias detection and correction

- A provider of a high-risk AI system may exceptionally process special categories of personal data
  to the extent strictly necessary for bias detection and correction under Art. 10(2), points (f)
  and (g), subject to appropriate safeguards for fundamental rights and freedoms, and only where, in
  addition to the GDPR, Regulation (EU) 2018/1725 and Directive (EU) 2016/680 as applicable, all six
  of the following are met: the goal cannot be effectively met by processing other data, including
  synthetic or anonymised data; the special-category data is subject to technical re-use limits and
  state-of-the-art security and privacy-preserving measures, including pseudonymisation; it is
  subject to measures securing it, with suitable safeguards, strict access controls and documentation
  to avoid misuse and keep access to authorised persons with confidentiality obligations; it is not
  transmitted, transferred or otherwise accessed by other parties; it is deleted once the bias is
  corrected or its retention period ends, whichever comes first; and the GDPR, Regulation (EU)
  2018/1725 or Directive (EU) 2016/680 processing records state why the processing was strictly
  necessary and why other data could not achieve the goal (Art. 4a(1), points (a) to (f)).
- A provider or deployer of other AI systems and models, and a deployer of a high-risk AI system, may
  process special-category data under the same six conditions where strictly necessary to detect and
  correct biases likely to affect health or safety, harm fundamental rights or lead to prohibited
  discrimination, in particular where data outputs feed into future operations (Art. 4a(2)).
- This is a conditional permission, not a mandate: nothing in Art. 4a creates an obligation to run
  bias detection and correction, so a privacy notice or DPA clause should present it as available,
  safeguarded processing, not a legal requirement (Art. 4a(2), closing sentence).

## What the documents must not say

- No product description, feature list or marketing page may describe, as something the product
  does, an AI system using subliminal techniques beyond a person's consciousness, or purposefully
  manipulative or deceptive techniques, with the objective or effect of materially distorting a
  person's or group's behaviour by appreciably impairing their ability to make an informed decision,
  causing a decision they would not otherwise have taken, in a way that causes or is reasonably
  likely to cause significant harm; this is prohibited outright (Art. 5(1)(a)).
- No product may describe an AI system exploiting a vulnerability due to age, disability, or a
  specific social or economic situation, with the objective or effect of materially distorting that
  person's or group's behaviour in a way that causes or is reasonably likely to cause significant
  harm; this is prohibited outright (Art. 5(1)(b)).
- A feature generating or manipulating realistic images, video, audio or similar material of an
  identifiable natural person's intimate parts, or of an identifiable natural person engaged in
  sexually explicit activity, is lawful only with that person's freely given, specific, informed,
  unambiguous and explicit consent to the generation or manipulation itself, not merely to the
  underlying service; without it, the practice is prohibited (Art. 5(1)(ba)). This prohibition
  applies only where that generation or manipulation is the system's intended purpose, or where its
  design, training, architecture, capabilities or user-facing functions make that outcome a
  reasonably foreseeable and reproducible result without significant technical modification and the
  system lacks reasonable, adequate technical and other safeguards against it, taking into account
  reasonably foreseeable misuse and correcting observed or reported misuse (Art. 5(1a)(a)); on the
  use side, it applies only where the deployer uses the system for that purpose (Art. 5(1a)(b)).
  Manipulating material in a way that does not increase the exposure of depicted intimate parts and
  does not alter the nature of depicted sexually explicit activity is not "manipulation" for this
  prohibition (Art. 5(1b)).
- A product may not generate or manipulate material or a performance within the meaning of Art. 2,
  points (c) and (e), of Directive 2011/93/EU; this is prohibited except where a "without right"
  defence applies under national law (Art. 5(1)(bb)).
- No product may evaluate or classify natural persons or groups over time by social behaviour or
  known, inferred or predicted personal or personality characteristics where the resulting score
  leads to detrimental or unfavourable treatment in social contexts unrelated to where the data was
  originally generated or collected, or to detrimental or unfavourable treatment unjustified or
  disproportionate to the person's social behaviour or its gravity; social scoring on this model is
  prohibited outright (Art. 5(1)(c), points (i), (ii)).
- No product may assess or predict the risk of a natural person committing a criminal offence based
  solely on profiling that person or assessing their personality traits and characteristics; this
  prohibition does not cover an AI system supporting a human assessment of a person's involvement in
  a criminal activity that is already based on objective and verifiable facts directly linked to that
  activity (Art. 5(1)(d)).
- No product may create or expand a facial recognition database through the untargeted scraping of
  facial images from the internet or CCTV footage; this is prohibited outright (Art. 5(1)(e)).
- No product may infer the emotions of a natural person in the workplace or in an education
  institution; this is prohibited except where the AI system is intended for medical or safety
  reasons (Art. 5(1)(f)).
- No biometric categorisation feature may categorise natural persons individually based on their
  biometric data to deduce or infer their race, political opinions, trade union membership, religious
  or philosophical beliefs, sex life or sexual orientation; this is prohibited outright. It does not
  cover labelling or filtering of lawfully acquired biometric datasets, such as images, based on
  biometric data, or categorising biometric data in the area of law enforcement (Art. 5(1)(g)).
  Outside law enforcement, biometric data processing still has to meet Art. 9 of Regulation (EU)
  2016/679 (Art. 5(1), first subparagraph, point (h), last sentence).
- A general consumer product may not claim a real-time remote biometric identification capability
  for publicly accessible spaces: that use is prohibited for law enforcement purposes unless strictly
  necessary for the targeted search for specific victims of abduction, trafficking or sexual
  exploitation, or for missing persons; the prevention of a specific, substantial and imminent threat
  to life or physical safety, or a genuine and present or genuine and foreseeable terrorist-attack
  threat; or the localisation or identification of a person suspected of an offence listed in Annex
  II and punishable in the Member State concerned by a custodial sentence or detention order of at
  least four years, and even then only subject to prior judicial or binding independent
  administrative authorisation, a completed fundamental-rights impact assessment, EU database
  registration, and the other conditions in Art. 5(2) to (6) (Art. 5(1)(h), points (i) to (iii); Art.
  5(2) to 5(6)).
- No decision producing an adverse legal effect on a person may rest solely on the output of a
  real-time remote biometric identification system used under the law-enforcement exception (Art.
  5(3), second paragraph, last sentence).
- None of these prohibitions limits any other prohibition that applies where the same AI practice
  infringes other Union law; a practice can be unlawful under Art. 5 and under separate Union law at
  the same time (Art. 5(8)).

## Product behaviour it assumes

- The product can identify, for each feature, which Art. 3 role (provider, deployer, downstream
  provider) it plays, since the AI-literacy, prohibited-practices and transparency duties attach to
  that role rather than to a generic account type.
- Any chatbot, voice assistant or other feature where a person interacts directly with an AI system
  shows an AI-interaction label at the first interaction, rather than leaving it to a mention
  buried in the terms (Art. 50(1)).
- Any feature generating synthetic audio, image, video or text carries a machine-readable mark
  detectable as artificially generated or manipulated, unless the feature's actual behaviour (an
  assistive, standard-editing function with no substantial alteration of the deployer's input or its
  semantics) genuinely meets the carve-out (Art. 50(2)).
- Any feature exposing people to an emotion-recognition or biometric-categorisation system shows an
  operation notice to the exposed person, and the underlying system does not fall into the Art.
  5(1)(f) or (g) prohibitions in the first place (Art. 50(3); Art. 5(1)(f), (g)).
- Any feature generating or manipulating deep-fake image, audio or video content, or AI-generated
  text published on matters of public interest, carries the matching disclosure, unless the
  product can actually show the artistic/satirical/fictional narrowing or a real editorial-review
  and editorial-responsibility process (Art. 50(4)).
- A consent record for Art. 5(1)(ba) content capture is freely given, specific, informed,
  unambiguous and explicit, and it covers the generation or manipulation itself.
- Where special-category data is processed for bias detection or correction under Art. 4a, the
  product keeps the processing record stating why other data could not meet the goal, enforces the
  access, security and retention-and-deletion conditions, and deletes the data once the bias is
  corrected or the retention period ends, whichever comes first.
- No feature is built, offered or described in a way that performs any Art. 5(1) prohibited practice;
  these cannot be cured by a disclosure or consent clause, except the narrow Art. 5(1)(ba) consent
  route, which is a defence to that one prohibition and not a general consent mechanism for the
  others.

## Prescribed wording

None: this file's source fixes duties, prohibitions, conditions and dates, not a specific wording a
terms document or UI label must reproduce.

## Dates

- The Regulation entered into force on the twentieth day following its publication in the Official
  Journal of the European Union, and applies from 2 August 2026 as the general rule; this date has
  passed (Art. 113, first and second paragraphs).
- Chapters I and II applied from 2 February 2025; this date has passed (Art. 113(a)).
- Chapter III Section 4, Chapter V, Chapter VII, Chapter XII and Art. 78 applied from 2 August 2025,
  except Art. 101; this date has passed (Art. 113(b)).
- Art. 102 to 110 apply from 27 July 2026; this date has passed (Art. 113(d)).
- Art. 5(1), first subparagraph, points (ba) and (bb), and Art. 5(1a) and (1b), apply only from 2
  December 2026; this date is still future as of this file's law-as-of date (Art. 113(a)).
- Chapter III, Sections 1, 2 and 3, except Art. 6(5), apply from 2 December 2027 for an AI system
  classified as high-risk under Art. 6(2) and Annex III, and from 2 August 2028 for an AI system
  classified as high-risk under Art. 6(1) and Annex I; both dates are still future as of this file's
  law-as-of date, and that regime sits outside this file's source (Art. 113(c), points (i), (ii)).

## Open points to raise

- Whether a feature relying on the Art. 50(2) assistive-function or no-substantial-alteration
  carve-out, or the Art. 50(4) editorial-responsibility carve-out, actually behaves the way the
  carve-out requires; this file cannot settle a question about a specific feature's technical
  behaviour or editorial process.
- Whether a product offering biometric categorisation or emotion recognition falls into the Art.
  5(1)(f) or (g) prohibitions before any Art. 50(3) notice clause is drafted for it; this is a
  factual question about what the feature infers and where it is used.
- Whether a research-only product relying on the Art. 2(6) sole-purpose scientific-research-and-
  development exclusion keeps that as its sole purpose once it is offered more broadly; this file
  cannot settle a question about a specific product's actual use.
