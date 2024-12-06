# Self-Attestation via Zero-Knowledge Proofs for Anonymous Authentication

This work item aims to develop mechanisms for self-attestation using Zero-Knowledge Proofs (ZKPs) and programmable cryptography with W3C Verifiable Credentials (VCs) and other decentralized identity standards to support anonymous authentication use cases, with a special focus on Proof of Personhood. This work is informed by efforts such as [Anon Aadhar](https://github.com/anon-aadhaar/anon-aadhaar). While we wish to see more governments adopting SSI tooling, there exist countries with digital identity programs that are issuing digitally signed documents, these signatures could be verified anonymously using ZK, providing a way to achieve anonymous credentials and selective disclosure.

The goals of the working group are to define a standard way to handle this type of self-attestation along with the corresponding use cases and trust model.

## Work Item Owners

- **Yanis Meziane** (@Meyanis95, yanis@pse.dev)
- **Kim Duffy** (@kimdhamilton, kim@identity.foundation)

## External Partners (OPTIONAL)

- **IETF**
- **W3C**
- **PSE**

## Outcome

The goals of this work item include:

- Define a mechanism for anonymous authentication based on SSI standards including W3C VCs and Decentralized Identifiers (DIDs).
- Define a verifiable credential container model for ZKP proof of personhood attestations.
- Define trust model and use cases
- Enable individuals to prove personhood without revealing personal information.
- Enhance the SSI ecosystem with practical applications of ZKPs and programmable cryptography.
- Foster interoperability and wallet-agnostic solutions for broader adoption.

## Deliverables

- **Technical Specification Document**: Outlining the protocols and standards for self-attestation using ZKPs along with W3C Verifiable Credentials.
- **Use Cases and Trust Model Document**: Non-normative document describing appropriate use cases, contexts, and trust models.
- **Prototype Implementation**: A reference implementation demonstrating the proof of concept.
- **Integration Guidelines**: Documentation on how to integrate the solution with existing SSI frameworks and wallets.
- **Timeline**:
  - Q4: Research and initial draft of specifications.
  - Q1: Development of prototype implementation, spec revisions
  - Q2: Testing, feedback, and revisions. Finalization of documents and presentation to the community.
- **Audience**: SSI architects and developers, cryptography and security researchers., standards bodies, and organizations interested in anonymous authentication.
- **Related Resources**:
  - W3C Verifiable Credentials
  - Decentralized Identifiers (DIDs)
  - DIF Presentation Exchange
  - Existing ZKP frameworks

## Meetings

- **Schedule**: Primarily asynchronous, to be revisited as necessary
- **Collaboration**: [DIF Discord](https://discord.gg/3qm3xQvv), zk-self-attestations channel
- **Notes and Recordings**: To be published on the DIF Applied Crypto WG GitHub repository and shared via the usual DIF channels
