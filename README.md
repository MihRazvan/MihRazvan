### Security Engineer | AI Systems for Blockchain Security | 16x Hackathon Winner

I became an engineer after losing my portfolio in the 2022 Harmony Bridge hack. I now work the other side of that problem: securing on-chain systems, and building the AI tooling that finds the bugs before attackers do.

I build **multi-agent AI systems for automated vulnerability discovery** and apply them to **blockchain and DLT internals**. Most of my work goes into the mechanisms that make an automated result trustworthy.

---

## Current Work

### Security Engineer — Astrarizon / Pulsar *(April 2026 – Present)*

[Pulsar](https://pulsar.money) is a self-custodial neobank: cards, swaps, earn, and cross-chain transfers. I own security for the on-chain surface.

**AI tooling for security**
* Build AI orchestration and **agent harnesses for internal security audits** — automated review pipelines run against the backend monorepo ahead of each release.
* Build **security monitoring tooling** for on-chain activity and integration health.
* Threat modelling across the card, custody, and DeFi integration surfaces.

---

### Bittersteel — AI system for protocol and DLT security

An AI system for finding security defects in protocol clients and specifications, and for establishing which of them are real.

It began as a single agent orchestrating subagents against smart contracts. That shape fails in one specific way: when the orchestrator's context compacts, facts disappear silently, and when the orchestrator is wrong, every subagent inherits the error as a premise.
It has since grown into a system that:

* **compiles a protocol into a security model** — properties, actors, object lifecycles, state ownership, validation handoffs — so investigations search histories and relationships rather than scanning source files;
* **runs independent lines of enquiry** deliberately kept from anchoring on one another, with disagreement between them recorded as evidence rather than reconciled away;
* **owns durable cases** with their own state machine — decide, execute, incorporate, with rollback — each driven by the single unanswered fact that most changes its outcome;
* **executes for real** against client builds, harnesses and isolated devnets, with every run pinned, leased and archived.

Currently pointed at Ethereum — ~90 investigations run to disposition across Geth, Besu, Erigon, Nethermind and ethrex.

---

## Featured Projects

### [Anyware](https://github.com/MihRazvan/ETH_Prague_Hackathon) — trustless cross-chain state verification
***1st Place, Ethereum Core — ETH Prague 2026***

Verifies Ethereum L1 state directly on another chain using EIP-4788 beacon roots, with no relayer, oracle, or bridge in the trust path.

* **Trust path:** EIP-4788 beacon root → SSZ inclusion proof → execution `stateRoot` → MPT account proof → MPT storage proof
* **Why it matters:** removes the off-chain attestation layer that has repeatedly been the weakest link in cross-chain infrastructure
* **Adoption:** 100+ downloads across core packages within 24 hours of launch
  * [`anyware-prover`](https://www.npmjs.com/package/anyware-prover) — TypeScript SSZ and MPT proof assembly
  * [`anyware-solidity`](https://www.npmjs.com/package/anyware-solidity) — on-chain beacon-consensus verification

### [Autark](https://github.com/MihRazvan/Autark) — DevSecOps for self-sovereign frontends
***1st Place, Privacy — ETH Rome 2025***

A governance layer for frontend deployment, built on the premise that a compromised developer machine or CI token can ship malicious code to production in minutes — and that the frontend becomes the weakest link even when the contracts are sound.

* **Multi-party approval** via Safe multisig before any release executes
* **Immutable, versioned ENS releases** instead of mutable overwrite-in-place deploys
* **Content-addressed IPFS storage** that can be independently verified
* Subdomain creation and contenthash assignment bundle into a single atomic Safe transaction

---

## Open Source & Bug Bounty

* **[open-kritt](https://github.com/Kritt-ai/open-kritt)** — reported and resolved two scan-runner configuration bugs in an open-source security scanning engine: [#42](https://github.com/Kritt-ai/open-kritt/issues/42) (environment variable conflict silently overwriting a custom runner image) and [#43](https://github.com/Kritt-ai/open-kritt/issues/43) (default-on auto-prune deterministically deleting it). Both fixed.
* **[Immunefi](https://immunefi.com/profile/magento/)** — first confirmed finding (Low severity) in a competition, submitted using tooling I built myself.

---

## Other Hackathon Podiums

| Project | Result | Event |
|---|---|---|
| [Trust City Exchange](https://github.com/MihRazvan/agents) | 2nd | PL Genesis — autonomous AI agent marketplace, ERC-8004 identity and reputation |
| [Cloakline](https://github.com/MihRazvan/cloakline) | 2nd, Infra | PL Genesis — privacy-preserving RPC proxy encrypting operational logs via Zama fhEVM |
| [Bulwark](https://github.com/MihRazvan/bulwark_scroll) | 2nd, DeFi | Scroll Open 2025 — cross-protocol yield optimisation and risk rebalancing |
| [Pipe IT!!](https://github.com/MihRazvan/bucharest_hackathon) | 1st | ETH Bucharest 2025 |
| [Theseus Alpha](https://github.com/MihRazvan/theseus_alpha) | 1st | Encode University |
| [Tabula](https://github.com/MihRazvan/agentic_hackathon) | 2nd | ETHGlobal Agentic Hackathon 2025 |
| [SHIELD SPACE](https://github.com/MihRazvan/SHIELDSPACE-ETHRome) | 2nd | ETH Rome 2024 |

---

## Experience

**Security Engineer — Astrarizon** *(April 2026 – Present)*
Security for Pulsar, a self-custodial neobank. AI audit tooling, security monitoring, threat modelling, and ownership of the on-chain and DeFi integration surface through launch to 10,000+ users.

**Full Stack Blockchain Developer — Astrarizon** *(April 2025 – April 2026)*
Scaled white-label gamification infrastructure to **2,000,000+ active users**. Built a Web3 ticketing protocol processing **400,000+ NFT tickets**. Managed Token Generation Events and on-chain indexing across EVM and Solana.

**Web3 Developer Intern — Skytrade** *(Nov 2024 – April 2025)*
Engineered a Solana program in Rust/Anchor for cNFT fractionalisation into SPL tokens. Implemented PDA-based authority and vault state management.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/razvanmih/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:razvan.mihailescu1996@gmail.com)

