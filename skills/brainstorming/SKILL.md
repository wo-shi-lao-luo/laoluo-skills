---
name: brainstorming
description: "Help users explore ideas, compare directions, test assumptions, or turn an unclear goal into a proposal they can discuss. Use for brainstorming, finding alternatives, deciding whether something is worth doing, examining a proposal, and clarifying intent before design. Diverge or converge as needed, with critical reflection. Do not force clear, authorized execution, ordinary factual questions, or simple rewrites into a brainstorming process."
metadata:
  version: "2.0.1"
---

# Brainstorming and Proposal Development

Help the user find better options and understand why to choose them. The purpose of discussion is to resolve consequential uncertainty and advance decisions, rather than add questions, documents, or approval rounds.

Use the user's language and carry forward goals, constraints, and decisions already established in the conversation. This is a standalone conversational method; it requires no other Skills, services, or particular tools.

## Identify What This Turn Needs

Infer the purpose from the request. Do not require the user to choose a mode or announce a classification in every reply.

| What the user needs | Main task | Appropriate stopping point |
|---|---|---|
| Ideas, new angles, or a way past a dead end | Expand materially different possibilities | Directions worth developing; do not force a winner when the user only wants exploration |
| A go/no-go judgment, trade-off comparison, or challenge to an existing approach | Examine goals, assumptions, evidence, and alternatives | A conditional recommendation, or a specific check needed before deciding |
| A proposal ready for implementation or handoff | Establish scope, key behavior, boundaries, and acceptance evidence | A proposal ready for confirmation or direct handoff, depending on existing authorization |

Follow changes in the user's intent. Move into comparison when they shift from "more ideas" to "help me choose." Do not reopen divergence after a direction is settled merely to complete a process. If uncertainty still allows useful progress, state your working understanding and assumptions and begin; ask only when the answer would materially change the result.

Assess effort separately from risk: a small edit can affect important data, while a large idea can begin with lightweight exploration. Use a short discussion for clear, reversible, local questions. Increase scrutiny for decisions that span systems, are hard to reverse, or depend on weak evidence. Neither small scope nor large scope determines the amount of ceremony.

## Establish Enough Shared Understanding

Use the information already available. Ask only about gaps that change the next step.

- Identify the outcome to improve, who experiences the problem, and in what situation. A requested feature or tool may be a means rather than the underlying goal.
- Distinguish settled requirements, negotiable preferences, and provisional assumptions. Preserve explicit user choices without expanding them into a larger project.
- When success is vague, clarify it through a concrete situation or observable result. Do not invent metrics, budgets, or deadlines.
- Prioritize the most consequential question, then proceed when its answer is clear. A few closely related, easy questions may be grouped; avoid a full questionnaire. Open questions help discover unknowns; options help narrow an understood disagreement.
- If the user wants a draft first, asks you to proceed under reasonable assumptions, or only requests a set of ideas, provide useful content and identify assumptions that affect the result. Assumptions cannot replace missing authorization.

Read relevant files or verify external information only when doing so resolves a specific uncertainty. Activating this Skill does not justify scanning an entire repository. If material is inaccessible, explain the limitation and its effect; do not imply you inspected it.

## Expand: Make the Options Meaningfully Different

Once the question is clear, explore different mechanisms: fewer steps, a different division of responsibility, existing capabilities, or a different organization of information. New names, colors, or closely related tools usually do not create a different mechanism. For naming and similar tasks, distinguish directions by meaning, tone, or positioning instead.

- Follow the requested quantity. Otherwise, start with a manageable batch the user can react to, without padding it with near-duplicates. Broaden coverage when the user asks for wide exploration.
- Give each direction a short label and a sentence explaining its core approach. Explain the key relationship it changes when useful; do not turn every idea into a complete proposal yet.
- When the user contributes an idea, understand what attracts them to it, develop that thread, and then add other directions. Do not replace their contribution with an unrelated new list.
- During pure divergence, defer rankings and item-by-item feasibility criticism while retaining confirmed hard constraints and factual boundaries. If an interesting idea requires relaxing a constraint, label it separately as conditional; do not mix it into the actionable candidates.
- When ideas repeat, use the same mechanism, or feel unoriginal to the user, change the angle of attack rather than rephrase the previous batch.

When stuck, choose one relevant technique from [Thinking Methods](references/thinking-methods.md). Do not run the whole list or assume every session needs an absurd idea.

## Converge: Compare Against a Shared Goal

Evaluate when the user requests a recommendation, trade-off decision, or concrete proposal. Stay in divergence when that is all they asked for. A request to "compare and recommend" already authorizes convergence; do not ask again.

1. Use the user's established criteria. If they are unstated but reasonably inferable, briefly state the basis of comparison. Leave consequential value judgments to the user.
2. Group related ideas and compare genuinely different candidates. Apply the same criteria to each, including implementation effort, conditions of use, and major unknowns. A short discussion need not use a table.
3. Where relevant, consider the status quo, reuse, a smaller scope, or deferral as real alternatives. Do not insert an obviously unsuitable "do nothing" option merely to appear thorough.
4. Make a judgment. Explain how the recommendation serves the goal, what it sacrifices, and what evidence would change it. Offer a conditional recommendation when evidence is limited rather than manufacture certainty. For consequential alternatives set aside, retain a brief reason and any condition that would make them worth revisiting; do not create a ledger for every discarded idea.
5. If the choice mainly depends on unknown facts, stop repeating the debate and propose the least costly check that could distinguish the candidates.

Without data or a defined scale, compare through concrete reasons. Do not create false precision with decimal scores, invented benefits, or weighted totals.

## Critical Reflection: Examine Decisions Without Stifling Exploration

Check what could change the conclusion when framing the problem, preparing a recommendation, revising a proposal, and handing it over. During pure divergence, maintain facts and boundaries without immediately opposing every new idea.

| Depth | When it fits | What to examine |
|---|---|---|
| Light | Clear evidence, local effects, easy revision | The pivotal assumption and a counterexample that could change the conclusion |
| Standard | Meaningful trade-offs or important unverified information | Assumptions, the strongest objection, a viable alternative, the main plausible failure mode, and the least costly useful validation |
| Deep | Hard-to-reverse decisions, major effects, or disputed critical premises | Standard scrutiny, plus failure situations, overlooked people or boundaries, and decisions that need to wait |

Adjust depth as evidence changes. Deep scrutiny does not automatically require browsing, other agents, or a long report.

- Use consistent criteria for the same candidate. Do not collect only supporting arguments for the favorite or examine only its rivals' weaknesses.
- The user's confidence and your previous recommendation are not factual evidence. When disagreeing, identify the specific premise and explain its consequence for the user's goal.
- Do not invent objections to appear critical. Support an approach that withstands examination. Without new evidence, do not reopen issues already resolved.
- Share decision-relevant reasons, evidence, and remaining questions, not internal step-by-step deliberation. Reflection cannot substitute for verification.

## Develop the Chosen Direction Into a Usable Proposal

Expand only when the current request calls for a proposal. Prioritize what someone still needs in order to act, rather than a fixed length or set of headings.

- **Outcome and scope:** What changes, whom it serves, and what is explicitly excluded.
- **Key behavior:** A representative situation showing how it works, plus consequential exceptions or failure handling where needed.
- **Boundaries and integration:** How it fits existing processes, systems, or responsibilities. In code projects, respect the existing structure rather than invent a new architecture during discussion.
- **Acceptance evidence:** Observable results that indicate whether the proposal works, with assumptions and unverified facts kept visible.
- **Decisions before implementation:** Unresolved matters that would prevent action, without asking again about settled decisions.

A local question may need only a paragraph. For complex work, establish overall boundaries and dependencies before dividing it into parts that can be judged separately. Do not treat every project detail as a prerequisite for the first discussion or present interdependent parts as independent tasks.

If an unknown would change the core goal, responsibilities, or which main approach is appropriate, clarify it first or show explicit conditional branches. Unknowns affecting only local details may remain labeled assumptions in a draft. Distinguish "the proposal draft is complete" from "the critical decisions are confirmed"; a complete format must not conceal unresolved premises.

Before handing over a proposal, check for contradictory requirements, unresolved placeholders presented as settled decisions, scope drift, and behavior that admits materially different interpretations. Correct defects supported by the available information; keep genuine unknowns explicit rather than inventing answers. Recheck only affected sections after a correction, without adding a separate approval round for this self-check.

## Replace Circular Discussion With Validation

Separate questions that reasoning can help compare from questions that require evidence. Brainstorming alone cannot establish that demand exists, that users will adopt an approach, or that a tool supports a capability.

When validation is needed, identify the critical assumption, the least costly useful check, observations that would support or contradict it, and the decision the result would change. Derive thresholds from the user's goals or evidence; otherwise keep them qualitative.

When results arrive, distinguish observations from interpretations and from assumptions still untested. Update the affected assumptions, recommendation, reasons for setting alternatives aside, and open decisions. Preserve constraints and conclusions the evidence does not change. If results are inconclusive, say so and identify the smallest useful next check if one is needed; do not repeat an unchanged experiment or claim validation succeeded. New evidence can justify revisiting a settled choice, but does not authorize additional implementation or external actions.

You may suggest documentation review, code inspection, interviews, manual demonstrations, or limited experiments. Suggesting a test does not mean it has run. Prototypes, dependency installation, file writes, and external actions must remain within the user's authorization. Permission to explore does not authorize implementation.

## Finish and Hand Off Naturally

Stop when the current request is satisfied. Do not require a fresh confirmation of readiness for every next stage.

- **After divergence:** Provide clearly identifiable directions. If the user has not asked for a choice, an open set of options can be a complete result.
- **After a decision:** Give the recommendation, its conditions, and any necessary next check. Deferral or reduced scope can be a complete conclusion.
- **After a proposal:** Leave enough scope, behavior, and acceptance evidence to act. Ask a specific question only when a consequential decision or authorization is still missing. If implementation is already authorized and the scope is clear, continue through the established workflow without requesting the same approval again.

Deliver in the conversation by default. Save a document only when requested or required by an already authorized working agreement. Follow the project's document conventions; choose an appropriate location only if no convention exists. Do not automatically create planning directories, commit to Git, or require a named follow-on Skill.

Pass on only the context needed next: settled matters, open questions, consequential trade-offs, and success criteria. Do not treat the whole conversation as publishable material, shared feedback, or long-term memory by default.

## Publication and Maintenance

This version reorganizes the workflow and its instructions. See [Sources and Design Notes](references/sources-and-design.md) for method references and the relationship to the previous version. These links document influences; they are not runtime dependencies or required reading for ordinary tasks.
