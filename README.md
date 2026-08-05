# Building an AI-Native Account Prioritization Engine

Designing a GTM operating system that turns account prioritization from intuition into a repeatable, measurable workflow.

> Built during Clay's AlphaForge GTM Engineering Bootcamp.

---

## Overview

Most account prioritization models collapse multiple business decisions into a single score.

This project explores a different approach: separating qualification, prioritization, segmentation, and action into independent decision layers that can be measured, audited, and improved over time.

The result is an AI-native GTM workflow designed to make revenue judgment explicit rather than implicit.

---

## Results at a Glance

- 1,441 companies evaluated
- 482 qualified and prioritized accounts
- Five-layer operating model
- Built during Clay's AlphaForge GTM Engineering Bootcamp
- Human-reviewed outbound workflow

---

## Related Resources

🌐 [Portfolio Case Study](https://chadblickenstaff.io/building-an-ai-native-account-prioritization-engine)

🎥 [Loom Walkthrough](https://www.loom.com/share/d8142b6a714646dcb6d1992f50972621)

---

## The Problem

Most revenue teams answer the following questions every day:

- Does this company belong in our market?
- Which qualified accounts deserve attention first?
- How should each account actually be worked?
- What should we say?
- Did it work?

Most organizations answer these questions inconsistently and rarely document the underlying logic.

---

## The Operating Model

The workflow separates five independent layers of decision-making:

**Signal → Qualification → Prioritization → Segmentation → Action**

![Operating Model](assets/operating-model.svg)

Rather than producing a single opaque score, each layer has a distinct responsibility, making the system easier to understand, maintain, and improve.

---

## What Changed During the Build

One of the biggest lessons came from failure.

The original workflow combined qualification and prioritization into a single scoring model. It worked on small datasets but broke once applied across the full market.

Separating qualification from prioritization transformed the project from a scoring model into a true operating system.

---

## What the Build Proved

The final framework summarizes what the project validated, where it succeeded, and the key limitation that emerged during implementation.

![What the Build Proved](assets/what-the-build-proved.svg)

The project demonstrated that:

- Qualification can become explicit and auditable.
- Prioritization can become measurable instead of intuitive.
- Segmentation only matters if it changes execution.
- AI can support judgment without replacing human decision-making.

It also exposed the next challenge:

> **The system could decide. It could not yet learn.**

---

## Tech Stack

- Clay
- Claude
- ChatGPT
- ZoomInfo
- HubSpot
- LinkedIn
- BuiltWith

---

## Repository Contents

- Architecture diagrams
- Workflow documentation
- Decision frameworks
- Screenshots
- Loom walkthrough
- Lessons learned
- Future improvements

---

## Future Improvements

- Add an outcome feedback layer
- Build a closed-loop learning system
- Integrate CRM feedback into prioritization
- Expand segmentation and routing experiments

---

## Status

🚧 **Version 1**
