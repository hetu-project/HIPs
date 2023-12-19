
# HIP-1: HIP Purpose and Guidelines

| Authors | Advaita Labs <hip@advaita.xyz>|
|--|--|
| Updated | 2023-12-19 |

## What is an HIP?
The Hetu Initiative Proposal (HIP) is an innovative proposal process promoted by the Hetu community. The goal of HIP is to enhance innovation capability and collaboration efficiency in open and inclusive communities. Through HIP, we hope to transform existing problems and improvement opportunities in our processes into valuable suggestions and specific action plans to better support Hetu protocol. These projects include the following three aspects:
- Development contribution
- Community-driven public products and innovation projects.
- Innovative and high-potential research projects.

A HIP must be a clear and complete description of the initiaitive. A single initiaitive is highly recommended that contain a single key proposal or new idea. 
## HIP Types
There are several different types of HIP, `A` `B` `C` used to distinguish different levels of HIP, and their processes will correspondingly be different.

### HIP-A: Communication layer
Proposals that affects the upgrade and major updates of all nodes within the Hetu network. It is necessary to fork the key components of Hetu (such as logical clock), cryptographic algorithms, and interfaces etc.

### HIP-B: Middleware & Extensions
Including proposals around client API/RPC specifications;the extension of data structure,network protocol and interfaces, existing network nodes can obtain locality capabilities (such as local ledgers, distributed key management, causal social networks, etc.) by upgrading their code without affecting the logic of underlying protocols and core components; using existing components to build application infrastructure, supporting building of cohort network and seamless access to Hetu Network.

### HIP-C: Application-level standards and schemes
Including proposals on applications and standards, these proposals provide users with innovative capabilities through the use of Hetu protocol, underlying extensions, data structures, and network transmission capabilities.

## Work Flow

### 1. Proposal

1. HIPs should be written in [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) format.
2. Fork the HIP repo, and modify the [Proposal template](https://raw.githubusercontent.com/hetu-project/HIPs/main/HIP_Proposal_Template.md) to create a proposal document with HIP type(e.g. HIP-A). 
3. Create a Pull Request to the HIP repository, make sure the email displayed on the proposer's GitHub should be one of the authors of HIP proposal document.

### 2. Proposal Review
1. The HIP review team will review most of the proposals,and discuss whether the type is appropriate.If the proposal is labeled as HIP-A, it need Hetu Core to discuss together and determine its appropriateness. If the proposal is labeled as HIP-B, HIP committee will determine its appropriateness.
2. Then proposal will be assigned a unique number(e.g. HIP-A-2) and notify the proposer. 
3. The proposer change the name of PR document to the assigned name and commit.
4. The HIP committee mark the PR as a `draft` status.
5. Unless specified otherwise,the day on which proposer change the name and commit will be considered the starting date of the project, and will be used to estimate delivery dates.

### 3. Proposal Delivery

1.  **Delivery**
    
    If a proposal`s goal is reached, the proposers should notify the HIP committee to perform acceptance checking. They should submit a delivery document.
    Using development as an example [Delivery Template](https://raw.githubusercontent.com/hetu-project/HIPs/main/HIP_Delivery_Template.md)

2.  **Delivery Review**
    
    Different types of proposals have different acceptance methods.

    `HIP-A`
    
    The proposal first needs to be voted on by the HIP committee. After approval, it needs to undergo a sufficiently long period of testing on the testnet. Then, it will be publicly discussed and confirmed for acceptance through a vote by Hetu Core.

    `HIP-B`
    
    A carefully selected acceptance team will review and accept the proposal. Some members of the HIP committee will be assigned to review the delivery and request changes on the delivery. Their feedback needs to be resolved before a proposal is accepted.

    `HIP-C`
    
    Criteria for acceptance of proposals:
    - They should make sense.
    - They should be optional and backwards-compatible.
    - They should be implemented in some applications when applicable.

3. **Incentive Relivery**
    
    The applicants will receive the badges representing achievement if the deliveries are accepted.


## Badges

As a primary form of incentive, Badges have different levels, as a recognition of community contribution and value.

Badges incentive can include various series:

- Member passes, As a symbol of identity for early participants in some kind of organization.

- Proof of Contribution, as proof of the amount of work contributed to the agreement and community.

- The Badges binding the core IP value of excellent content.
  

## Copyright

Copyright and related rights waived via  [CC0](https://creativecommons.org/publicdomain/zero/1.0/legalcode).
