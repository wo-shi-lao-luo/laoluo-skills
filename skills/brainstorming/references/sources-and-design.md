# Sources and Design Notes

Review date: 2026-10-17. This file records material consulted for the rewrite, method-level influences, and deliberate changes to workflow boundaries. It is not required reading for ordinary tasks.

## Relationship to the Previous Version

Several passages in the previous local installation matched [obra/superpowers at historical revision b36e082](https://github.com/obra/superpowers/blob/b36e082/skills/brainstorming/SKILL.md), including task routing, approvals, the flow diagram, and planning conventions. That folder also contained the project's visual companion code. This review cannot reconstruct the previous version's full creation history or attribute every contribution.

Version 2.0.0 rewrites the entry point around a new organization of work. It retains the local version's requirement for critical reflection while re-expressing and integrating it. The distribution contains none of the old scripts, page templates, reviewer prompts, or visual companion documentation, and no longer uses the prescribed document directory or named planning Skill.

Version 2.0.1 restores an explicit proposal self-check and checks plausible failure at standard reflection depth. It also retains reasons for setting important alternatives aside and specifies how validation results update decisions. These additions preserve the standalone workflow and existing authorization boundaries.

A rewrite and removal of runtime dependencies do not erase influences. This version does not claim that its maintainer originated brainstorming, routing, assumption testing, or reflection methods, or that textual comparison alone can establish authorship.

## Public Skills Consulted

The links below identify material actually reviewed. Except for the pinned revision above, main branches can change. The comparisons describe the content retrieved on the review date, not future versions of those projects.

| Material | Useful influence | Choice made in this version |
|---|---|---|
| [Anthropic: product-brainstorming](https://github.com/anthropics/knowledge-work-plugins/blob/main/product-management/skills/product-brainstorming/SKILL.md) | Distinguish problem exploration, ideation, and assumption testing; identify inexpensive checks for critical unknowns | Support multiple domains without fixed idea counts or a mandatory framework checklist |
| [nicknisi/ideation: brainstorm](https://github.com/nicknisi/ideation/blob/main/skills/brainstorm/SKILL.md) | Separate the decision about whether to build from implementation; give the current stage a clear stopping point | Avoid a plugin-internal engine, tool whitelist, or prescribed next command; honor existing user authorization |
| [ui-iids/claude-skills: brainstorm](https://github.com/ui-iids/claude-skills/blob/main/skills/brainstorm/SKILL.md) | Separate divergence from evaluation; vary mechanisms and switch perspectives when stuck | Do not persist divergence across the entire chat or require absurd ideas; converge directly when the original request calls for a recommendation |
| [phuryn/pm-skills: brainstorm](https://github.com/phuryn/pm-skills/blob/main/pm-product-discovery/commands/brainstorm.md) | Distinguish proposing ideas from designing validation; consider different participants' needs | Do not require fixed role turns or companion Skills; examine only perspectives relevant to the goal |
| [obra/superpowers: historical brainstorming version](https://github.com/obra/superpowers/blob/b36e082/skills/brainstorming/SKILL.md) | Scale discussion to scope and make proposals sufficient for handoff | Remove universal approval pauses, fixed document paths, automatic commits, and a prescribed planning Skill |

These materials informed method comparison. This package does not copy their scripts, templates, or whole instruction passages. Using general methods does not imply endorsement by the referenced projects.

## Main Design Choices

1. **Separate purpose from depth.** Determine whether the user needs ideas, a judgment, or a proposal, then scale scrutiny to evidence and risk. Do not push every request into software design.
2. **Reflect at the appropriate time.** Protect space for exploration; examine assumptions, counterexamples, and alternatives when preparing a decision.
3. **Allow conversation to be a complete result.** Do not write files just to record the discussion or seek authorization already granted. A formal handoff must still contain enough information.
4. **Give validation a specific role.** Identify which observation would change which decision, then revise only the affected assumptions and choices when evidence arrives. Do not present reflection, simulated users, or subjective scores as real-world evidence.
5. **Keep execution self-contained.** The main file and optional method reference are sufficient. Source links document influences, rather than resources to download or execute.

These are instruction-design choices, not measured performance guarantees. Continue evaluating them through real use, preserving valid user constraints and settled decisions when changing the rules.
