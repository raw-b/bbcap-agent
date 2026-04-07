<?xml version="1.0" encoding="UTF-8"?>
<prompt_template version="1.0.0">
	<template_name>Core Melody Extraction Prompt (CMEP)</template_name>
	<version>1.0.0 - Initial Template: Staged transcript-to-argument workflow</version>
	<target_project>Belief-Building Core Argument Pro (BBCAP)</target_project>
	<trigger>Post-discovery interview. LUCID Sprint calls complete. Ready for Core Melody Argument development, Version 1.</trigger>

	<changelog>
		<version_1_0_0>
	  		<description>Initial production template for extracting Core Melody Argument from LUCID Sprint discovery transcripts.</description>
			<includes>
			- Four-stage workflow: Transcript Mining, Syllogism Development, Core Melody Versions (bullet/short prose/one-pager), Belief Map and Content Starter CSVs
			- Staged checkpoints requiring consultant approval before advancing
			- Hype-data spectrum diagnosis integrated into Stage 1
			- Steelmanning directive for alternatives identified in transcript
			- Writing quality system enforcement on all outputs
			- CSV output for Belief Transformation Map and Marketing Content Starter List
			</includes>
		  	<source>Built from BBCAP v3.4.0 custom instructions and Singing Hills LUCID Sprint transcripts (pts 2-3) as reference material</source>
		</version_1_0_0>
	</changelog>

	<initialization_protocol>
    Before beginning Stage 1, confirm you have the following required inputs. If any are missing, ask for them before proceeding. Do not assume or fill in placeholders.

	    <required_inputs>
			<input name="client_name">The client's business or organization name. Appears as [CLIENT NAME] in the context block.</input>
			<input name="transcript">One or more LUCID Sprint discovery call transcripts, attached as files. If no transcript is attached or pasted, ask for it. Confirm the number of parts received matches what the consultant expects.</input>
	    </required_inputs>

	    <optional_inputs>
			<input name="prior_context">Any previously developed assets for this client (e.g., Customer Transformation Profile, prior LUCID Sprint notes, existing marketing materials). Not required, but improves output if available. Ask whether any exist.</input>
			<input name="priority_notes">Specific areas the consultant wants emphasized, deprioritized, or handled carefully (e.g., "they're sensitive about the competitor comparison" or "lean into the hospitality angle"). Not required. Ask if there's anything to flag.</input>
	    </optional_inputs>

	    <initialization_behavior>
	      When this template is triggered, respond with a brief checklist confirming what you have and requesting what you still need. Keep it tight. Example:

	      "Ready to run the Core Melody Extraction. Here's what I have and what I need:
	      - Client name: [confirm or ask]
	      - Transcript(s): [confirm count or ask for upload]
	      - Prior assets for this client: [ask if any exist]
	      - Anything to flag before I start mining: [ask]"

	      Once all required inputs are confirmed, proceed directly to Stage 1. Do not re-explain the methodology or the staged workflow. Just start mining.
	    </initialization_behavior>
	</initialization_protocol>

	<context>
		<client_name>[CLIENT NAME]</client_name>
		<engagement_stage>Post-discovery interview. LUCID Sprint calls complete. Ready for Core Melody Argument development, Version 1.</engagement_stage>
		<transcript_source>Attached: LUCID Sprint discovery call transcript(s) with [CLIENT NAME] ([NUMBER] parts).</transcript_source>
	</context>
	<task type="staged">
	Read the attached transcript(s) in full before doing anything else. This is the raw source material for everything that follows.
		<stage_1 name="transcript_mining">
		Mine the transcript for the following, organized by category. Present your findings as a structured inventory so I can validate before you build on them.

		Status quo language: Direct quotes and paraphrases capturing what the client's prospects currently experience, feel, struggle with, or tolerate. Flag language that reveals unspoken frustrations or assumptions.
		Failed or inferior alternatives: Every competing approach, workaround, or default behavior the client named or implied. Note whether each is a philosophy/worldview-level alternative (Note 2 territory) or a product-level competitor (Note 4 territory). Steelman each one briefly.
		Unique approach signals: Anything the client said about why they do things differently, what shaped their perspective, or how their method diverges from the alternatives. Look for background transfer, unique exposure, and frustration-innovation patterns per the LB3 excavation methodology.
		Proof points already in hand: Stories, data, testimonials, outcomes, or third-party validation mentioned in the transcript. Categorize each as Reasoning, Story, or Trust.
		Transformation language: How the client describes what changes for their customers after working with them. Concrete behavioral shifts, emotional shifts, identity shifts.
		Tensions and open questions: Anything unresolved, contradictory, or underdeveloped in the transcript that would need clarification before the argument can be finalized. Be specific about what's missing and why it matters.

		Hold here. Present the inventory. Wait for my review before proceeding.
		</stage_1>
		<stage_2 name="syllogism_development">
		After I confirm Stage 1, draft 2-3 candidate syllogisms (major premise, minor premise, conclusion) for this client.
		For each candidate:

		State the syllogism in plain language
		Note which transcript evidence supports each premise
		Run the validation tests: logical validity, premise defensibility, transformation architecture (does it trace the arc from Note 1 status quo to Note 5 transformation?), and differentiation strength
		Identify any nested arguments within premises that would require their own proof
		Flag which candidate you'd recommend and why

		Hold here. Present the candidates. Wait for my selection before proceeding.
		</stage_2>
		<stage_3 name="core_melody_versions">
		After I select a syllogism, develop the Core Melody Argument in three versions:

		Bullet version: The 5-Note Melody as five concise claims (Note 1 through Note 5), each one sentence, using the client's language where possible.
		Short prose version: A 150-250 word narrative that walks a prospect through the belief progression from "We Get You" through "We Know What You Want." Written in second person, addressed to the prospect. No headers or labels, just the argument flowing naturally.
		One-pager version: A structured document with each Note as a labeled section, each containing the claim, 2-3 supporting points drawn from the transcript evidence, and the primary proof type (Reasoning, Story, or Trust) identified for each point.

		Apply the full writing quality system. Use the client's branded terminology, not methodology terms. Crown every fact with its argument.
		Hold here. Present all three versions. Wait for my feedback before proceeding.
		</stage_3>
		<stage_4 name="belief_map_and_content_starter">
		After I approve the Core Melody versions, produce two CSV files:

		1. **Belief Transformation Map (CSV)**: Columns: Note (1-5), Claim, Belief Shift, Premise It Proves, Primary Objections/Subclaims, Proof Available (from transcript), Proof Gaps (needs development), Proof Type (Reasoning/Story/Trust).

		2. **Marketing Content Starter List (CSV)**: Columns: Note (1-5), Content Idea, Source (transcript reference or proof point), Deployment Pattern (Story-Principle-Application / Single Objection / Named Concept / Progressive Series / Soft CTA), Recommended Format, Priority (H/M/L).

		Output each as a clean CSV code block I can copy and import into Google Sheets. No merged cells, no special formatting. Plain comma-delimited with headers in row 1.
		</stage_4>
	</task>

	<output_requirements>
	All client-facing language uses the 5-Note Melody framework (Note 1-5), Core Melody, Blueprint, and Reasoning/Story/Trust terminology. Never use Lightbulb, LB, Logos, Pathos, Ethos, or Constellation in deliverables.
	Run every output through the writing quality system before presenting. Zero em-dashes, zero disallowed words, zero AI-template structures.
	Diagnose where the client currently falls on the hype-data spectrum based on what the transcript reveals about their existing marketing. Include this as a one-line note in Stage 1.
	If the transcript contains insufficient material for any stage, flag exactly what's missing and what follow-up questions I should ask the client. Do not fill gaps with generic content.
	</output_requirements>
</prompt_template>
