# Belief-Building Core Argument Pro (BBCAP)

BBCAP is an AI-powered strategy assistant for brand strategists who need to build defensible, evidence-backed core arguments for client marketing.

The system is designed around Billy Broas' argument-first methodology, translated into client-facing language and structured for repeatable execution.

## What This Tool Does

- Guides strategists through the real BBCAP phased workflow used in production examples.
- Converts discovery insights into an approval-ready Core Melody before full expansion.
- Builds a complete Core Message Blueprint with claims, subclaims, and proof architecture.
- Surfaces argument gaps and proof collection priorities.
- Enforces client-facing terminology and writing quality standards.

## Canonical Workflow

The project now follows this 3-phase flow:

1. **Phase 1: Interview Question Generation**
   - Generate discovery questions based on client background and positioning context.
2. **Phase 2: Transcript -> Core Melody (Bullet Draft)**
   - Read interview transcript and produce a concise bullet version for client approval.
3. **Phase 3: Approved Bullet Draft -> Full Blueprint**
   - Expand into a comprehensive Core Message Blueprint with claims and subclaims.

Important gate:

- Do not move to the full Blueprint until the bullet Core Melody is explicitly approved.

## Core Outcomes

- A validated underlying syllogism (major premise, minor premise, conclusion).
- A client-facing 5-Note Melody argument with clear belief progression.
- A Core Message Blueprint with subclaims and proof points.
- Proof typing by Reasoning, Story, and Trust.
- Gap analysis, development priorities, and implementation direction.

## Project Structure

```text
bbcap-agent/
  README.md
  prompts/
    bbcap-main-prompt.md
  examples/
    ...real BBCAP sample deliverables
```

## How To Use

1. Load `prompts/bbcap-main-prompt.md` as your primary instruction prompt.
2. For new-client core argument development, follow `bbcap-standard-workflow-template.md` and the `## Standard Workflow` section in `prompts/bbcap-main-prompt.md`.
3. Save staged outputs in the client's deliverables folder as:
   - `stage-1-transcript-mining.md`
   - `stage-2-syllogism-candidates.md`
   - `stage-3-core-melody-versions.md`
   - `stage-4-belief-map-content-starter.md`
4. Pick the current project stage:
   - Phase 1 question generation,
   - Phase 2 bullet draft from transcript,
   - or Phase 3 full Blueprint from approved draft.
5. Keep deliverables in client-facing language:
   - 5-Note Melody,
   - Core Melody,
   - Core Message Blueprint,
   - Reasoning / Story / Trust.

## Notes

- The prompt was updated using patterns observed in `examples/` deliverables.
- The examples show iterative revision behavior, proof gap tracking, and approval gating.
- Next implementation step is to add execution scaffolding (CLI/API, schemas, validators, and template automation).
