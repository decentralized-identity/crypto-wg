# Crypto-systems Building Blocks: Provenance Log Identifiers

This is the fifth proposed work item in a series of work items under the
category of "crypto-systems building blocks".

This work item is to propose an IETF standard for a method to calculate a self-
certifying uniform resource name (URN) from a standard cryptographic provenance
log. The purpose of the identifier is to uniquely identify a cryptographic
provenance log in a cryptographically secure way while also providing
and end-to-end integrity verification method. This is a critical part of
building decentralized crypto-systems because the identifiers are used to
"anchor" provenance logs in external "trust anchors" such as public blockchains
to provide proof of existence as well as proof of completeness.

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Hopefully somebody else :)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish an algorithm for calculating the URN for a given provenance log
  using self-describing encoded digests.
- Establish the optional URN components used for addressing sub-components of
  a provenance log.
- Register a formal URN namespace (e.g. urn:pli).

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A URN formal namespace application.
- A white paper describing the cryptographic guarantees and applications of the
  URNs in crypto-systems.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that is working provenance logs and wishes to
  use URNs to reference them in related software.

### Relevant Related Standards
- [IETF RFC 8141 Uniform Resource Names][0]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://datatracker.ietf.org/doc/html/rfc8141
