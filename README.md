# Research Paper Workflow Skill

A reusable workflow for high-stakes scientific paper work: research framing, contribution auditing, experiment design, manuscript review, reviewer response, revision auditing, terminology/provenance control, and final submission.

The repository is designed for use with AI coding/research agents, but the workflow is intentionally model-agnostic.

## Core idea

Paper revision is not “make the answer stronger.”

A good revision should:

1. recover what the original submission actually claimed, did, and reported;
2. identify the reviewer’s real concern rather than reacting to surface wording;
3. make the smallest sufficient change that closes that concern;
4. preserve provenance: distinguish original evidence, new revision evidence, corrected description, and new interpretation;
5. ask whether the revision itself creates a new question or contradiction;
6. keep manuscript, response letter, figures, tables, supplementary video, and submission metadata on the same factual story.

This principle grew out of a real robotics-paper revision workflow, but the repository is generalized for any scientific field.

## Repository structure

```text
.
├── README.md
├── SKILL.md
├── AGENTS.md
├── principles/
│   ├── revision-six-questions.md
│   ├── evidence-discipline.md
│   └── decision-priorities.md
├── workflows/
│   ├── reviewer-response.md
│   ├── revision-audit.md
│   └── final-submission.md
├── checklists/
│   ├── reviewer-closure.md
│   ├── provenance.md
│   ├── terminology-freeze.md
│   └── cross-artifact-consistency.md
└── templates/
    ├── reviewer-response-matrix.md
    └── final-audit-report.md
```

## Recommended use

For a revision, provide at minimum:

- original manuscript;
- complete editor/reviewer comments;
- current revised manuscript;
- response letter;
- any new tables, figures, supplementary video, or experiment notes.

Then ask the agent to run the workflow in `workflows/revision-audit.md`.

For a near-final submission, run `workflows/final-submission.md`.

## Design philosophy

The workflow prioritizes information gain, reviewer decision impact, and factual consistency over exhaustiveness. It is deliberately skeptical of:

- adding experiments that do not change any conclusion;
- defensive caveats that create new reviewer attack surfaces;
- rewriting historical provenance during revision;
- baseline proliferation;
- terminology drift across manuscript / figures / response / video;
- local polishing when the paper’s central claim-evidence chain is still weak.

## Status

Initial version. The skill will evolve from real paper-review and revision cases.
