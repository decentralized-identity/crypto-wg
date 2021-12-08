## Meeting - Thursday 11th November 2021 - (3pm ET)

### Chair
Tobias Looker

### Agenda
- IPR reminder, Agenda Review, and Introductions 
- [Issue Review](https://github.com/decentralized-identity/crypto-wg/issues)
- [Proposal Review](https://github.com/decentralized-identity/crypto-wg/pulls)
- [Work Item Reports](https://github.com/decentralized-identity/crypto-wg/tree/main/work_items)
    - [BBS+ Issue 10](https://github.com/decentralized-identity/bbs-signature/issues/10)

### Attendees
* Srinath Setty
* Brent Zundel
* juan caballero (Spruce/DIF)
* David Waite
* Steve Todd
* Andreas Freitag
* Mike Jones
* Matt Raffel (kiva)

### Notes
#### Issue Review
no open issues

#### PR Review
- #8 = no update (Steve)
- #15 = no update (Steve inadvertant co-owner)

#### Work Item status
- [bbs signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bbs_signatures.md)
    - issue [#10](https://github.com/decentralized-identity/bbs-signature/issues/10) - awareness about order of messages
        - 3 design options
            - no awareness - most flexible for higher layers
            - current approach - prefix with bit array to match order to underlying order (doesn't allow for canonicalization algos or higher-level users which need to reorder, i.e. LDP URDNA)
            - append a more elaborate structure - byte array of indices referring to the message order in underlying dataset
        - hard to summarize but reading the whole issue recommended; #3 not popular
        - update: vasilios - intending to present his findings at the next WG mtg
            - the #1 option - reordering for URDNA purposes would happen at LDP layer (and only there), leaving BBS sig layer blissfully ignorant
            - the #2 option - specify Dan Yamamoto's more explicit solution mentioned [here](https://github.com/mattrglobal/jsonld-signatures-bbs/issues/158#issuecomment-946576175)

- [bof secure software supply chain](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bof_secure_software_supply_chain.md)
    - no update
    
- [CBB Data Encoding](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_data_encoding.md) & [CBB Crypto Service Protocol](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_service_protocol.md)
    + steve: if you're interested in providing input or have use-cases, reach out to steve on DIF Slack!
    
- [cbb_delegatable_anonymous_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_delegatable_anonymous_credentials.md)

- [cbb_policy_as_code](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_policy_as_code.md)
    - #27 = no update (Juan has heard nothing about it)

- [JSON Web Proof](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/json_web_proof.md)
    + Presenting next week at W3C-CCG!
    + issues and PRs proceeding at a good clip; 
    + multiple drafts at different levels
        + proof algos already drafted
        + analogue of a JWT starting to be drafted

- [revocation_methods_for_verifiable_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/revocation_methods_for_verifiable_credentials_.md)
    - Housekeeping and cleaning up the documents
        - We have now 3 schemas for further assessment
        - We created a presentation and started graphical description
    - We need to get the in the details and decide on design options for each schema.
    
- [Spartan ZKP signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/spartan_zkSNARK_signatures.md)
    - no updates, still getting started and laying groundwork 
    
