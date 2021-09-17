# Crypto-systems Building Blocks: Policy-as-Code Language

This is part of a series of work items under the category of "crypto-systems
building blocks".

This work item is to propose an IETF standard for a domain specific language
focused on capturing policies as code that is translated into R1CS gadgets
which are in turn compiled to verifiable computation such as a zkSNARK or
Bulletproof. There only exists two known examples (that I could find) of a
high level language designed for this purpose: Snarky and a C compiler that was
published along with the Pinocchio protocol work.

Snarky is limited to targeting zkSNARKs and thus rely on a trusted setup. This
new high level policy-as-code language is targeted at defining R1CS gadgets
that serve as inputs to zkSNARKS and Bulletproof encoders for both trusted
and untrusted verifiable computations.

## Work Item Owners
- Dave Huseby (@dhuseby, dave@cryptid.tech, CryptID Technologies, Inc)
- Wayne Chang (@wyc, Spruce Systems, Inc)

## External Partners
- IETF, new WG for crypto-systems building blocks?

## Outcome
- Establish a standard language definition for a higher level language that
  enforces the limitations required for converstion to R1CS gadgets.

## Deliverables
- An IETF formatted draft standard, ready for proposal.
- A white paper describing the design decisions as well as the applications of
  the language in provenance logs and other crypto-systems (e.g. emailed Git
  patches).
- One or more reference implementations.
- The expected timeline is 1-3 months to completion.
- The audience is any developer that works with crypto-systems and requires a
  method for defining verifiable computations for both trusted and untrusted
  setups.

### Relevant Related Work
- [Crypto Construct Language][0]
- [Snarky Language][1]
- [Pinocchio Protocol Paper/Compiler][2]

## Meetings
- [Work item repo][3]
- Current agenda and work conversation happening in the Discussions in the
  Github repo.
- Implementor updates are presented at the regular Applied Crypto WG meetings.

[0]: https://github.com/dhuseby/cclang
[1]: https://github.com/o1-labs/snarky
[2]: https://eprint.iacr.org/2013/279.pdf
[3]: https://github.com/decentralized-identity/policy-as-code
