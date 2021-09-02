# Revocation Methods for Verifiable Credentials

The goal is to identify and define revocation methods for authentic data, to manage the validity of verifiable credentials and create the protocol to ensure interoperability.
In this work item, possible revocation methods should be collected and assessed. Suitable revocation methods should be defined in a revocation protocol. 

Tasks:
- Collect possible revocation methods
  - Cryptographic accumulator suggestion by Mike (https://hackmd.io/O4c3wiLZQLeXuXirm7dl9A#Math-explaination)
  - tbd

- Define an assessment setup (#of entries, #of revocations per epoch,...)for performance testing
- Define requirements for privacy (correlation (linked, linkable), traceability, leaking of usage data,..)
- Define performance requirements (computational effort, storage, data transmission, sizes,...)
- Assess the revocation methods and define one or more revocation methods that fits the purpose
- Create the protocol 

## Work Item Owners
- Andreas Freitag (andreas.freitag.77@gmail.com)
- Mike Lodder (redmike7@gmail.com)
- Dave Huseby (dave@cryptid.tech)

## External Partners
**This is only for work items intended for transition to an external standards
body after incubation here. This may be filled in later and is not required for
initial approval of the work item.**:
- W3C
- Hyperledger Ursa/Aries

## Outcome
One (max. three) scalable and privacy-preserving revocation method(s) are described on the protocol level.
The revocation method can be implemented and is interoperable if you follow the defined protocol.

## Deliverables
- Assessment set up for technical and privacy requirements
- Result of the assessment
- Explanation of why we choose a method
- Description of the method
- Protocol as a base for implementation

- **What's the expected timeline?**
Feb.2022
- **Who's the audience of your deliverables?**
All implementers of SSI solutions

- **What are related resources or standards from DIF or adjacent organizations?**

## Meetings
- bi-weekly status calls
