# Crypto-systems Building Blocks: Provenance Logs, Identifiers, Locators and Anchors

This work item is to propose IETF standards for:

- an abstract data model and file format for a cryptographic provenance log.
- method to calculate a self-cerityfing unifrom resource name (URN) from a
  cryptographic provenance log.
- method to calculate a cryptographically secure uniform resource locator (URL)
  for a provenance log using the provenance log identifier and a compact BLS
  digital signature.
- protocol for "anchoring" provenance logs in external trust services (e.g.
  public blockchains).

Cryptographic provenance logs are hash-linked data structures that store a
series of event meta data and related data with additional cryptographic data
that enforces integrity and authenticity. Decentralized crypto-systems must
track the history of data over time such as key commitments and rotations but
any data may be tracked. To create a cryptographically secure system for
trusting the contents, history, identity and location of provenance logs we
first need a way to calculate a self-certifying identifier from a provenance
log. The identifiers must meet the criteria for being a URN. Then from the
identifier, we need a way to add a protocol scheme and domain information (e.g.
https://example.com/) so that the when combined with the identifier the
provenance log file can be retrieved. However, the URL must also contain a
compact BLS digital signature over the URL so that resolvers are able to verify
that the controller of the provenance log created the URL as well. The last
piece needed is a simple protocol for asking an anchoring service to include
data from the provenance log to prove that it existed and that the set of
events in the log forms the complete log at the time of anchoring. The protocol
also retreives the anchoring "receipt" in the form of a cryptographic proof
identifying the location the anchoring data resides and the data necessary to
prove that the provenance log is included.

Provenance logs are intended to be a generalized form of a linked list data
structure that uses cryptographic primitives to ensure integrity with a strong
cryptographic link to a crontroller of the log. There are many examples of
systems that use similar concepts: blockchains (e.g. Bitcoin), messaging
platforms (e.g. Secure Scuttlebutt), and revision control systems (e.g. Git).
Having an abstract data model for a general and extensible provenance log is
a big step towards interoperability across crypto-systems that use them.

This is similar to the standard for email messages. There is an abstract model
for email that includes headers, body, and also multi-part messages and
attachments. There are IETF standards that define the encoding of those
messages and the protocols for transmitting them. This work item seeks to
establish similar standards for provenance logs so that we normalize on what
a secure record of history looks like. Because it is impossible to enumerate
all possible use cases, the data model for provenance logs is extensible with
the standard only covering core concepts (e.g. hash linking, policy-as-code,
associated data tracking, key rotations, and anchoring for trust across
trust domains).

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Steve Todd (@stevetodd, Individual Contributor)
- Seth Back (@Seth Back, sethjback@gmail.com, Individual Contributor)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish an abstract data model for basic provenance log events.
- Establish an encoding and file format for binary and text version of
  provenance logs.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the cryptographic guarantees and applications of
  provenance logs and their identifiers, locators, and anchoring in
  crypto-systems.
- A URN formal namespace application.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer building software that must track the history
  and/or provenance of data and secure it using cryptographic operations.

### Relevant Related Standards
- [ToIP ACDC Proposal][0]
- [Bitcoin Blockchain][1]
- [IETF RFC 8141 Uniform Resource Names][2]
- [IETF RFC 8141 Uniform Resource Locators][3]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://wiki.trustoverip.org/display/HOME/ACDC+%28Authentic+Chained+Data+Container%29+Task+Force
[1]: https://developer.bitcoin.org/reference/block_chain.html
[2]: https://datatracker.ietf.org/doc/html/rfc8141
[3]: https://datatracker.ietf.org/doc/html/rfc1738
