# Crypto-systems Building Blocks: Delegatable Anonymous Credentials

This is the ninth proposed work item in a series of work items under the
category of "crypto-systems building blocks".

This work item is to propose an IETF standard to formalize the method and
application of delegatable anonymous credentials for use in decentralized
crypto-systems. It also establishes an abstract data model that explicitly
avoids negative privacy implications of using stable identifiers for inter-
object and intra-object references. This is critical for building fully
decentralized crypto-systems that maximize privacy and have authorization
functions that rely on credential delegation and revocation.

This is similar in nature to the IETF JOSE and COSE standards work that
formalized the data model and method for encoding cryptographically signed JSON
and CBOR encoded data objects respectively.

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Hopefully somebody else :)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish a standardized approach for anonymously creating, delegating, and
  revoking authentic data payloads intended for the use of authorization.
- Establish an abstract data model for such credentials.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the cryptographic guarantees and applications of
  the anonymous credentials in decentralized crypto-systems.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that is working with authentic data and
  applying it to fully decentralized authentication systems.

### Relevant Related Standards
- [Delegatable Anonymous Credentials from Mercurial Signatures][0]
- [Authorization Capabilities for Linked Data][1]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://eprint.iacr.org/2018/923.pdf
[1]: https://w3c-ccg.github.io/zcap-ld/
