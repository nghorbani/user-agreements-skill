# Connected product data

Law as of: 2026-10-20

## Purpose

This clause states what a user of a connected product or a related service may do with the data that
product or service generates, how the trader (as data holder) must give the user access to it or share
it with a third party at the user's request, and what the trader must say before the contract is
concluded about the data the product or service produces. It also states when a legal basis under the
GDPR, separate from the Data Act's own access and sharing rights, is needed for data in this flow that
is personal data. It does not cover the Regulation's statutory data-sharing chapter, the public-sector
data-access regime, the interoperability and smart-contract chapter, the cloud and data-processing-service
switching duties, or the B2B unfair-terms test for a data contract one enterprise imposes on another (see
`references/eu/data-act.md` for all of these, stated there but not restated here). It does not cover the
general GDPR transparency and privacy-notice content (see `references/clauses/privacy-and-data.md` and
`references/eu/gdpr-privacy-notice.md`), processor duties or international transfers (see
`references/eu/gdpr-processors-transfers.md`), or the data subject's access, erasure and portability
rights as such (see `references/eu/gdpr-rights-liability.md`).

## Model wording

[Product name] is a connected product that generates data about its use and its environment (product
data). [Where a related service is sold with it: using [service name] with [product name] also generates
data through that service (related-service data).] Before [licensee name] buys, rents or leases [product
name] [or subscribes to [service name]], [trader name] tells [licensee name] what data the product or
service can generate, whether it does so continuously and in real time, whether and how long the data is
stored, and how [licensee name] can access, retrieve or erase it.

By default, [licensee name] can access the data [product name] [and [service name]] generate, with the
information needed to interpret and use it, easily, securely, free of charge, in a structured,
commonly used, machine-readable format[, and, where this is technically possible, continuously and in
real time]. Where [licensee name] cannot access the data directly through [product name] [or [service
name]], [trader name] makes it available on request, without undue delay, free of charge, at the same
quality [trader name] itself has access to.

On [licensee name]'s request, [trader name] makes the same data available to a third party [licensee
name] names, to the same standard and without undue delay, at no cost to [licensee name]. [Trader name]
does not keep more information about an access or sharing request, including log data, than is needed to
carry it out and to keep the systems that handle it secure.

[Trader name] may restrict or refuse a request where sharing the data would undermine a security
requirement that applies to [product name] [or [service name]] and cause a serious risk to health,
safety or security, or where the data is protected as a trade secret and no agreement is reached on
protecting it; [trader name] tells [licensee name] in writing why, without undue delay. [Licensee name]
may bring this before [the competent authority / the dispute settlement body named in this contract] or
before a court.

[Where the data [trader name] holds about [licensee name]'s use of [product name] [or [service name]] is
personal data: [trader name] processes it only on the basis set out in `references/clauses/privacy-and-data.md`,
and tells [licensee name] which basis applies to which purpose. Where that basis is consent, giving it is
a separate, standalone step from accepting this contract.]

A named third party receiving data under this clause may use it only for what [licensee name] agreed to,
must delete it once that purpose is served unless [licensee name] agreed otherwise for data that is not
personal data, and may not use it to build a product that competes with [product name] [or [service
name]], or pass it on to a company designated as a gatekeeper under Regulation (EU) 2022/1925.

## Modules

### EU consumers

Give every Art. 3(2) and Art. 3(3) disclosure before the contract is concluded, not folded into the
general terms after the fact: for the connected product itself, the type, format and estimated volume
of data it can generate, whether it generates continuously and in real time, whether and how long it is
stored on the device or remotely, and how the user can access, retrieve or erase it (Art. 3(2)(a) to
(d)). Where a related service is sold or offered with the product, give the user a separate set of nine
disclosures for that service: the nature, estimated volume and collection frequency of the product data
the service expects to obtain and how the user can access or retrieve it, with the provider's storage
and retention plans; the nature and estimated volume of related-service data the service will generate,
with the same access, storage and retention detail; whether the provider will use readily available data
itself and for what purpose, and whether it will let a third party use it on terms agreed with the user;
the provider's identity and contact details; how the user requests sharing with a third party and ends
it; the user's right to complain to the competent authority; whether the provider holds trade secrets in
the data and, if not, who does; and the contract's duration and termination (Art. 3(3)(a) to (i)). Keep
all nine as separate items rather than one combined sentence.

State the default-access standard in the model wording's second paragraph only for data the product or
service is actually built to expose directly to the user; where it is not, keep the fallback paragraph
instead, since the two rest on different articles with different conditions (Art. 3(1); Art. 4(1)).

Where the user asks for data to be shared with a named third party rather than retrieved directly, use
the third paragraph; this right does not reach data generated in testing a product, substance or process
not yet on the market, unless the user's contract with the third party permits that use (Art. 5(1),
(2)).

Fill in the restriction paragraph only where it reflects an actual, contractually reserved right: a
security-and-safety restriction needs notice to the competent authority designated under Art. 37 where
the trader refuses on that ground (Art. 4(2), (3)); a trade-secret restriction needs a prior attempt to
agree protective measures, a written, substantiated refusal or suspension without undue delay, and the
same competent-authority notice (Art. 4(6) to (9); Art. 5(9) to (12)). State plainly that the user may
bring a refusal or restriction before the competent authority, a dispute settlement body, or a court;
this is not optional wording to drop where the trader prefers to keep the point silent (Art. 4(3), (9);
Art. 5(12)).

Where a named third party receives data under this clause, bind it by contract to the limits the fourth
paragraph of the model wording states, and add the further limits this clause does not restate in full:
it must not make the user's access or sharing choices unduly difficult through non-neutral framing or a
manipulative interface, must not use the data for profiling beyond the requested service, must not pass
it to a further third party without the user's fresh agreement and the same trade-secret protections, and
must not use it to develop a competing product or derive insights about the trader's economic position
(Art. 6(2)(a) to (g)). Where the user is a consumer, the third party cannot stop the user making the data
it received available to others again (Art. 6(2)(h)).

State the processing basis for personal data in this flow by pointing to the applicable module of
`references/clauses/privacy-and-data.md` rather than restating the six Art. 6(1) grounds here; this
clause only flags that a separate basis is needed and that it must be disclosed, not which one applies
to a given purpose (Art. 1(5)).

### EU business customers

The disclosures, default-access standard, and sharing mechanics above apply the same way to a business
customer: the Data Act does not limit Chapter II to consumer users, and the "user" definition reaches any
natural or legal person who owns, holds a contractual right to use, or receives the related service for
the connected product (Art. 2(12)). Drop the user's-interest safeguards that exist specifically for a
consumer, since Art. 6(2)(h) (the ban on a third party blocking onward sharing) is itself limited to a
consumer user; state plainly in the document whether the counterparty is a consumer or a business user,
since this one provision turns on that fact (Art. 6(2)(h)).

Where the connected product or related service is generated by a microenterprise or small enterprise for
its own product or service, that enterprise is outside the Chapter II duties above, unless it has a
disqualifying partner or linked enterprise, or is itself subcontracted to build the product or service
for someone else; the same carve-out reaches an enterprise that has held medium-sized status for less
than a year, and a product for one year after a medium-sized enterprise places it on the market (Art.
7(1)). Where the trader relies on this carve-out, state it, since it changes which disclosures and access
duties this clause requires the trader to meet.

### Germany

No German transposition or supplementing law for the Data Act's Chapter II is among this clause's
sources; the Regulation applies directly, so no separate German module adds rules beyond the EU
consumers module above. Where personal data is involved, the German rules this clause's GDPR source
states (see `references/clauses/privacy-and-data.md`, Germany module) apply alongside the Data Act module
exactly as the EU consumers module here describes, since Art. 1(5) resolves any conflict in favour of
data-protection law and does not displace the Data Act's own access and sharing duties.

### US

No source behind this clause covers a US connected-product or related-service data-access right. Do not
reuse this clause's access, sharing or disclosure duties for a US-facing document on the strength of
this clause; a US product's own data-handling terms rest on whatever privacy or consumer-protection law
actually applies there, not on this clause. Treat a US connected-product data duty as an open point for a
reference file that covers it.

## Must not

- No clause may make exercising the access or sharing right unduly difficult, whether by a non-neutral
  presentation of the choice or by interface design that subverts or impairs the user's decision-making
  (Art. 4(4)).
- No clause may let the user, or a third party acting with the user, use data obtained under this clause
  to develop a competing connected product, share it with that intent, or derive insights about the
  trader's economic situation, assets or production methods (Art. 4(10), (11); Art. 5(5)).
- No clause may let the trader use readily available non-personal data except on a contractual basis
  with the user, or use it to derive insights about the user's or a third party's economic position in a
  way that could undermine their commercial standing, unless that third party permitted the use and can
  withdraw the permission at any time (Art. 4(13); Art. 5(6)).
- No clause may let the trader share non-personal product data with a third party for any purpose beyond
  fulfilling its contract with the user, or omit the onward-sharing restriction that contract with the
  third party must carry (Art. 4(14)).
- No clause may exclude, derogate from or vary, to the user's detriment, the access, sharing or
  trade-secret-handling rights this clause states, even with the user's express agreement to that
  variation (Art. 7(2)).
- No clause may grant third-party access rights under this clause to a company designated a gatekeeper
  under Art. 3 of Regulation (EU) 2022/1925, and no clause may let such a company solicit or
  commercially incentivise a user to route data to one of its own services (Art. 5(3)(a) to (c)).
- No clause may commit to sharing a data subject's personal data with the user or a named third party
  under this clause without a valid GDPR legal basis for that sharing, and no clause may let a dispute
  over sharing arrangements between the trader and a third party be used to block a data subject's own
  GDPR rights (Art. 4(12); Art. 5(7), (8), (13)).
- No clause describing a processing purpose in this flow as resting on consent may rely on a bundled
  acceptance of this contract as that consent; consent for personal data in a connected-product or
  related-service flow needs the same standalone, specific, affirmative act any other consent needs (see
  `references/clauses/privacy-and-data.md`).

## Drafting notes

See `references/conflicts.md` for whether an entry decides between the Data Act access right and a
trader's own competing-interest clause on data reuse; none is listed for this topic as of this file. Where
the contract also needs the B2B unfair-terms test for data clauses one enterprise imposes on another, or
the cloud-switching duties for a data-processing service, build those from `references/eu/data-act.md`
directly: this clause's model wording and modules cover only the user-facing access, sharing and
pre-contract disclosure duties, not those other two regimes.

Where the connected product or related service generates personal data about an identified or
identifiable individual, this clause's data-access and sharing rights sit alongside, not instead of, the
GDPR basis that data needs; state both in the document, since satisfying one does not satisfy the other
(Art. 1(5)).

## Legal basis

`references/eu/data-act.md` (Regulation (EU) 2023/2854, Art. 1, 2, 3, 4, 5, 6, 7); `references/eu/gdpr-legal-bases.md`
(Regulation (EU) 2016/679, Art. 6, 7, naming the standalone consent requirement this clause's personal-data
paragraph points to).
