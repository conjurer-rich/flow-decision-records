---
permalink: /docs/overview
title: "Overview"
layout: single
sidebar:
  nav: "docs"
classes: wide
---

## What is a Flow Decision Record (FDR)?

A Flow Decision Record (FDR) is a short, structured artifact that captures a decision made to improve the flow of value in an organization. Like an [Architecture Decision Record](https://adr.github.io/), it emphasizes clarity, traceability, and accountability—but instead of focusing on technical architecture, it focuses on organizational dynamics, team interactions, and strategic alignment with flow.

FDRs enable decentralized decision-making by using an advice process: those closest to the work gather input from people affected by or with expertise in the decision. The result is a documented, transparent record that supports learning and coherence across teams.

## When to Create a Flow Decision Record

Use an FDR when making decisions about:

- Team boundary changes
- Service ownership shifts
- Coordination mechanism changes
- New platform capabilities or abstractions
- Redesigning team-to-team interactions
- Replacing or removing internal dependencies

## Core Structure of a Flow Decision Record

You want this to be scannable, lightweight, and repeatable. Here's a proposed structure:

**Id:** FDR-###

**Title:** Short, descriptive summary of the decision

**Date:** YYYY-MM-DD

**Status:** Proposed \| Approved \| Implemented \| Evaluated

**Context:** What prompted this decision? What struggle, signal, or user need triggered it? (See [Flow Decision Triggers](/docs/flow-decision-triggers))

**Decision:** What decision is being made? What boundaries, responsibilities, or interactions will change? (See [Flow Decision Approaches](/docs/flow-decision-approaches))

**Advice Gathered:** Who was consulted and what input was considered?

**Expected Impact:** What flow outcome is this intended to improve? (See [Flow Decision Outcomes](/docs/flow-decision-outcomes))

**Dependencies & Risks:** Are there path dependencies or potential blockers?

**Placement on Flow Roadmap:** Now \| Next \| Later - Why this timing?

**Evaluation Plan:** When and how will we revisit this decision? (See [Flow Decision Metrics](/docs/flow-decision-metrics))

**Notes & Attachments:** Link to Miro board, Linked to User Needs Map

## Using FDRs on a Flow Roadmap

You can use a Now / Next / Later roadmap to visualize prioritized FDRs based on:

- Expected impact (on flow, team clarity, user alignment)
- Feasibility (cost, time, risk, resistance)
- Dependencies (what needs to happen first)

Once implemented, each FDR enters an Evaluation Loop where teams assess:

- Did it have the intended impact?
- What new signals or needs emerged?
-Should we evolve this decision or reverse it?

## Flow Decision Record Template

The following templates are available to help you create FDRs:

- [Basic Template](/docs/templates/FDR-template)
- [Team and Boundary Template](/docs/templates/FDR-template-team-and-boundary)
- [Interaction Modes Template](/docs/templates/FDR-template-interaction-modes)
- [Constraints and Compliance Template](/docs/templates/FDR-template-constraints-and-compliance)
- [Communication and Coordination Template](/docs/templates/FDR-template-communication-and-coordination)

---

Now that you know what a Flow Decision Record is, you can learn how to [Trigger a Flow Decision Record](/docs/flow-decision-triggers).

[⬅ Back to Home](/docs/overview)
