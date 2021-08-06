# Crypto-systems Building Blocks: Service Protocol

This is the second proposed work item in a series of work items under the
category of "crypto-systems building blocks".

This work item is to propose an IETF standard for a protocol that cryptographic
service consumers utilize to interact with cryptographic service providers.
This protocol is needed to enable the separation of concerns between
cryptographic service providers and consumers and is key to building crypto-
systems that have algorithm agility and are agnostic to the cryptography used.

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Steve Todd (@stevetodd, Individual Contributor)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish a standard protocol for the set up and execution of cryptographic
  services (e.g. digital signature creation/verification, etc) by an external
  cryptographic service provider.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the concept of the separation of concerns into
  cryptographic service providers and consumers and the motivation for this
  approach.
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that is working on software that has to rely
  upon cryptographic operations and needs a standard way for talking to
  external cryptographic service providers.

### Relevant Related Standards
- [GnuPG Assuan Protocol][0]
- [IETF Draft TEEP Protocol][1]
- [Tor Control Protocol][2]
- [IETF RFC5321 Simple Mail Transport Protocol][3]
- [Git Cryptography Protocol Proposal][4]
- [SSH Agent Protocol][5]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://www.gnupg.org/documentation/manuals/assuan.pdf
[1]: https://datatracker.ietf.org/doc/html/draft-ietf-teep-protocol-06
[2]: https://gitweb.torproject.org/torspec.git/tree/control-spec.txt
[3]: https://datatracker.ietf.org/doc/html/rfc5321
[4]: https://github.com/TrustFrame/git-cryptography-protocol/blob/main/Git%20Cryptography%20Protocol.md
[5]: https://datatracker.ietf.org/doc/html/draft-miller-ssh-agent-04
