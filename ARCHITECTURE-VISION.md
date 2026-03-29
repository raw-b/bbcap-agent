# Multi-Agent Architecture Vision

This document describes how a **Strategic COO** (chief agent) orchestrates specialized sub-agents, how **CPCI** (Quality Control & Prompt Architecture) governs instruction quality across the stack, and how client delivery compounds. It is a planning artifact, not an implementation spec.

## North Star

**CPCI** sits above all agents as the meta-layer that governs instruction quality across the entire system. The **Strategic COO** (Chief Orchestrator) routes tasks to specialized sub-agents. Sub-agents are deep experts with narrow remits; they do not replace judgment but accelerate execution and preserve methodology.

## Architecture Layers

1. **CPCI + Prompt Enhancer (merged)** — Meta-tool that reviews and enhances instructions for all other agents. Cross-cutting quality and prompt architecture.
2. **Strategic COO** — Routes intent to the right specialist, sequences multi-step work, and synthesizes. Built **last** so the router reflects how each agent actually behaves (the “James” equivalent).
3. **Sub-agents** — BBCAP, LUCID Pro, Headliner Pro, COO-per-client, Call Transcript Analyzer, 4 Wins Email.

## Agent Roster

| Agent | Role | Status |
| :--- | :--- | :--- |
| **CPCI + Prompt Enhancer** | Meta-layer: instruction review, prompt hardening, quality across the system | Planned (position 5 in build order) |
| **Strategic COO** | Orchestration, routing, sequencing, synthesis | Built last (position 8) |
| **BBCAP** | Belief-building core arguments, 5-Note Melody, Core Message Blueprint | Done (this repo) |
| **LUCID Pro** | Strategy sprint delivery engine; structured outputs that feed BBCAP | Next after COO-per-client template |
| **Headliner Pro** | Belief-building headlines; downstream of BBCAP, implementation phase | Planned |
| **COO-per-client** | One **template**, cloned per engagement: status, next steps, deliverables, comms rhythm | Next build (from Fixation COO as mature base) |
| **Call Transcript Analyzer** | Intake agent; interview/call data → LUCID Pro and BBCAP | Planned |
| **4 Wins Email** | Newsletter production for audience building | Planned |

## Relationship Map

```
                    ┌─────────────────────────────────┐
                    │  CPCI + Prompt Enhancer (meta)  │
                    │  governs instruction quality    │
                    │  for ALL agents below           │
                    └────────────────┬────────────────┘
                                     │ improves instructions
     ┌───────────────────────────────┴───────────────────────────────┐
     │                  Strategic COO (Chief Orchestrator)         │
     │                  intent → routing → sequencing              │
     └───────────────────────────────┬───────────────────────────────┘
                                     │
     ┌───────────────┬───────────────┼───────────────┬───────────────┬───────────────┐
     ▼               ▼               ▼               ▼               ▼               ▼
┌──────────┐  ┌──────────────┐  ┌─────────┐  ┌─────────────┐  ┌──────────────┐  ┌────────────┐
│ COO-per- │  │ Call         │  │ LUCID   │  │ BBCAP       │  │ Headliner    │  │ 4 Wins     │
│ client   │  │ Transcript   │  │ Pro     │  │ (belief     │  │ Pro          │  │ Email      │
│ (engagement│ │ Analyzer     │  │ (sprint │  │  engine,   │  │ (headlines,  │  │ (newsletter│
│  spine)  │  │ (intake)     │  │ engine) │  │  blueprint) │  │  downstream) │  │  production)│
└────┬─────┘  └──────┬───────┘  └───┬─────┘  └──────┬──────┘  └──────────────┘  └────────────┘
     │               │              │               │
     │               └──────┬───────┴───────────────┘
     │                      │
     │            (Analyzer feeds LUCID + BBCAP)
     │                      ▼
     │               LUCID Pro ──────────────► BBCAP ──► Headliner (+ impl. copy/content)
     │
     └──── manages engagement across the full pipeline (one template per client)
```

**Dependency logic (conceptual):**

- **CPCI + Prompt Enhancer** is not a task router; it raises instruction quality for COO, every sub-agent, and client-facing briefs.
- **Strategic COO** chooses specialists and order of operations once those behaviors are known (hence build order 8).
- **COO-per-client** holds *who, when, and what’s open* per engagement and spans the whole delivery pipeline — **not** a separate product per client; **one template**, cloned and populated per engagement (see Design Principles).
- **Call Transcript Analyzer** feeds **LUCID Pro** and **BBCAP** with structured intake from calls and interviews.
- **LUCID Pro** is the strategy sprint engine; outputs feed **BBCAP** (belief and blueprint).
- **BBCAP** is the core belief engine; **Headliner Pro** and other implementation surfaces express it downstream.
- **4 Wins Email** supports Robby’s audience-building stack; orthogonal to a single client blueprint but part of the same ecosystem.

## Core Delivery Pipeline (all client engagements)

**LUCID sprint → BBCAP (Core Message Blueprint) → implementation deliverables** (Headliner Pro, website copy, content/email), with **COO-per-client** managing the engagement throughout.

**Active clients in the pipeline right now:**

| Client | Stage |
| :--- | :--- |
| **Amy Fulmer** | Post-sprint, monthly implementation partnership; blueprint done |
| **Fixation (Gavin)** | Months 5–6 of 12-month partnership; page architectures done, implementation in progress |
| **Singing Hills (Phil)** | Mid-sprint; LUCID Part 2 in progress |

## Recommended Build Order

Order reflects **active revenue**, **dependencies**, **reuse of IP**, and **orchestration readiness** — the Strategic COO is intentionally last so routing matches real agent behavior.

| Priority | Agent | Rationale |
| :---: | :--- | :--- |
| 1 | **BBCAP** | Done — belief-building core argument engine (this repo). |
| 2 | **COO-per-client template** | **One** template, cloned per engagement. Build from **Fixation COO** instructions as the most mature example. Test with **Amy Fulmer** and **Singing Hills** instances. Directly serves three active paying clients. |
| 3 | **LUCID Pro** | Strategy sprint delivery engine; Singing Hills needs this now. Feeds BBCAP. |
| 4 | **Call Transcript Analyzer** | Intake agent feeding LUCID and BBCAP with interview/call data. |
| 5 | **CPCI + Prompt Enhancer (merged)** | Meta-tool: reviews and enhances instructions for all other agents. Builds here so one investment improves four-plus agents at once. |
| 6 | **Headliner Pro** | Belief-building headlines; downstream of BBCAP; implementation phase. |
| 7 | **4 Wins Email** | Newsletter production for Robby’s own audience building. |
| 8 | **Strategic COO (Chief Orchestrator)** | Built **last** — need observed behavior from each agent before the router. The “James” equivalent. |

## Client-Facing Products (Future Revenue Layer)

### Blueprint Implementation Copilot

A **client-facing AI tool**, personalized per client and loaded with their **approved Core Message Blueprint**, **brand voice guide**, and **disallowed language filter**.

**What it does**

- Lets clients check any marketing draft against their Blueprint for alignment, missing beliefs, and off-message language.
- Generates first drafts anchored to their approved core argument and proof points.
- Flags messaging drift and suggests corrections using approved language.
- Maintains consistency without requiring Robby in the room for every marketing decision.

**Note:** This is a simplified, locked-down cousin of the BBCAP agent — preloaded with the approved Blueprint, stripped of strategy-building phases, focused purely on **implementation checking** and **content generation**.

### MRR tiers

| Tier | Price (indicative) | Includes |
| :--- | :--- | :--- |
| **Copilot Access Only** | $200–500/mo | Self-serve messaging checks and first-draft generation |
| **Copilot + Monthly Review** | $500–1,000/mo | Above plus one monthly strategy session to review flags, update proof points, refresh Blueprint |
| **Full Partnership** | $1,500–3,500/mo | Above plus active strategic advisory — Copilot becomes a tool **within** the existing retainer |

### Strategic value

Creates a **productized retention layer** for clients who complete a sprint but are not ready for a full partnership. Addresses the main **post-engagement failure mode**: clients drift from their Blueprint because they do not have Robby in the room for every decision. **Extends value without extending time.**

### Infrastructure dependencies

Requires **BBCAP** (done), **COO-per-client template**, **CPCI** for instruction quality, and at least one **client beta** — **Amy Fulmer** is the ideal candidate (post-sprint, in implementation, high trust).

### Build position

Ship **after Headliner Pro** (internal build order #6) and **before Strategic COO** (Chief Orchestrator, #8). **Do not build** until the delivery system is solid — **factory before showroom.** Sequencing relative to **4 Wins Email** (#7) can follow revenue priority; Copilot is a client retention surface, not a shortcut around a stable internal agent stack.

## What Makes This System One of One

- **Proprietary methodology** encoded as persistent AI agents.
- **Meta-layer (CPCI)** that improves the system itself, not only deliverables.
- **Client delivery that compounds** with every engagement (same templates, richer context).
- **Platform-independent IP** stored in markdown on GitHub.

## How the Strategic COO Routes Tasks

Use these **routing rules** as the mental model for orchestration (implementation follows once the COO is built).

### 1. Classify the ask

- **Client ops** (status, deadlines, what we owe, meeting prep) → **COO-per-client**
- **Calls / transcripts / interview intake** → **Call Transcript Analyzer** (then typically LUCID and/or BBCAP consumers)
- **Strategy / sprint / decision** (priorities, tradeoffs, sprint report) → **LUCID Pro**
- **Core argument, melody, blueprint, proof architecture** → **BBCAP**
- **Headlines, hooks, subject lines** (belief-aligned) → **Headliner Pro**
- **Newsletter / 4 Wins production** → **4 Wins Email**
- **Improve a prompt, instruction set, or agent brief** → **CPCI + Prompt Enhancer**

### 2. Multi-step chains (typical)

| User intent | Sequence |
| :--- | :--- |
| “Prep this week for Client A” | COO-per-client → (optional) BBCAP if argument work is open → Headliner if assets due |
| “Turn sprint outcomes into messaging” | LUCID Pro → BBCAP (draft or update Core Melody) → Headliner Pro |
| “New client: discovery through launch” | COO-per-client (setup) → Call Transcript Analyzer / LUCID → BBCAP → Headliner + implementation |
| “This agent feels fuzzy” | CPCI + Prompt Enhancer on that agent’s instructions → rerun specialist |

### 3. What the COO always owns

- Which client and which phase of work.
- Whether outputs must stay consistent across agents (terminology, file names, approval gates like BBCAP’s bullet draft before full Blueprint).
- Final synthesis when multiple agents return partial work.

### 4. What sub-agents never own alone

- Cross-client prioritization without COO-per-client context.
- Contradicting strategic decisions already captured in LUCID without an explicit “revise decision” step.
- Headlines that imply a new core belief not yet reflected in BBCAP.

## Design Principles (for when you implement)

- **COO-per-client is one template, many instances:** client COO “projects” are not separate builds — same architecture, different context, cloned per engagement.
- **Single source of belief:** BBCAP (with LUCID and intake from the Call Transcript Analyzer) owns the argument; Headliner expresses it.
- **Client truth for ops:** COO-per-client is the engagement system of record for what’s true about the relationship *right now* (tasks, rhythm, deliverables).
- **CPCI is meta-quality, not a decider:** it sharpens instructions; it does not override methodology or client facts.
- **Chief agent is thin, specialists are thick:** COO routes and stitches; sub-agents carry the deep prompts and quality bars.

## Open Questions (to resolve as you build)

- How much state does COO-per-client persist (files, DB, CRM) vs. re-derive each session?
- Does LUCID output a formal handoff artifact (e.g., decision log) that BBCAP must ingest verbatim?
- What is the canonical schema from Call Transcript Analyzer into LUCID vs. BBCAP?
- Should Headliner Pro receive only approved BBCAP bullets, or also raw transcript snippets?

---

*Version: planning draft. Update as agents ship and real handoff patterns emerge.*
