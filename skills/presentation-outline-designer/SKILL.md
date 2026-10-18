---
name: presentation-outline-designer
description: Design concise, speaker-led PowerPoint outlines for professional presentations, training sessions, workshops, client briefings, internal sharing, and talks. Use when Codex needs to plan a PPT before production and specify, slide by slide, the communication goal, audience-visible content, visual layout, speaker additions, timing, and asset needs.
---

# Presentation Outline Designer

Create an executable slide plan before creating a PPT. The deck must support the speaker instead of becoming a script for the speaker to read.

## Inputs

Identify the topic, audience, duration, desired outcome, source materials, delivery format, and brand/template constraints. Infer low-risk details from context. Ask only when a missing decision would materially change the deck.

For a skill, agent, or workflow topic, distinguish clearly between what a person sees on a slide, what the speaker explains, and what is implementation detail.

## Narrative design

1. State the audience outcome in one sentence: after the talk, they can **do** something concrete.
2. Build a simple arc: context/problem -> core idea -> applied examples -> reusable method -> next action.
3. Allocate time before choosing slide count. For a 45-minute training or talk, target 12-15 content slides, including 2-3 application or discussion moments.
4. Give each slide one message. Use an action title that states the takeaway rather than a generic topic label.
5. Use the audience's real work and existing materials for examples. Do not use generic lifestyle examples when a business scenario is available.

## Speaker-led visual rules

- Keep visible copy sparse: one headline, one central visual or exhibit, and at most three short supporting points.
- Do not paste the speaker's explanation onto the slide. Put context, caveats, transitions, and examples in **speaker additions**.
- Prefer a before/after comparison, annotated sample, process path, or simple table when it makes the point clearer than bullets.
- Do not use decorative images that carry no explanatory role.
- Vary adjacent layouts. Avoid repeated card grids and dashboard-like pages.
- Use large type, generous whitespace, and an obvious visual hierarchy. Reduce copy before reducing type size.
- Treat statistics, current claims, and external imagery as source-backed content; flag any that require verification.

## Required output

Start with a concise deck brief containing title, audience outcome, duration, visual direction, and the story in three to five beats.

Then provide a slide-by-slide table with these columns:

| # | Action title | This slide must achieve | Audience sees | Layout and visual design | Speaker additions | Time | Assets / verification |
|---|---|---|---|---|---|---|---|

Write `Audience sees` as finished, audience-facing copy or a precise visual description. Write `Layout and visual design` spatially: what goes left, right, center, background, and what should be visually dominant. Write `Speaker additions` as brief talk-track prompts, not a full script.

After the table, include:

1. **Interaction plan**: exercise or discussion instructions, expected output, and facilitation time.
2. **Materials to collect**: only missing examples, screenshots, data, logos, or brand assets needed before production.
3. **Build handoff**: slide types that require diagrams, screenshots, charts, or generated imagery.

## Quality gate

Before returning the outline, verify that:

- the timed sections fit the requested duration with a small buffer;
- every slide advances the narrative or supports an exercise;
- the visible content is understandable without duplicating the spoken content;
- practical examples use the audience's context;
- each exercise tests a skill the audience can reuse;
- there is a clear final action, not merely a closing thank-you slide.

When the user asks to build the actual deck, use the `presentations:Presentations` skill after this outline is approved.
