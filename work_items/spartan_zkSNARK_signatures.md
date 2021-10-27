# Spartan zkSNARK Signatures

This work item focuses on adding selective disclosure and unlinkable derived
credential generation for multi-message credentials issued with standard digital
signature schemes such as ECDSA using NIST's P-256.

To achieve this, we rely on zkSNARKs, a cryptographic primitive that allows a
prover to prove the knowledge of a secret witness of an arbitrary circuit
satisfiability instance to a verifier *without* revealing anything about the
witness besides the fact that the circuit is satisfiable. In computational
terms, a zkSNARK enables the prover to prove the correct execution of a program
(e.g., a program that verifies ECDSA signatures) to a verifier (since program
executions can be encoded with R1CS, a generalization of circuit
satisfiability). 

To produce unlinkable derived credentials (for credentials issued with standard
signature schemes), we need a zkSNARK that supports arbitrary,
sufficiently-large prime fields (e.g., the scalar field of P-256 curve). For
this purpose, we use [Spartan](https://eprint.iacr.org/2019/550.pdf), a
state-of-the-art zkSNARK, with the fastest prover. Additionally, Spartan does
not require a trusted setup (a major issue in prior zkSNARKs).


## Work Item Owners
- Jeremie Miller (jmiller@pingidentity.com)
- Srinath Setty (srinath@microsoft.com)
- Kristina Yasuda (Kristina.Yasuda@microsoft.com)

## Outcome

Our goal is to produce a document that can be proposed as an input to the IETF
CFRG for the formal standardization of adding selective disclosure and
unlinkability to standard signature schemes.

## Deliverables
- A document with a formal description of the cryptographic processes (and
  representations) for producing and verifying unlinkable derived credentials
  using the Spartan zkSNARK.  
- A set of test vectors to support the development of interoperable
  implementations.
- Estimated six month timeline

## Meetings
- A bi-weekly work item call to make progress on the above deliverables.
