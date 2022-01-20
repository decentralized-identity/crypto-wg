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

    
## Previous Meetings
- [Thursday 9th December 2021](./meetings/2021-12-09/agenda.md)
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
