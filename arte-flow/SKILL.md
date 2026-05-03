---
name: arte-flow
description: Guides art prompt intake with two choice modes (AI decides or user picks from catalog), asks follow-up text placement and placeholder questions, and outputs a final prompt reply in chat. Use when users want collage/art prompt generation with style, composition, character pose, and vibe selection.
disable-model-invocation: true
---

# Art Prompt Flow

## Purpose
Run a fixed intake flow, then return one final prompt in chat.

## Intake Mode
Start by asking the user to choose one mode:

1. **Let AI decide**
2. **Pick from catalog list**

If the user picks **Pick from catalog list**, show choices grouped by:
- `artstyles`: visual style direction
- `collage`: element layering and collage approach
- `composition`: layout structure and focal arrangement
- `character-poses`: body pose and camera framing direction for character/object focus
- `vibes`: mood and emotional tone

For each option shown, include one brief sentence description.
Use [catalog.md](catalog.md) as the default option source.
Present numeric ranges and let users respond with numbers:
- `artstyles`: 1-15
- `collage`: 1-8
- `composition`: 1-12
- `character-poses`: 1-25
- `vibes`: 1-30

Catalog entries must stay grounded in reference content:
- `references/artstyle-references.md`
- `references/composition-layout.md`
- `references/character-poses.md`
- `references/vibes.md`

If the user picks **Let AI decide**, ask a short series of questions to infer direction, such as:
- subject/theme
- mood target
- color preference
- complexity level
- any must-include visual motifs

Then decide `artstyles`, `collage`, `composition`, and `vibes` based on their answers.
For character/object-focused prompts, also decide a matching `character-poses` option.

## Required Follow-Up Questions
After either mode (catalog or AI-decide), ask these in order:

1. Ask whether the output is character/object-focused and whether they want a specific pose from `character-poses` (or AI to choose one).
2. Ask whether the user wants certain words written in the collage or placed in specific locations.
3. Ask whether the user already has placeholders.
4. If user says they have placeholders, include square-bracket placeholders `[]` in the `Text in collage` line.
5. If placeholders are not provided but user says they have them, ask one short follow-up for placeholder positions/content.

## Output Rules
- Output must be a single chat reply.
- Output must be in **prompt form** (ready to use for generation).
- Include the selected/decided `artstyles`, `collage`, `composition`, `character-poses` (when relevant), and `vibes`.
- Include text placement instructions if provided.
- If placeholders exist, include `[]` inside the `Text in collage` line.
- Keep wording concise and production-ready.
- If user selected by number, resolve numbers to label names before final prompt output.

## Suggested Prompt Template
Use this shape for the final answer:

```text
Create a collage artwork with:
- Artstyle: <chosen artstyle>
- Collage approach: <chosen collage approach>
- Composition: <chosen composition>
- Character pose: <chosen pose or "none">
- Vibe: <chosen vibe>
- Subject/theme: <user or inferred theme>
- Text in collage: <text words and placement, or "none">

Additional direction:
<color, motif, detail constraints>
```

For complete final-output examples, use [template-output/template-output.md](template-output/template-output.md).

## Interaction Constraints
- Do not skip required follow-up questions.
- If user input is unclear, ask one concise clarification before finalizing.
- Do not output analysis; output only the final prompt when intake is complete.
- Match the final output style to examples in [template-output/template-output.md](template-output/template-output.md).
