# DIF Applied Crypto WG – Rolling Agenda & Minutes

[![hackmd-github-sync-badge](https://hackmd.io/FdDDhUXkQdq2Iglrsfq-7g/badge)](https://hackmd.io/FdDDhUXkQdq2Iglrsfq-7g)

 

[WG projects](https://github.com/topics/wg-crypto) | [DIF page](https://identity.foundation/working-groups/crypto.html) | [Mailing list](https://lists.identity.foundation/g/crypto-wg) | [Recordings](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit#gid=339046779)

_For this call, you are encouraged to turn your video on. This is a good way to build rapport given we are a large, disparate group experiencing a lot of churn._

_This document is live-edited DURING each call, or shortly after the call, and stable/authoritative copies live on our github repo under /agenda.md .
Please note that we might not notice a pullrequest in time, but you are free to propose agenda items for future meetings via hackmd._

<details>
<summary> Meeting information - <b>3pm ET odd Thursdays</b></summary>
- Before your contribute - [**join DIF**](https://identity.foundation/join) and [sign the WG charter](https://bit.ly/DIF-WG-select1) (both are required!)
- Time: 3pm ET, time in ET
- [Calendar entry](https://calendar.google.com/event?action=TEMPLATE&tmeid=M2c5ZnRnZWFnbWxqdm9tOG5ncXNzMm1wYnJfMjAyMTA2MjRUMTkwMDAwWiBkZWNlbnRyYWxpemVkLmlkZW50aXR5QG0&tmsrc=decentralized.identity%40gmail.com&scp=ALL)
- [Zoom room](https://us02web.zoom.us/j/87960900967?pwd=Ti9KWXpyR0dkKzhEQ0lTTVkxOE1WQT09), Meeting ID: 879 6090 0967 , Password: 045023
</details>

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

    
## Previous Meetings
- Thursday 25th November **Cancelled due to Thanksgiving Holiday**
- [Thursday 11th November 2021](meetings/2021-11-11/agenda.md)
- [Thursday 28th October 2021](meetings/2021-10-28/agenda.md)
- [Thursday 30th September 2021](meetings/2021-09-30/agenda.md)
- [Thursday 16th September 2021](meetings/2021-09-16/agenda.md)
- [Thursday 2nd September 2021](meetings/2021-09-02/agenda.md)
- [Thursday 19th August 2021](meetings/2021-08-19/agenda.md)
- [Thursday 5th August 2021](meetings/2021-08-05/agenda.md)
- [Thursday 22nd July 2021](meetings/2021-07-22/agenda.md)
- [Thursday 8th July 2021](meetings/2021-07-08/agenda.md)
- [Thursday 24th June 2021](meetings/2021-06-24/agenda.md)
