# ~~Crypto-systems Building Blocks: Distributed ZKP Authentication~~ [ARCHIVED]

**This work item has been archived. If you are interested in reviving it, please contact the Crypto WG chairs.**

~~This is the tenth proposed work item in a series of work items under the
category of "crypto-systems building blocks".~~

~~This work item is to propose an IETF standard method and protocol for a novel
MFA ZKP authentication system based on curve and bilinear maps. The approach
produces a capability token that is just 48 bytes and produces proofs that are
just 96 bytes. The authentication method does not require disclosure of the
token value which eliminates the risk associated with traditiona "API token"
approaches to zero-round-trip, or non-interactive, authentication. This is
a critical part of building decentralized crypt-systems because the capability
token is a form of anonymous delegated credential granting access service
endpoints. The generation of tokens can also be done using one-pass distributed
key generation and threshold signing to eliminate a single point of attack in
the decentralized authorization delegation system.~~

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Tomislav Markovski (@Tomislav, Trinsic, Inc)
- Steve Todd (@stevetodd, Individual Contributor)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish a standard approach based on curve and bilinear maps for creating
  authentication capability tokens.
- Establish a standard approach for distributed key generation and threshold
  signing of tokens.
- Establish a standard protocol for zero-round-trip authentication.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the cryptographic guarantees and applications of the
  capability tokens.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that is working with decentralized systems and
  needs a distributed authentication delegation system that uses capability
  tokens and zkp presentation.

### Relevant Related Standards
- [Oberon Crypto][0]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://github.com/mikelodder7/oberon/blob/main/CRYPTO.md
