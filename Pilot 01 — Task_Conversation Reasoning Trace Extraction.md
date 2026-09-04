## Source
Process the entire supplied conversation window as one continuous context.

## Objective
Compress the conversation into a structured reasoning trace.

The output must preserve how the thinking developed, including:
- the initial question or trigger;
- early hypotheses and interpretations;
- challenges, objections, and counterexamples;
- missing variables or assumptions that were identified;
- branches that were separated;
- rejected or weakened models;
- revisions and newly introduced concepts;
- connections discovered between previously separate ideas;
- unresolved questions.

## Critical Rule
Do not summarize only the final conclusions.

The reader must be able to understand:
1. where the discussion started;
2. why each major interpretation changed;
3. what evidence or objection caused the change;
4. where the discussion ended;
5. what remains uncertain.

## Compression Rule
Compress language, not reasoning.

Remove:
- repeated phrasing;
- conversational filler;
- duplicated examples;
- stylistic repetition;
- jokes that do not affect the reasoning.

Preserve:
- every meaningful change in reasoning;
- every important correction;
- every change of scope, role, world, definition, or assumption;
- representative wording when the exact formulation materially affected the discussion.

## Do Not
- Do not create permanent Obsidian Nodes yet.
- Do not decide which concept is a Root Node.
- Do not rewrite the discussion as if the final model was obvious from the beginning.
- Do not resolve disagreements that the conversation itself did not resolve.
- Do not add external theories or terminology unless explicitly marked as an editorial suggestion.
- Do not praise, evaluate, diagnose, or profile the participants.

## Required Output

# [Conversation Topic]

## 1. Starting Point
What initiated the discussion?

## 2. Reasoning Trace

### Stage 01 — [Short descriptive name]
- Claim / question:
- Supporting reasoning:
- Challenge or uncertainty:
- Resulting change:

### Stage 02 — [Short descriptive name]
- Claim / question:
- Supporting reasoning:
- Challenge or uncertainty:
- Resulting change:

[Continue for all meaningful transitions.]

## 3. Major Branches
Document ideas that separated into parallel paths rather than forming one linear sequence.

## 4. Model Changes
| Earlier model | Why it became insufficient | Revised model | Status |
|---|---|---|---|

Status must be one of:
- retained
- revised
- rejected
- unresolved

## 5. Newly Discovered Connections
List relationships that became visible during the discussion and explain why each connection matters.

## 6. Candidate Concepts
List possible future Nodes, but do not finalize or rank them.

For each candidate:
- Candidate title:
- What it currently explains:
- Evidence from the reasoning trace:
- Why it may or may not deserve independent Node status:

## 7. Open Questions
What has not yet been resolved or sufficiently tested?

## 8. Compression Notes
Briefly state:
- what kinds of material were removed;
- what was deliberately preserved;
- any section where compression risked losing important nuance.

Deliverables

1.
REASONING_TRACE.md

2.
Compression Report

3.
Compression Statistics

4.
Questions Encountered