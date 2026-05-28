## Hi there 👋

I'm Randy, founder of [BabySea](https://babysea.ai) and maintainer of the [babysea-community](https://github.com/babysea-community) open-source repositories.

**TL;DR:** BabySea is the execution control plane for generative media. It gives developers one system to run image and video workloads across inference providers with predictable, observable, and adaptive execution.

I build open-source infrastructure for generative media: SDKs, primitives, and starters. The goal is to help creators, artists, designers, founders, and developers ship real image and video products without rebuilding the same execution, storage, billing, auth, webhook, and workflow layers from scratch.

Current projects include:

| Project                                                                                   | Taxonomy  | Status     | Boundary                                                                                               |
| :---------------------------------------------------------------------------------------- | :-------- | :--------- | :----------------------------------------------------------------------------------------------------- |
| [BabySea SDK](https://www.npmjs.com/package/babysea)                                      | SDK       | Production | TypeScript SDK for the BabySea execution control plane for generative media.                           |
| [Adaptive Island](https://github.com/babysea-community/adaptive-island)                   | Primitive | Production | Cache-first provider selection engine for multi-provider inference workloads.                          |
| [Ledger Fortress](https://github.com/babysea-community/ledger-fortress)                   | Primitive | Production | Atomic credit settlement engine for async inference workloads.                                         |
| [Rosetta Bridge](https://github.com/babysea-community/rosetta-bridge)                     | Primitive | Production | Request normalization engine for multi-provider inference workloads.                                   |
| [BabyChain](https://github.com/babysea-community/babychain)                               | Starter   | Production | Model chain API engine for image and video workloads with one durable pipeline and one final callback. |
| [Generative Media Starter](https://github.com/babysea-community/generative-media-starter) | Starter   | Working    | Credit-based generative media app starter with auth, prepaid credits, and private storage.             |
| [Sherin](https://github.com/babysea-community/sherin)                                     | Starter   | Working    | Self-hosted private workspace for generative media with own key, domain, and storage.                  |

Most of my open-source work comes from real execution problems I’ve faced while building BabySea: provider fragmentation, schema drift, async generation state, credit settlement, private storage, webhook delivery, model routing, and production deployment.

If you are building with generative media, these projects are for you.
