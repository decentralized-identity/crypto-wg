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

## Meeting - Thursday 30th September 2021 - (3pm ET)

### Chair
Brent

### Agenda
- IPR reminder, Agenda Review, and Introductions 
- [Issue Review](https://github.com/decentralized-identity/crypto-wg/issues)
- [Proposal Review](https://github.com/decentralized-identity/crypto-wg/pulls)
- [Work Item Reports](https://github.com/decentralized-identity/crypto-wg/tree/main/work_items)

### Attendees
- Brent Zundel
- David Huseby
- Seth Back
- Andreas Freitag
- David Waite
- Steve Todd
- Mike Jones
- Tomislav Markov
- Andrew Whitehead
- Orie Steele
- Tobias Looker
- Brian Richter
- Kristina Yasuda

### Notes
#### Issue Review
https://github.com/decentralized-identity/crypto-wg/issues/24 should be resolved today

#### PR Review
- merged PR 30 https://github.com/decentralized-identity/crypto-wg/pull/30
- PR 27 needs feedback: https://github.com/decentralized-identity/crypto-wg/pull/27
- PR 15 https://github.com/decentralized-identity/crypto-wg/pull/15: good feedback from participants. Scope has changed somewhat so it may need to be tweaked a bit before accepting the work item.
    - how is this different from JWP? Is this an expression for the results of an algorithm, or is it an algorithm? It is an algorithm, the encoding is outside the scope
    - It what sense can this be authentication, if there is no stable identifier? What something is being authenticated? This is a capabilities-based system, a way of issuing tokens for accessing an endpoint without correlation. Proof that you possess a token, but the token itself is randomized.
    - The title is wrong, that is authorization, not authentication.
    - Does this overlap with privacy pass? there are fundamental differences. PP has different security economics. May be worth checking with the PP WG to see what they're currently talking about.
    - IETF Privacy Pass WG: https://datatracker.ietf.org/wg/privacypass/
    - Next steps:
        - reach out to PP WG, see if they bite
        - fix title
        - update the description to be less confusing, this is for cap authorization not authentication
        - also mention potential integration with openid
        - address comments from Tobias about encoding being outside of the scope
- PR 8 https://github.com/decentralized-identity/crypto-wg/pull/8 Mitwicki came in with some proposed changes from the KERI WG
    - has Item owners
    - should compare lists of requirements between this and similar efforts

#### Work Item status
- [bbs signatures](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bbs_signatures.md)
    - had biweekly meeting with some new attendees. 
    - Filed some issues
    - things are moving forward
    - new slack channel being created:
- [bof secure software supply chain](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/bof_secure_software_supply_chain.md)
    - made contact with counterparts in the OpenSSF (open secure software foundation)
    - currently establishing the relationships
    - potential for a presentation and/or bof meeting at an upcoming meeting of the OpenSSF
- [cbb data encoding](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_data_encoding.md)
    - Steve is co-owner
    - does this need to be completed first? Sometimes encoding issues can hold up more impactful work.
    - trying to boil down requirements - why can't existing schemes do this?    
- [cbb_delegatable_anonymous_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_delegatable_anonymous_credentials.md)
    - no updates on this
- [cbb_policy_as_code](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_policy_as_code.md)
    - some discussion on whether to narrow focus to verifiable computation
- [cbb service protocol](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/cbb_service_protocol.md)
    - discussions around requirements
    - setting up requirement capturing documents
- [JSON Web Proof](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/json_web_proof.md)
    - having substantive discussions and raising issues related to the structure of the work.
    - JWT is built as a layer above JWS
    - JWP was originally thought of as a single layer, but now we're looking at a multi-signing layer, followed by a claims layer.
    - designing it so that it can be used with ZKP pairing friendly curves, as well as single use presentations from traditional algorithms.
- [revocation_methods_for_verifiable_credentials](https://github.com/decentralized-identity/crypto-wg/blob/main/work_items/revocation_methods_for_verifiable_credentials_.md)
    - Collected 8 methods 
    - 5 including description
        - 2 of them with a first implementation
    - 3 additional methods w/o sufficient description
    - Discussed the testcase including numbers (#10m items, 365epochs, about 1000 additions and 600 deletions per epoch)
    - Link to the google doc [link](https://docs.google.com/spreadsheets/d/1B6Koo8_wUoN4SPDvX7gaKBtkKBr6efOLwKIeVoy4mdI/edit#gid=1798866783) where you can find the method list, the assessment setup and future results

## Previous Meetings

- [Thursday 16th September 2021](meetings/2021-09-16/agenda.md)
- [Thursday 2nd September 2021](meetings/2021-09-02/agenda.md)
- [Thursday 19th August 2021](meetings/2021-08-19/agenda.md)
- [Thursday 5th August 2021](meetings/2021-08-05/agenda.md)
- [Thursday 22nd July 2021](meetings/2021-07-22/agenda.md)
- [Thursday 8th July 2021](meetings/2021-07-08/agenda.md)
- [Thursday 24th June 2021](meetings/2021-06-24/agenda.md)
