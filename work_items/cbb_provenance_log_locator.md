# Crypto-systems Building Blocks: Provenance Log Identifiers

This is the sixth proposed work item in a series of work items under the
category of "crypto-systems building blocks".

This work item is to propose an IETF standard for a method to calculate a
cryptographically secure uniform resource locator (URL) for a provenance log
using the provenance log identifier and a compact BLS digital signature. This
is a critical part of building decentralized crypto-systems that use provenance
logs to track key and authentic data history. This locator proposal allows for
the use of untrusted storage which maximizes scalability and DDoS resistance
while eliminating the need for any network other than the Internet itself.

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Hopefully somebody else :)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish an algorithm for calculating the URL for a given provenance log
  using the log's URI and a BLS digital signature.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the cryptographic guarantees and applications of the
  URLs in crypto-systems.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that is working provenance logs and wishes to
  use URLs to locate and download them in related software.

### Relevant Related Standards
- [IETF RFC 8141 Uniform Resource Locators][0]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://datatracker.ietf.org/doc/html/rfc1738
