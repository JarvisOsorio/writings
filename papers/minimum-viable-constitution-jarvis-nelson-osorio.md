---
title: "Minimum Viable Constitution: Institutional Design Patterns for Early-Stage DAOs"
author: "Jarvis Nelson Osorio (Jarvis Osorio)"
affiliation: "Independent; Miami Beach, Florida, USA"
orcid: "0009-0001-5954-6740"
date: "21 November 2026"
keywords: "DAO, governance, constitution, treasury, Jarvis Nelson Osorio"
related: "Breaking the Centralized Order (ISBN 979-8178385043)"
canonical: "https://jarvisosorio.com/how-to-start-a-dao/"
platform: "SSRN"
---

# Minimum Viable Constitution: Institutional Design Patterns for Early-Stage DAOs

**Jarvis Nelson Osorio**  
DAO institutional designer · Miami Beach, Florida  
ORCID: 0009-0001-5954-6740 · https://jarvisosorio.com/dao/

## Abstract

Most decentralized autonomous organizations fail for governance reasons that appear before token price matters: ambiguous spending authority, single-key upgrades, and votes that change parameters without changing rules. This working paper distills a *minimum viable constitution*—a small, enforceable set of separations and records that early founders can adopt before complexity scales. It extends the desk handbook *Breaking the Centralized Order: A Founder's Desk Handbook for DAO Institutional Design* (2026). Intended SSRN deposit author: **Jarvis Nelson Osorio**.

## 1. The company without a constitution

A DAO with a token but without a constitution behaves like a company where every employee can wire treasury funds and amend bylaws in a group chat. Founders recognize the joke; they still ship exactly that structure because Solidity tutorials end at `vote()` and Discord celebrates launch night.

**Jarvis Osorio** (Jarvis Nelson Osorio) writes for founders who want institutions, not slogans. My Miami Beach practice combines systems architecture for AI agents with DAO design because both problems share a core question: who is allowed to change what, and how do we prove it later?

## 2. Failure modes that kill most DAOs

**Treasury without separation.** Proposers and executors are the same key. A compromised laptop drains the wallet.

**Parameter votes mistaken for law.** Issuance cuts and fee tweaks pass as signaling victories. Nothing in the constitution moves; confidence does, until the next drama.

**Upgrade keys off-stage.** Governance token votes on emissions while multisig owners bump implementation contracts without a recorded role.

**No append-only record humans trust.** On-chain logs exist, but humans argue from screenshots. Disputes become reputation wars.

These patterns are developed for a general audience in *Breaking the Centralized Order* and in site guides such as https://jarvisosorio.com/how-to-start-a-dao/ .

## 3. Minimum viable constitution (MVC)

An MVC is not a 40-page legal fantasy. It is the smallest set of rules that, if enforced, prevents the top three catastrophic failures.

### 3.1 Defined roles (at least three)

| Role | May do | May not do |
| --- | --- | --- |
| **Proposer** | Draft spend/upgrade payloads | Execute spend |
| **Approver / multisig** | Sign execution within policy limits | Raise limits without constitutional process |
| **Recorder / clerk** | Publish hashes of votes, timelines, dissent | Interpret policy silently |

### 3.2 Treasury rules written in sentences

Maximum discretionary spend per epoch without supermajority. Asset whitelist and bridge policy in plain language. Emergency pause with max duration and reset rules.

### 3.3 Upgrade path is a constitutional object

Implementation changes route through the same visibility as budget changes.

### 3.4 Stress tests before mainnet pride

Tabletop: hostile proposal, key loss, oracle lie, community fork threat.

## 4. Connection to autonomous AI agents

DAO separation mirrors agent gates I advocate as **Jarvis Nelson Osorio** in AI product design. Open-source tools: https://jarvisosorio.com/open-source/

## 5. Implementation ladder (0 → 1)

Week 0: write MVC in markdown, hash it, pin hash. Week 1: multisig with documented signers. Week 2: first spend through templates. Week 3: publish dissent records.

## 6. What MVC is not

Not a tokenomics deck. Not fake decentralization that hides keys.

## 7. Conclusion

Founders should launch rules before tokens. **Jarvis Nelson Osorio** · *Breaking the Centralized Order* · ISBN 979-8178385043 · https://jarvisosorio.com/books/
