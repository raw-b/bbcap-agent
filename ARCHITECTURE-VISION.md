# Multi-Agent Architecture Vision

This document describes how a **Strategic COO** (chief agent) orchestrates specialized sub-agents. It is a planning artifact, not an implementation spec.

## North Star

The chief agent acts as your **Strategic COO**: it understands intent, chooses the right specialist, sequences work when multiple agents are involved, and keeps client context coherent. Sub-agents are deep experts with narrow remits. They do not replace judgment; they accelerate execution and preserve methodology.

## Agent Roster

| Agent | Role | Status |
| :--- | :--- | :--- |
| **Strategic COO** | Orchestration, routing, sequencing, synthesis | Chief (not a separate “product” yet) |
| **BBCAP** | Belief-building core arguments, 5-Note Melody, Core Message Blueprint | Built (this repo) |
| **LUCID Pro** | Strategy sprint reports, decisions, and structured strategic outputs | Planned |
| **Headliner Pro** | Belief-building headlines aligned to core argument | Planned |
| **COO per client** | Per-client engagement: status, next steps, deliverables, comms rhythm | Planned |
| **Prompt Enhancer** | Prompt optimization and instruction hardening for other agents | Planned |

## Relationship Map

```
                    ┌─────────────────────────┐
                    │    Strategic COO      │
                    │  (intent → routing)   │
                    └───────────┬───────────┘
                                │
        ┌───────────────────────┼───────────────────────┐
        │                       │                       │
        ▼                       ▼                       ▼
┌───────────────┐       ┌───────────────┐       ┌───────────────┐
│ COO per       │       │ LUCID Pro     │       │ Prompt        │
│ client        │       │               │       │ Enhancer      │
│ (context +    │       │ (sprints +    │       │ (meta:        │
│  engagement)  │       │  decisions)   │       │  improve      │
└───────┬───────┘       └───────┬───────┘       │  instructions)│
        │                       │               └───────┬───────┘
        │                       │                       │
        │                       ▼                       │
        │               ┌───────────────┐              │
        │               │ BBCAP         │◄─────────────┘
        │               │ (core         │   (optional pass:
        │               │  argument)  │    sharpen prompts
        └──────────────►└───────┬───────┘    before heavy work)
                                │
                                ▼
                        ┌───────────────┐
                        │ Headliner Pro │
                        │ (headlines    │
                        │  from belief  │
                        │  architecture)│
                        └───────────────┘
```

**Dependency logic (conceptual):**

- **COO per client** holds *who, when, and what’s open* for each engagement. It should be the COO’s first stop when work is client-scoped.
- **LUCID Pro** produces *strategic decisions and sprint artifacts* that often *feed* BBCAP (what we believe, what we’re proving, what we decided).
- **BBCAP** turns strategy and discovery into *argument architecture* (Core Melody → Blueprint). It is the belief engine for the stack.
- **Headliner Pro** sits *downstream of BBCAP*: headlines express beliefs already structured; it should not invent the core argument in isolation.
- **Prompt Enhancer** is *cross-cutting*: it improves prompts *for* COO, LUCID, BBCAP, Headliner, and client-COO instructions. It is not a dependency for “truth” of the work, but it raises quality of every call.

## Recommended Build Order

Order reflects **dependencies**, **reuse of your IP**, and **orchestration value**—not difficulty alone.

| Priority | Agent | Rationale |
| :---: | :--- | :--- |
| 1 | **BBCAP** | Core belief and messaging IP. Already shipped. Everything else either feeds it or expresses it. |
| 2 | **COO per client** | Without per-client memory and engagement rhythm, the chief agent has nowhere to attach tasks. This is the operational spine for “which client, which phase, what’s due.” |
| 3 | **LUCID Pro** | Strategy sprints and decisions are upstream of argument refinement and headline work. Feeds BBCAP with structured inputs. |
| 4 | **Headliner Pro** | Explicitly downstream of BBCAP: same belief system, different surface (headlines). Build after argument path is solid. |
| 5 | **Prompt Enhancer** | Meta-layer: improves how every other agent is invoked. Highest leverage once multiple agents exist; less critical when only one specialist is live. |

**Alternative:** If you want **faster headline experiments** before full LUCID, you could swap 3 and 4 *only if* Headliner Pro is strictly constrained to “express existing BBCAP outputs” and does not imply new strategic decisions. The dependency diagram still prefers LUCID → BBCAP → Headliner for coherence.

## How the Strategic COO Routes Tasks

Use these **routing rules** as the mental model for orchestration (implementation can follow later).

### 1. Classify the ask

- **Client ops** (status, deadlines, what we owe, meeting prep) → **COO per client**
- **Strategy / sprint / decision** (priorities, tradeoffs, sprint report) → **LUCID Pro**
- **Core argument, melody, blueprint, proof architecture** → **BBCAP**
- **Headlines, hooks, subject lines** (belief-aligned, not generic copy) → **Headliner Pro**
- **Improve a prompt, instruction set, or agent brief** → **Prompt Enhancer**

### 2. Multi-step chains (typical)

| User intent | Sequence |
| :--- | :--- |
| “Prep this week for Client A” | COO per client → (optional) BBCAP if argument work is open → Headliner if assets due |
| “Turn sprint outcomes into messaging” | LUCID Pro → BBCAP (draft or update Core Melody) → Headliner Pro |
| “New client: discovery through launch” | COO per client (setup) → LUCID (positioning/sprint) → BBCAP → Headliner |
| “This agent feels fuzzy” | Prompt Enhancer on that agent’s instructions → rerun specialist |

### 3. What the COO always owns

- Which client and which phase of work.
- Whether outputs must stay consistent across agents (terminology, file names, approval gates like BBCAP’s bullet draft before full Blueprint).
- Final synthesis when multiple agents return partial work.

### 4. What sub-agents never own alone

- Cross-client prioritization without COO per client context.
- Contradicting strategic decisions already captured in LUCID without an explicit “revise decision” step.
- Headlines that imply a new core belief not yet reflected in BBCAP.

## Design Principles (for when you implement)

- **Single source of belief:** BBCAP (and inputs from LUCID) owns the argument; Headliner expresses it.
- **Client truth lives in one place:** COO per client is the engagement system of record for “what’s true about this relationship right now.”
- **Prompt Enhancer is a service, not a decider:** it sharpens instructions; it does not override methodology or client facts.
- **Chief agent is thin, specialists are thick:** COO routes and stitches; sub-agents carry the deep prompts and quality bars.

## Open Questions (to resolve as you build)

- How much state does COO per client persist (files, DB, CRM) vs. re-derive each session?
- Does LUCID output a formal handoff artifact (e.g., “decision log”) that BBCAP must ingest verbatim?
- Should Headliner Pro receive only approved BBCAP bullets, or also raw transcript snippets?

---

*Version: planning draft. Update as agents ship and real handoff patterns emerge.*
