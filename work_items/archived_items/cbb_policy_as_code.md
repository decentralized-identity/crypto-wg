# ~~Crypto-systems Building Blocks: Policy-as-Code Language~~ [ARCHIVED]

**This work item has been archived. If you are interested in reviving it, please contact the Crypto WG chairs.**

~~This is the eigth proposed work item in a series of work items under the
category of "crypto-systems building blocks".~~

~~This work item is to propose an IETF standard for an application independent,
non-Turing-complete language and virtual machine definition for encoding and
executing cryptographic policies as code (i.e. smart contracts). Fully
decentralized crypto-systems require a method for defining policies that allow
for decentralized and independent verification and enforcement. This is similar
to the way Bitcoin users define the policy for validating Bitcoin transactions
such that Bitcoin miners can do the validation independently and without any
coordination with other miners. This is a generalization of that concept to
application neutral, authentic data applications that require maximum
decentralization and scalability.~~

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Wayne Chang (@wyc, Spruce Systems, Inc)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish a standard language definition for a non-Turing-complete
  programming language designed for defining policy-as-code.
- Establish a standard virtual machine definition that formalizes external
  data sources that may be referenced by the language at run-time.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the design decisions (e.g. non-Turing-complete) as
  well as the applications of the language in provenance logs and other crypto-
  systems (e.g. emailed Git patches).
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that works with crypto-systems and requires a
  method for defining late-binding policies as code for decentralized and
  independent verification of cryptographically secure data.

### Relevant Related Standards
- [Crypto Construct Language][0]
- [Bitcoin Script][1]

## Meetings
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://github.com/dhuseby/cclang
[1]: https://en.bitcoin.it/wiki/Script
