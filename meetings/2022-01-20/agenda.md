## Meeting - Thursday 20th January 2022 - (3pm ET)

### Chair
Brent Zundel


### Agenda
- Agenda Review, and Introductions 
- [Issue Review](https://github.com/decentralized-identity/crypto-wg/issues)
- [Proposal Review](https://github.com/decentralized-identity/crypto-wg/pulls)
- BBS+ Signatures - Tools for test vector generation and a code-level specification feedback loop.
- [Work Item Reports](https://github.com/decentralized-identity/crypto-wg/tree/main/work_items)
- IETF-bound specification tooling - What do we need from DIF in order to make this process efficient and pleasant as possible within DIF-provided repositories.

### Attendees
* Brent Zundel (Avast/Evernym)
* Andreas Freitag (Jolocom)
* Mike Lodder (cryptid.tech)
* Dave Huseby (cryptid.tech)
* Tobias Looker (Mattr)
* Steve Todd (Independent)
* Seth Back (Trinsic)
* Iván Temchenko (Jolocom)
* Michael Jones (MSFT)
* David Waite (Ping)
* Cam Parra (Kiva)
* Brian Richter (Aviary)

### Notes
#### Issue Review
no open issues

#### PR Review
no updates on the two open PRs
- #27 - Policy as Code updates
- #8 Provenance logs work item

#### Tooling for spec development
- BBS+ Signatures work item wants to have scratch code to assist in development: Group is fine with it as ong as it is clear that it is not a reference implementation
- IETF-Tooling - this isn't totally necessary in the JWP instance. The spec is intended to stay where it is as the work on the spec transitions from DIF to IETF.

#### Work Item status
- [bbs signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bbs_signatures.md)
    -  work is progressing. there are a couple of issues that could use more feedback
        -  https://github.com/decentralized-identity/bbs-signature/issues/19

- [bof secure software supply chain](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bof_secure_software_supply_chain.md) 
    - a lot going on, connected with gitlab and other core people in the space
    - can't reveal much at this point, but a "meeting of the minds" is possible, possibly around IIW.
    
- [CBB Data Encoding](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_data_encoding.md) & [CBB Crypto Service Protocol](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_service_protocol.md)
    - new version of spec is out and new implementation.
    - ready for working group approved status
    
- [cbb_delegatable_anonymous_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_delegatable_anonymous_credentials.md) 
    - nothing new

- [cbb-distributed_zkp_authentication](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_distributed_zkp_authentication.md) 
    - deployed in the wild, implementations being developed
    - ready for working group approved status

- [cbb_policy_as_code](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_policy_as_code.md) 
    - PRs are in place.
    - this is shifting somewhat - need to know from Wayne Change what he thinks
        - may turn into verifiable computations with untrusted setups

- [cbb-service_protocol](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_service_protocol.md) 
    - really cool
    - shifted from simple text to [DISCO](https://www.discocrypto.com/disco.html) (signal, but using strobe protocol instead of SHA2)

- [JSON Web Proof](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/json_web_proof.md)
    - single-use credentials being documented and implemented
    - optimization of number of cryptographic operations
    - Merkle-tree based approach in development as well

- [revocation_methods_for_verifiable_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/revocation_methods_for_verifiable_credentials_.md)
    - Added an non-cryptographic accumulator schema "ValidityVerifiableCredential"
        - Can be an interims solution which can be implemented "fast". It sets up on available and tested functions.Needs to be explored in more detail in the next weeks.
    - No update on the other 3 schemas
    
- [Spartan ZKP signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/spartan_zkSNARK_signatures.md)
    - no update
