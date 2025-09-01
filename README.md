# tdd-generator
An application to leverage the architect-engineer aspect of planning and turning business requirements into technical requirements.


Idea: PRD/prompt → templated TDD generator
Owner: Chris Pishaki   Co-devs: tbd
Origin date: 2025-09-01
Summary: Takes a written PRD or user prompt, outputs a strict TDD template auto-filled from source. Flags ambiguities and marks unmet acceptance. Uses multi-stage LLM prompts and validates against the PRD.
Why: Faster, consistent TDDs. Surfaces missing requirements early.
High-level flow: PRD/prompt in → parse → map to TDD sections → fill → diff vs PRD → flag gaps → export.
Credit policy: Public mentions and docs attribute origin to Chris Pishaki New contributors listed as co-authors on commits and docs.
Next steps: 1) Minimal CLI prototype 2) Sample PRD set 3) Eval script.
