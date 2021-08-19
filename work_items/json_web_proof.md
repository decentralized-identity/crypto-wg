# JSON Web Proof

The JOSE-based standards of JWS, JWT, JWK, etc are widely deployed and well understood, but they lack the ability to support newer privacy-oriented features such as selective disclosure and unlinkability.

This work item is to incubate an addition to the JOSE family called JSON Web Proof (JWP) that adheres as close as possible to the patterns established there, but incorporates support for using Zero-Knowledge Proofs instead of traditional signatures.  The scope of this incubation also includes developing the same analog for COSE, a CBOR Web Proof that mirrors the same features.

The initial JWP proposal and planned space for the development of this work is at: https://github.com/json-web-proofs/json-web-proofs

The intent is to discuss and develop these as minimal container formats in order to ensure there is a viable strategy with a useful result before starting the official standards process within the IETF.

## Work Item Owners
- Jeremie Miller (@quartzjer)
- Mike Jones (@selfissued)
- David Waite (@dwaite)

## Outcome
The outcome is an Internet Draft that is the starting point for a new standards track effort within the IETF (might be a new Working Group, re-opening a previous one, add to an existing one, etc).

## Deliverables
- Internet Draft
- Experimental Implementations (minimum two)
- Six Month Timeline

## Meetings
- A bi-weekly work item call to review open issues/PRs and discuss implementor feedback
- Notes will be published in the official work item repo at https://github.com/json-web-proofs/json-web-proofs
