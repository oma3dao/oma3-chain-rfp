# OMA3 Request for Proposals
# OMA3 Home Chain

## Background

OMA3 is building decentralized smart contracts to enable its internal token-based governance system as well as interoperability standards for the metaverse.  OMA3 is considering building its own chain or choosing an existing chain for deployment of its smart contracts.    For more details on these projects, we reference our [Token Infrastructure](https://github.com/oma3dao/token-litepaper) and [Inter World Portaling System](https://github.com/oma3dao/portal-position-paper).  

This Request for Proposals is open to the public and any interested organization is invited to submit a proposal to be the home chain of OMA3’s infrastructure.  Organizations can be the governing body or administrator of an existing chain, or have a solution that will enable OMA3 to launch its own chain.

## Goals

OMA3 would like to achieve the following goals with its chosen infrastructure:

General goals:

  * Reliability:  strong preference for a tech stack already in production with a track record of performance and security.
  * Decentralized liquidity:  access to high liquidity through decentralized exchanges to reduce reliance on a token listing by centralized exchanges.
Usability:  the user interface should make it as easy as possible for users to bridge tokens between OMA3’s infrastructure, Ethereum, and other chains used by OMA3 members (see below).
  * Decentralized operations:  centralization (e.g.- sequencers, RFC nodes, client stacks) introduces operational risk as a single point of failure can bring down the network.
  * Decentralized governance:  centralization also cedes control to entities that OMA3 cannot control.  Any centralization of governance (if any) should be under the control of OMA3. 
  * Multichain interoperability:  OMA3 members already have applications deployed across a wide variety of EVM (Ethereum, Polygon, etc.) and non-EVM (EOS, Wax, Chromia, etc.) chains.  OMA3’s infrastructure should have a clear path to interoperability with all chains utilized by OMA3 members. Bridges and support for projects such as LayerZero and Hyperlane should be mentioned.
  * Performance guarantees:  If the chain is a public chain that allows permissionless deployment of smart contracts, the chain should give OMA3’s smart contacts the ability to guarantee its performance to users, so that other smart contracts on the chain do not interfere with the performance of OMA3’s infrastructure.  This could be solutions such as guaranteed blockspace or load balancing between shards or chains.
  * Development environment:  The chain should utilize a development environment that is reasonably accepted by Web3 developers such as EVM, Cosmos SDK, SVM, or Move VM.
  * Ethereum alignment:  The chain should leverage Ethereum security in some manner, such as through data availability (e.g.- Eigen DA) or state root settlement.
  * RPC API flexibility:  the chain architecture should allow OMA3 to define REST and GraphQL style APIs to augment the native transaction API of the chain client (e.g.- Ethereum RPC).
  * Privacy:  OMA3’s identity system aspires to be privacy preserving, so data associated with an ID can be kept private.  Note that this is a different form of privacy, privacy of data, which is different from private token transactions.

Goals specific to an existing chain: 

  * Shared gas fees:  The existing chain has a mechanism that rewards OMA3 a percentage of the gas fees generated by its smart contracts.  Other technologies that achieve the same goal of sharing gas fee revenue will also be considered.

Goals specific to a new chain: 

  * Native token:  As described in OMA3’s Token Litepaper, the infrastructure must have a solution to migrate the Ethereum ERC-20 OMA token to the new chain for use as the new chain’s native token.

## Requested Information

OMA3 requests organizations submit the following information in response to this RFP:

  * How the organization’s tech stack address each of the goals.  If the goals cannot be met immediately, provide a roadmap for how the goal can be met in the future or explain why the goal will not be met.
  * The costs associated with launching/deploying on the chain, and the ongoing costs after launch.
  * Can the organization invest monetary resources into the project, either via a grant program or a purchase of OMA tokens.  If so, what is the proposed amount.
  * Does the organization or its partners have development resources that can help with launch of the chain and smart contracts.
  * Is the organization willing to join OMA3 as a member.
  * Details on the technical stack, such as the originating code base, consensus algorithm, programming languages, etc.

## Timeline

TBD

## Contact Information

For inquiries or proposal submissions:

Alfred Tom, [atom@oma3.org](mailto:atom@oma3.org), TG: alfredctom

