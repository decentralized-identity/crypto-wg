# Crypto-systems Building Blocks: Data Encoding

This is the first proposed work item in a series of work items under the
category of "crypto-systems building blocks".

This work item is to propose an IETF standard for encoding cryptographic data
in a universal and self-describing way. This goes beyond the existing JWK/JWT
standards and includes all classes of cryptographic data: keys, nonce, digital
signatures, encrypted data, AEAD constructs, PRNG state, policy-as-code (smart
contracts), HMAC, and digests. The self-describing aspect is key in enabling
the separation of concerns into cryptographic service providers (e.g. signing
and encrypting tools) and cryptographic service consumers (e.g. email, Git).

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Hopefully somebody else :)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish an abstract data model for self-describing "tag" and payload.
- Establish an encoding and framing method for self-describing data.
- Establish [multicodec][0] as the canonical list of type tag values and
  [governance around the maintenance of the list][1].
- Establish a standard for binary encoding and text encoding of the self-
  describing crypto data.

In the end we will have a standard way of encoding--in both text and binary--
cryptographic data in a self-describing and portable way.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the concept of the separation of concerns into
  cryptographic service providers and consumers and the motivation for this
  approach.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that is working on software that has to rely
  upon cryptographic data and need a way to store and transmit the data in a
  way that enables "algorithmic agility". This deliverable is an important
  step in making software that can work with any cryptographic service provider
  and externalize all cryptographic operations.

### Relevant Related Standards
- [de facto Multicodec standard][2]
- [de facto Unsigned Varint standard][3]
- [IETF RFC 4648 Base64 Data Encoding][4]
- [IETF Draft Base58 Encoding Scheme][5]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://github.com/multiformats/multicodec#multicodec-table
[1]: https://github.com/multiformats/multicodec#adding-new-multicodecs-to-the-table
[2]: https://github.com/multiformats/multicodec
[3]: https://github.com/multiformats/unsigned-varint
[4]: https://datatracker.ietf.org/doc/html/rfc4648
[5]: https://datatracker.ietf.org/doc/draft-msporny-base58/03/

