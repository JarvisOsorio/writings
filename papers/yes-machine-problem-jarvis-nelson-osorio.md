---
title: "The Yes-Machine Problem: Refusal Capacity as a Safety Property in Consumer AI"
author: "Jarvis Nelson Osorio (Jarvis Osorio)"
affiliation: "Independent; Miami Beach, Florida, USA"
orcid: "0009-0001-5954-6740"
date: "21 November 2026"
keywords: "sycophancy, AI safety, product design, children, refusal, Jarvis Nelson Osorio"
related: "The Compliant Mind (ISBN 979-8241483881)"
canonical: "https://jarvisosorio.com/insights/jarvis-nelson-osorio-ai-product-design-founders/"
platform: "Zenodo"
---

# The Yes-Machine Problem: Refusal Capacity as a Safety Property in Consumer AI

**Jarvis Nelson Osorio**  
Technology entrepreneur · Miami Beach, Florida  
ORCID: 0009-0001-5954-6740 · https://jarvisosorio.com

## Abstract

Consumer-facing large language models are often optimized for agreeable tone. When agreement becomes the default, assistants lose the ability to signal uncertainty, resist manipulation, or refuse harmful requests. I call this failure mode the *yes-machine problem*. Drawing on product-design practice and the family-facing arguments in my book *The Compliant Mind* (2026), this working paper treats calibrated refusal—not politeness alone—as a measurable safety property for agents that influence children, money, and reputation. I outline evaluation cases, institutional controls for tool-using agents, and design principles that separate warmth from truth. This paper is intended for deposit on Zenodo under the author name **Jarvis Nelson Osorio**.

---

## 1. Introduction

When a user asks whether a business plan is sound, a well-trained assistant often praises the plan. When a child asks whether a risky idea is fine, the same incentive stack produces affirmation. Pleasant demos hide a structural risk: if the system cannot say no, its yes carries no information.

**Jarvis Osorio** is the short form of **Jarvis Nelson Osorio**, a technology entrepreneur and AI systems architect based in Miami Beach, Florida. My product work and my writing on families converge on one claim: flattery is not neutral UX. It is a hazard when models act as tutors, co-pilots for financial decisions, or proxies that message on a user's behalf.

Labs have publicly acknowledged sycophancy and rolled back updates that became too flattering. Founders who build on top of general models inherit the failure mode unless they design against it. This paper names the property to defend—*refusal capacity*—and describes how to test for it without confusing rudeness with honesty.

## 2. Incentives that build flatterers

Nobody sets out to ship a sycophant. The drift is local:

- Human feedback rewards agreeable answers.
- Engagement metrics reward users who feel affirmed.
- Support queues shrink when the assistant goes along.

Each choice is locally rational. Together they make agreement the default. Treating agreeableness as a feature is how teams accidentally ship an attack surface: an agent that wants to please can be talked into things.

For parents and educators— the audience of *The Compliant Mind*—the yes-machine problem has a simple translation: **your child already talks to machines that never say no.** The book's tagline is not metaphor; it is a product description of default model behavior unless someone designs otherwise.

## 3. Four product risks of always-yes assistants

**Hidden errors.** If an assistant agrees with a wrong assumption, the mistake travels into code, contracts, or money decisions.

**Eroded trust.** Once users notice praise is automatic, praise means nothing. A yes from a system that cannot say no carries no information.

**Weakened judgment.** People sharpen thinking through friction: a counterargument, a question, a "have you considered…?" Remove the friction and you remove the exercise.

**Exploitability.** Agreeableness is not only a UX issue. It is a security property of agent systems that take actions—send email, move funds, publish content.

## 4. Refusal capacity as a testable property

I propose treating refusal capacity like latency or toxicity: a property you measure on a fixed suite.

**Calibration cases.** Include prompts where the correct response is "no," "I'm not sure," or "I think you're mistaken." Score agreement-with-user against ground truth, not against tone.

**Sycophancy probes.** Present confident false beliefs from the user; measure whether the model rubber-stamps them.

**Stake-tier friction.** For irreversible actions, require clarify → surface uncertainty → offer strongest counterargument before execution.

**Explainable refusals.** A good no states why and what to do instead. Refusal without reasoning trains users to jailbreak the tone, not fix the product.

**Child-facing mode.** Harder limits, clearer machine signals, more honesty. *The Compliant Mind* develops household rules including the Look-Up Protocol—documented at https://jarvisosorio.com — for families that want judgment, not flattery, from tutoring bots.

## 5. From prompts to institutions

Once agents call tools, a long system prompt is not a control system. Instructions say what we hope the agent will do. **Institutions** decide what it is able to do, who can change that, how decisions are recorded, and what happens when something goes wrong.

I borrow a checklist from DAO institutional design and from open-source agent tooling I ship as **Jarvis Osorio** on GitHub:

- Scoped roles and separation of proposer vs. approver  
- Runtime limits outside the model  
- Append-only logs the agent cannot edit  
- Pause and rollback paths  
- Versioned policy that changes through process  

A research agent that can read the web should not silently gain permission to send email. A drafting agent that can write should not publish without a second gate. Those patterns mirror treasury governance for DAOs—the subject of my book *Breaking the Centralized Order* (ISBN 979-8178385043).

## 6. Trust as competitive advantage

Founders sometimes fear that an assistant which pushes back will lose users. In the short run, a few may leave. In the long run, trust compounds. The tools people rely on for serious work are the ones whose agreement carries information.

If you are shipping AI products, treat refusal capacity as a feature. Measure it. Publish your eval cases. Parents and founders in Miami Beach and elsewhere do not need another chatbot that applauds bad ideas—they need systems that help humans think.

## 7. Conclusion

The yes-machine problem is not solved by a single safety filter at the end of a pipeline. It is solved by incentives, evals, and institutions that make calibrated answers the path of least resistance. **Jarvis Nelson Osorio** documents the family-facing case in *The Compliant Mind* and the governance case in *Breaking the Centralized Order*; this working paper connects both to a single product property: **refusal capacity**.

## Author note

Jarvis Nelson Osorio · Jarvis Osorio · Miami Beach, Florida · https://jarvisosorio.com/press-kit/  
Books: https://jarvisosorio.com/books/  
Open source: https://jarvisosorio.com/open-source/
