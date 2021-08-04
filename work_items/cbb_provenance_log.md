# Crypto-systems Building Blocks: Provenance Log

This is the third proposed work item in a series of work items under the
category of "crypto-systems building blocks".

This work item is to propose an IETF standard for a cryptographic provenance
log abstract data model and related file format. Cryptographic provenance logs
are hash-linked data structures that store a series of event meta data and
related data with additional cryptographic data that enforces integrity and
authenticity. This is a critical piece of fully decentralized crypto-systems
that must track the evolution of data over time such as key commitments and
rotations but any data may be tracked.

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Hopefully somebody else :)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish an abstract data model for basic provenance log events.
- Establish an encoding and file format for binary and text version of
  provenance logs.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the concept of a cryptographic provenance log.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer building software that must track the history
  and/or provenance of data and secure it using cryptographic operations.

### Relevant Related Standards
- [ToIP ACDC Proposal][0]
- [Bitcoin Blockchain][1]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://wiki.trustoverip.org/display/HOME/ACDC+%28Authentic+Chained+Data+Container%29+Task+Force
[1]: https://developer.bitcoin.org/reference/block_chain.html
