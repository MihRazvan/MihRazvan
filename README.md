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

An autonomous research system for finding security defects in distributed-ledger clients and specifications, built on one premise: **an automated finding is worthless unless the instrument that produced it can be shown to work.**

* **Surface compilation** — targets are extracted mechanically from executable specifications and system history rather than chosen by intuition, so coverage is measurable rather than asserted.
* **Bounded, reproducible investigation** — each line of enquiry runs as an isolated, budgeted task with pinned inputs, explicit preconditions, and distinct recorded outcomes.
* **Adversarial vetting with asymmetric authority** — the role arguing *for* a finding cannot kill it; the role arguing against it can kill only on executed evidence or a cited rule, never on argument alone.
* **Evidence tiers** — a lead's strength is always a tier with defined criteria, never a judgement call.
* **Control gating** — a clean result is not recordable unless a planted defect was detected in the same run, because *"nothing was found"* and *"the instrument never ran"* are indistinguishable in the output.

The same mechanisms generalise to how audits are run: the constraint on automated security work is not how much you can generate, but how much of it you can defend.

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

