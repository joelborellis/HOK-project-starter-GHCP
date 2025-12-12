# 🧑‍💻 3-Day Customer Code-with Workshop using GitHub SpecKit

This agenda outline is intended for SE roles—pre-sales “code-with” engagements where the objective is to prove out a technical solution by doing hands-on keyboard work with the customer.

> **Note**
> This outline is for a code-with project that will tackle building a solution with three (3) cascading specifications—this keeps the engagement time bound. Because we are using GitHub SpecKit, the customer can continue to develop specification 3, 4, 5, … etc. SpecKit creates the scaffolding for continuing to move the project forward.

## 🧰 How to use this repo

This repository is a **starter kit for running a 3-day “code-with” engagement** using SpecKit. It’s designed to be forked then install the  latest version of SpecKit into the forked repo.

### What you get

- An outline for a **3-day agenda** focused on a hands on keyboard experience with a customer building a solution with three (3) specifications using SpecKit.
- A **day-by-day agenda** with session examples:
  - [Day 1](./Day-1.md)
  - [Day 2](./Day-2.md)
  - [Day 3](./Day-3.md)
- Placeholders for **session materials (PowerPoints)** and sample outputs (see the TODOs in the day files).

### How to start (two common paths)

1. **Starting a brand-new coding project**
  - Fork this repo as the engagement workspace.
  - Install the latest version of SpecKit into the fork.
  - Use SpecKit to drive the constitution/specifications/plans/tasks, and build the solution from the generated scaffolding.

2. **Starting from an existing accelerator / reference implementation**
  - Fork the accelerator repo.
  - Install SpecKit into that fork.
  - Use *this* repo as the agenda + session-materials companion (or copy the day files/slides into the accelerator fork).

Which path you choose depends on whether you’re **starting from scratch** or **starting from an existing codebase**—either way, the goal is the same: keep the workshop time-boxed, ship working code quickly, and leave the customer with a GitHub repo they can continue to expand with new specifications.

## 🧾 What is SpecKit?

SpecKit is a **Specification-Driven Development (SDD)** approach that inverts traditional development:

- Instead of writing code first and *hoping* it matches requirements,
- you write **executable specifications** that drive (and can generate) the implementation.

In this model, the **specification is the source of truth**—the code is its expression.

### The “power inversion”

For decades, specifications served code. SpecKit flips that relationship:

- **Code serves specifications**.
- When the spec changes, the implementation is updated systematically.
- The gap between *intent* and *implementation* shrinks to a repeatable transformation.

### Why it works well for Solution Engineers

- **Speed**: turn vague ideas into working prototypes in days, not weeks.
- **Customer confidence**: work in business language; keep artifacts readable by stakeholders.
- **Rapid pivots**: update the spec and regenerate/update the plan—less manual rewrite churn.
- **Quality by design**: start with “constitutional” principles to prevent scope creep.
- **Reusable assets**: specs become portfolio artifacts you can adapt for future engagements.

### Core loop (workshop-friendly)

```text
Constitution -> Specify -> Clarify -> Plan -> Tasks -> Implement
```

In practice, this means you’re rarely “heads down coding” for long stretches—you’re continuously validating requirements with the customer while using an agent-assisted workflow to translate those requirements into a working demonstration.

### 🔗 Official resources

- SpecKit (GitHub repo): https://github.com/github/spec-kit
- SpecKit (website): https://speckit.org/

**Shout-out**: huge thanks to **Den Delimarsky** and **John Lam** (GitHub/Microsoft) for their work on SpecKit and the broader Spec-Driven Development workflow.

## 🚀 Why use SpecKit with hands-on keyboard engagements?

SpecKit is a great fit for “code-with” engagements because it helps the **SE team and the customer’s developers** work from the same source of truth (the spec) and move quickly from a business problem to a working technical proof.

### Key benefits

- **Prove a technical solution quickly (together)**

  - Our SE teams pair with the customer’s developers to turn the agreed business problem into an executable plan.
  - The result is a working implementation sooner, with fewer “handoff gaps” between requirements and code.

- **Create an expandable GitHub repo the customer keeps**

  - The engagement produces a GitHub repository with clear artifacts (constitution, specs, plans, and tasks).
  - After the workshop, the customer can add *new specifications* as priorities evolve (spec 3, 4, 5, …) without starting over.
  - This repo becomes a durable foundation for moving from prototype to a **production solution faster**.

- **Leverage agentic coding with GitHub Copilot Agents**

  - The team uses GitHub Copilot Agents to accelerate the “mechanical” work of implementation (scaffolding, iteration, refactors, and validation).
  - SEs and customer developers stay focused on correctness, architecture, and outcomes—while agents help drive execution.

- **Traceability and alignment throughout**

  - Decisions and changes remain anchored to written specifications.
  - Stakeholders can review intent (specs) and progress (plans/tasks) in a format that’s easy to follow.

> **🧪 Example repo (fictitious workshop specs)**
> 
> For an example of what the 3-day workshop can produce, see:
> https://github.com/joelborellis/mcp-project-speckit
> 
> This repo is an example of testing out the 3-day workshop approach using a *fictitious* set of specifications. It contains a fully operational **MCP server registration portal** integrated with **Microsoft Entra ID** for authentication and authorization, with:
> 
> - a **React** frontend,
> - a **FastAPI** backend,
> - and persistence to **PostgreSQL in Azure**.

## 🗓️ Agenda by day

- [Day 1: Establish principles and define customer specifications](./Day-1.md)
- [Day 2: Code the first and second specification](./Day-2.md)
- [Day 3: Code the final specification and test the full solution](./Day-3.md)



