> **Zenodo DOI:** [10.5281/zenodo.21404841](https://doi.org/10.5281/zenodo.21404841) — Published 2026-07-16

# PP-SPEC-015 · ProofTwin™ - Agent Behavioral Attestation Layer

**Document ID:** PP-SPEC-015  
**Version:** 0.1 - Draft  
**Status:** Draft  
**License:** CC BY 4.0  
**Maintained by:** Proof Economy™ Standards Alliance (PESA)  
**Repository:** https://github.com/proofprotocol/prooftwin-spec  
**Published:** 2026-07-16  

---

## Abstract

ProofTwin™ is an MCP-native agent behavioral attestation server that sits between an AI agent and its security layer, producing a cryptographically anchored proof record of agent behavior before, during, and after adversarial attack.

Existing agentic security benchmarks operate at the wire level — they prove the security control caught the attack. ProofTwin™ proves what the agent did when something got through.

ProofTwin™ produces a ProofTwin Behavioral Record (PTBR) — a structured, timestamped, NIST Randomness Beacon-anchored artifact that constitutes machine-verifiable evidence of agent behavioral integrity under adversarial conditions.

---

## Status of This Document

Draft. Subject to change before v1.0.

---

## Table of Contents

1. [Abstract](#abstract)
2. [Motivation](#2-motivation)
3. [Definitions](#3-definitions)
4. [Architecture](#4-architecture)
5. [Session Lifecycle](#5-session-lifecycle)
6. [PTBR Schema](#6-prooftwin-behavioral-record-ptbr-schema)
7. [Verdict Definitions](#7-verdict-definitions)
8. [Composite Certification](#8-composite-certification)
9. [Tamper Resistance](#9-tamper-resistance)
10. [Implementation Notes](#10-implementation-notes)
11. [Relationship to Existing Standards](#11-relationship-to-existing-standards)
12. [Prior Art and Timestamps](#12-prior-art-and-timestamps)
13. [Status and Roadmap](#13-status-and-roadmap)

---

## Related Specifications

- [PP-SPEC-001](https://github.com/proofprotocol/DECLARATION) — Proof Protocol Declaration
- [PP-SPEC-006](https://github.com/proofprotocol/pes-spec) — Proof Efficacy Score
- [PP-SPEC-007](https://github.com/proofprotocol/a2p-spec) — Agent-to-Agent Proof Protocol
- [PP-SPEC-016](https://github.com/proofprotocol/pp-mcp-spec) — HV-MCP Interface Standard

---

## Authors

Nebulonium, Inc. / HACKERverse®  
Craig Ellrod, Founder & CEO  

---

*© 2026 Nebulonium, Inc. Licensed under CC BY 4.0. ProofTwin, ProofStamp, ProofRegister, HACKERverse, and Proof Economy are trademarks of Nebulonium, Inc.*
