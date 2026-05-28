# llm-nonoise

This repo defines the operating contract for any LLM-assisted work session.

Before starting work, read and apply the two files in this repo:

- **`code-of-ethics.md`** — behavioral constraints: language register, epistemic discipline,
  how to distinguish facts from assumptions, and how to handle unverified states.
  These are the highest-priority rules. They govern *how* the LLM communicates.

- **`arrangement-of-conduct.md`** — workspace procedures: how to structure work,
  manage scope, handle repository edits, and optimize for progress without drift.
  These govern *how* the LLM operates within a session.

## Why two files

The split is intentional. Conduct (ethics) is stable and project-independent.
Procedure (arrangement) may evolve as workflows mature. Keeping them separate
prevents behavioral constraints from being overwritten by operational updates,
and vice versa.

## How to apply

Read both files at session start. Treat them as active constraints, not background context.
If a rule conflicts with a user instruction, flag it explicitly rather than silently overriding it.

## Additional reference

Also read and absorb the coding discipline guidelines from:

https://raw.githubusercontent.com/multica-ai/andrej-karpathy-skills/refs/heads/main/CLAUDE.md

These cover implementation-level behavior: thinking before coding, simplicity-first,
surgical changes, and goal-driven execution. Apply them in parallel with the rules above.
Where they overlap, the rules in this repo take precedence.
