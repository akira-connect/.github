# Hi 👋

I'm Randy Aries Saputra, founder and developer building **BabySea**, the execution control plane for generative media.

I focus on infrastructure for AI workloads: provider routing, async execution, credit settlement, webhooks, idempotency, failover, observability, and security invariants.

BabySea is not a provider wrapper. It is the execution layer behind image and video generation workloads.

---

## What I build

I build systems around one question:

> What has to stay correct when AI workloads become async, expensive, multi-provider, and failure-prone?

That usually means working on:

- generative media execution
- model/provider routing
- async generation lifecycle
- Stripe credit settlement
- Supabase/Postgres invariants
- Databricks routing intelligence
- Upstash cache/rate-limit layers
- SDKs and developer tools
- security testing and operational trust

## BabySea

**BabySea** gives developers one API/SDK for image and video generation while managing the execution layer underneath:

- model and provider access
- normalized generation schemas
- async lifecycle management
- provider failover
- routing policy
- credit reservation and settlement
- webhooks
- usage and billing state
- regional execution

Website: https://babysea.ai  
Playground: https://us.babysea.ai/playground  
SDK: https://github.com/babysea-ai/babysea  
npm: https://www.npmjs.com/package/babysea

## Open source

BabySea OSS projects are organized into three categories.

### OSS Primitives

Production-derived infrastructure patterns extracted from BabySea's execution control plane. These isolate one hard system invariant at a time.

- 🏝️ [`adaptive-island`](https://github.com/babysea-ai/adaptive-island)  
  Cache-first provider selection for multi-vendor AI workloads. Built on Databricks, Upstash, and Supabase.

- 🏰 [`ledger-fortress`](https://github.com/babysea-ai/ledger-fortress)  
  Atomic credit settlement for async AI workloads. Built on Stripe and Supabase.

### SDKs

Typed developer entry points into BabySea's execution control plane.

- 🌊 [`babysea`](https://github.com/babysea-ai/babysea)  
  Open source TypeScript SDK for the BabySea execution control plane for generative media.

### OSS Starters

Deployable reference applications that help builders adopt BabySea patterns quickly.

- 🐧 [`generative-media-starter`](https://github.com/babysea-ai/generative-media-starter)  
  Launch a credit-based generative media app. Built with Next.js, Supabase, Stripe, Upstash, and the BabySea SDK.

## Current focus

I am currently building and publishing the infrastructure patterns behind BabySea:

- routing intelligence for AI providers
- atomic billing and credit settlement
- developer SDKs for generative media
- deployable starters for AI builders
- public security and trust artifacts

I write technical deep dives around the systems I build.

Blog: https://babysea.ai/blog

## Security and trust

I care about execution-layer correctness.

For AI infrastructure, security is not only about blocking bad requests. It is about preserving invariants under pressure:

- identity must come from verified API keys
- account boundaries must hold
- regional replay must fail
- malformed input must stop at validation
- SSRF must not reach internal resources
- provider callbacks must not be forgeable
- retries must not create duplicate work
- credit settlement must remain balanced

Public security reports:  
https://github.com/babysea-ai/babysea-security-reports

## Technical interests

- AI infrastructure
- generative media
- distributed execution
- provider routing
- billing systems
- Stripe webhooks
- Postgres/RLS
- Databricks
- Supabase
- Upstash
- SDK design
- DevSecOps
- OSS developer tools

## Founder note

I started by building applications, then kept running into the same deeper problem:

The hard part was not only calling models.

The hard part was execution.

Different providers, different schemas, async jobs, retries, webhooks, billing state, failed generations, storage, refunds, and observability all had to work together.

That is why I am building BabySea.

## Links

BabySea: https://babysea.ai  
GitHub org: https://github.com/babysea-ai  
LinkedIn: https://www.linkedin.com/in/ariesrandy  
Email: dev@babysea.ai
