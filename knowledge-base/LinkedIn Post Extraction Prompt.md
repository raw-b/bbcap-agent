# LinkedIn Post Extraction Prompt

<task>generate_linkedin_post
<linkedin_prompt_cue>
Run the following prompt when I ask you to "generate the LinkedIn post" (or similar).
<linkedin_prompt_cue>
</task>

<source_material>
Win #2 from the current issue is the only source. Read it completely before writing anything.
</source_material>

<extraction_step>
Identify the single most compelling insight, argument, or reframe in Win #2 — the one idea that would make a solopreneur stop scrolling and reconsider something they thought they already knew. Name it before you write. This is your anchor. Everything else in the post serves it.
</extraction_step>

<writing_rules>
Write a standalone LinkedIn post (150–300 words) built around that one idea.

STRUCTURE:
- Open with the insight itself: a provocative statement, a surprising reframe, or a strong claim pulled directly from Win #2. No preamble. No "In this week's newsletter..." opening. Ever.
- Develop the idea in the body. The reader should walk away with something useful even if they never click a link. Not a teaser. Not a trailer. A complete thought.
- End with exactly ONE of the following (alternate between issues — if the last post used a question, use the soft CTA this time, and vice versa):
  - An engagement question that invites reflection or experience-sharing
  - Soft CTA: "I write about this every week in 4 Wins → [link]"

VOICE:
Direct, warm, slightly provocative, conversational. Smart friend telling you the truth at a coffee shop. Not corporate. Not motivational.

FORMATTING:
One idea per paragraph. Short paragraphs. Occasional single-line paragraphs for emphasis. White space is structural, not decorative.

DO NOT:
- Summarize the newsletter
- Use hashtags
- Use emoji as bullet points
- Write in a hype or motivational tone
- Include more than one CTA
</writing_rules>

<voice_constraints>
This post must read as human-written. Before finalizing, self-check every sentence against these hard rules:

PUNCTUATION:
- No em-dashes (use a comma, colon, or rewrite the sentence)
- No exclamation points

BANNED WORDS AND PHRASES — do not use any of the following:
authentic, transformative, game-changer, unlock, unleash, elevate, delve, harness, thrive, skyrocket, soar, savvy, evolve, superpower, superstar, magic, lightning, puzzle, integrity, buzzword, void, fluff, crickets, vanity metrics, pitch-slapped, double-edged sword, fast track, strike gold, secret weapon, arsenal, through the noise, in a world of, here's the thing, here's the kicker, forget [thing], your truth, share your truth, I used to… then I…, it's not about [x]… it's about [y], unleashed the power of, your audience will thank you for it, art/science analogy constructions, ethical (or similar moralizing statements)

BANNED PATTERNS — rewrite if you catch these:
- Metaphors or analogies that feel manufactured ("like a GPS for your brand," "think of it as a muscle")
- Any sentence that could appear in a generic AI content post
- Motivational cadence ("Do the work. Show up. Be consistent.")
- Purple prose or anything that reaches for effect instead of clarity

If a sentence triggers any of the above, rewrite it before outputting. Do not flag it. Fix it.
</voice_constraints>

<output_format>
LINKEDIN POST — Issue [#]
Anchor insight: [The specific idea from Win #2 you built around, and why it's the strongest pull — 1 sentence]

---

[Post]

---

Alternate closing: [One backup question or CTA if Robby prefers a different angle]
</output_format>