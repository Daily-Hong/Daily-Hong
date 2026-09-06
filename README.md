# Jonghun Hong

**CEO, [Oraclizer](https://oraclizer.io)** — regulated tokenization infrastructure.

Oraclizer builds the state-synchronization layer between institutional ledgers and EVM execution, so a regulated asset means the same thing on both sides: same rights, same restrictions, same enforcement — provably.

### What we build

**[ERC-TRUST](https://github.com/Oraclizer/erc-trust)** — Typed Regulatory Uniformity for Security Tokens
A typed, fail-closed execution standard candidate. Six regulatory actions (`FREEZE` · `SEIZE` · `CONFISCATE` · `LIQUIDATE` · `RESTRICT` · `RECOVER`), each bound to its authority, evidence, replay guard, and a receipt any independent observer can recompute.
Verified across four engines — Isabelle/HOL, Certora, Kontrol/KEVM, Foundry — with a formal-verification corpus roughly 5× the size of the Solidity it verifies.

**ERC-8319 (RCP)** — the Regulatory Compliance Protocol the typed actions build on.

**[Formal verification](https://github.com/Oraclizer/formal-verification)** — mechanized state-transition and synchronization proofs, traced to code and tests rather than kept on paper.

**OSS state synchronization** — Canton ↔ EVM, bidirectional, with finality confirmation, mismatch detection, and recovery.

### Links

[oraclizer.io](https://oraclizer.io) · [docs](https://docs.oraclizer.io) · [research](https://research.oraclizer.io) · [X](https://x.com/Oraclizer)
