## Proposal Overview

### Poll & Vote over Nostr protocol

The initial idea was to integrate the ability of logical clocks into Nostr networks, this proposal integrates the VLC with Nostr protocol through new NIPs and reconstructs the development mode of social network applications in a very simple way.

### Proposal Details

We hope to create a new voting scheme in a completely decentralized network environment, utilizing the eventual consistency capability of Hetu logical clocks, without the need for any trusted third parties or consensus algorithms, and with easy scalability. This capability cannot be achieved simply by modifying existing Nostr protocols and blockchains.

In terms of technology stack, our proposal is divided into three layers:
- P2P Logical Clock Layer
- Nostr Relay
- Nostr Client

You can see the specific architecture [here](https://github.com/hetu-project/ZSocial/blob/main/zchronod/doc/zchrono_framework.md).

We introduce new [NIP](https://zsocial.gitbook.io/zsocial/nip/nip-3041-poll-and-vote-event-with-vlc). There is no difference in event handling between NIP-3041 and other NIPs. The only difference is that when receiving a new event, it constructs a new state structure which can be transmitted to chronod nodes associated with the relay at the P2P Logical Clock Layer. In this layer, nodes communicate through the Gossip protocol.

When votes are continuously transmitted to chronod nodes, the P2P Logical Clock Layer merges these states and eventually obtains a consistent result. This result can be presented to users at the client level.

## Team:

### Members

- Team leader: 
[fshif](https://github.com/fshif)
- Team members: 
[peter-jim](https://github.com/peter-jim);
[sglk123](https://github.com/sglk123); 
[bai123-123](https://github.com/bai123-123)

### Contact
- contact@nagara.dev

## Development Roadmap

### Overview

- **Total Estimated Duration:** 2 weeks

### Milestone

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 1. | design doc  | The design document includes the specific design of the entire proposal and modification tutorial, as well as a new Nostr NIP example. |
| 2. | zchronod  | zchronod includes a self-running node program, which contains the VLC and some processing logic for new states. |
| 3. | relay & client | Modified Nostr relay and client, used to be compatible with the new NIP and demonstrate how to use the new features. |


## Future Plans

We will continue to improve this proposal, making it more user-friendly and clearer in terms of document content, and fixing the bugs that arise during the testing process. 

At the same time, we will utilize the existing zsocial stack to implement new proposals for nostr and Hetu logical clock.

