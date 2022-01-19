## Meeting - Thursday 9th December 2021 - (3pm ET)

### Chair
Brent Zundel


### Agenda
- Agenda Review, and Introductions 
- No Meetings until 2022-01-19
- [Issue Review](https://github.com/decentralized-identity/crypto-wg/issues)
- [Proposal Review](https://github.com/decentralized-identity/crypto-wg/pulls)
- [Work Item Reports](https://github.com/decentralized-identity/crypto-wg/tree/main/work_items)

### Attendees

* Andreas Freitag
* Brent Zundel
* Noah Bouma
* Tomislav Markov
* Jeremie Miller
* Srinath Setty
* Mike Lodder
* Cam Parra
* Matt Raffel
* Stephen Curren
* Andrew Whitehead
* Steve Todd
* Dave Huseby

### Notes

#### Issue Review

#### PR Review
- #27 - Policy as Code updates - Dave and Wayne need to get together, then clean up the PR so we can get it merged.
- #15 Proposal for ZKP authentication - work item approved and merged
- #8 Provenance logs work item - Dave will have conversation with Robert Mitwicki about merging efforts.

#### Work Item status
- [bbs signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bbs_signatures.md)
    -  ready to create draft proposal for details.

- [bof secure software supply chain](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bof_secure_software_supply_chain.md) 
    - Connections made with key folks at google, gitlab, LF to see if a community event might be organized. Perhaps an intra-IIW event.
    
- [CBB Data Encoding](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_data_encoding.md) & [CBB Crypto Service Protocol](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_service_protocol.md)
    -  hasn't moved since september. Lots of research. Dave has implemented his original proposal so it can be integrated into git. 
    
- [cbb_delegatable_anonymous_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_delegatable_anonymous_credentials.md) 
    - not really started yet. Implementation is moving forward, but other items have taken precedence for now.

- [cbb-distributed_zkp_authentication](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_distributed_zkp_authentication.md) 
    - work item just created.

- [cbb_policy_as_code](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_policy_as_code.md) 
    - waiting on feedback from Wayne Chang

- [cbb-service_protocol](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_service_protocol.md) 
    - draft spec will be updated soon. C implementation done soon, with possibility of it merging with Git.

- [JSON Web Proof](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/json_web_proof.md)
    - steadily moving forward with issues and discussions. The draft is now broken into more of a family of drafts, a'la JOSE. Iterating along.

- [revocation_methods_for_verifiable_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/revocation_methods_for_verifiable_credentials_.md)
    - We have now 3 accumulator schemas for further assessment
        - From 2 we have first performance figures
    - Discussed an additional solution for an interims revocation solution which is privacy preserving in the holder-verifier relationship.
    - Graphical descriptions expanded.
    - Need validator/wingman for "zk-SAM: Signed Accumulator Members"
    
- [Spartan ZKP signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/spartan_zkSNARK_signatures.md)
    - work just started. working closely with JWP