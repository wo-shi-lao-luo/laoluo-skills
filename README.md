# Laoluo Skills

A selected collection of Skills for exploring ideas and planning presentations. Each folder under `skills/` contains its instructions and any supporting resources needed for distribution.

## Included Skills

| Skill | Purpose | Package notes |
|---|---|---|
| [brainstorming](skills/brainstorming/SKILL.md) | Explore alternatives, test assumptions, compare directions, and develop proposals with critical reflection. | Version 2.0.1. Self-contained; no companion service or other Skill is required. |
| [presentation-outline-designer](skills/presentation-outline-designer/SKILL.md) | Plan a speaker-led presentation with slide objectives, audience-visible content, visual direction, speaker additions, timing, and asset needs. | Produces an outline rather than a rendered deck. |

## Use a Skill

Copy the complete folder for the Skill you want into your assistant's supported Skill installation directory. Preserve `SKILL.md` and its supporting `agents/` and `references/` folders. If a same-name installation exists, compare it first rather than overwriting it blindly.

Example requests for a host that supports `$skill-name` invocation:

```text
Use $brainstorming to compare ways to improve our training-material workflow.

Use $presentation-outline-designer to plan a 30-minute internal workshop.
```

The English instructions do not require English output. Brainstorming explicitly follows the user's language.

The presentation outline's final production handoff names the separate `presentations:Presentations` Skill. That production capability is not included in this repository; creating an outline does not require rendering a deck.

## Repository Layout

- `skills/`: distributable Skill packages, not configuration automatically applied to maintain this repository.
- [FOLDER_STRUCTURE.md](FOLDER_STRUCTURE.md): folder purposes and placement conventions.

This collection uses `skills/` as its distribution source. Installing or activating a package in a particular project is a separate step governed by that host's discovery conventions.

## Sources and Design

Brainstorming's [Sources and Design Notes](skills/brainstorming/references/sources-and-design.md) record the rewrite's relationship to the earlier local version, the public Skills consulted, and the choices made for this version. Those references document influences and are not runtime dependencies.
