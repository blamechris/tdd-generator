# tdd-generator

Turn business requirements into clear, testable technical plans.

> Status: Pre‑alpha • Public repo README

---

## Overview

**tdd-generator** converts a Product Requirements Document (PRD) or a concise user prompt into a structured Technical Design Document (TDD). It fills a well defined template, highlights ambiguities, and flags any acceptance criteria the current inputs cannot satisfy. The goal is faster planning, consistent documentation, and earlier detection of gaps.

## Key features

* PRD or prompt in, TDD out
* Strict template with required sections auto filled
* Ambiguity detection and call outs
* Unmet acceptance criteria clearly labeled
* PRD ⇄ TDD comparison to spot gaps
* Multi stage LLM prompting pipeline
* Planned exports to common formats (Markdown, JSON)

## How it works (high level)

1. Parse the PRD or prompt
2. Map content to the TDD schema
3. Fill sections with structured text
4. Compare the generated TDD to the source PRD
5. Highlight ambiguities and unmet acceptance criteria
6. Produce an exportable artifact

## Quick start

CLI prototype is in progress. Expected usage examples:

```bash
# Generate a TDD from a PRD file
 tddg generate --prd path/to/prd.md --out tdd.md

# Validate an existing TDD against a PRD
 tddg validate --prd prd.md --tdd tdd.md
```

## Roadmap

1. Minimal CLI prototype
2. Sample PRD set and fixtures
3. Evaluation script for quality and drift
4. Model adapter layer and prompt packs
5. Editor and IDE integrations
6. CI checks for PRD ⇄ TDD consistency
7. Team workflow guide and templates

## Authorship and credit

* **Idea originator:** Chris Pishaki
* **Origin date:** 2025‑09‑01
* **Credit policy:** Public mentions and docs attribute origin to Chris Pishaki. New contributors are listed as co authors on commits and docs. Please include attribution in presentations and demos.

## Contributing

Issues and pull requests are welcome. Please open an issue to discuss larger changes before starting work. A contributor guide and code of conduct will be added before beta.

## License

To be added.

## Changelog

Releases are tracked with Git tags and summarized in `CHANGELOG.md` once the CLI prototype lands.

## Contact

Open an issue to start a discussion or propose features.
