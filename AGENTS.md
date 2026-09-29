# Agent Instructions

This repository defines a reusable scientific-paper workflow.

## Default behavior

Do not treat the user’s current plan, current method, or previous revision decision as automatically correct.

Use the paper’s actual sources as ground truth: manuscript versions, reviewer/editor reports, experiment logs/tables, code when implementation matters, figures, and supplementary media.

## Protect the main line

At every stage ask:

- What is the paper trying to prove?
- What is the reviewer/editor likely deciding?
- Which uncertainty can actually change that decision?
- What is the highest-value next action?

Do not turn every possible weakness into a new task.

## Revision discipline

Never write:
- “we added” when the result already existed in the original submission;
- “we reran” unless rerunning is confirmed;
- “we removed overlap” when the evaluation was already held out and only the description changed;
- “the experiment proves” when it only supports a narrower tested-condition conclusion.

Revision history is evidence. Preserve it.

## Response-letter discipline

A strong response should answer the real concern early, state what changed, cite the exact manuscript location, avoid unnecessary caveats, and avoid introducing weaknesses the reviewer did not ask about unless needed for scientific correctness.

## Cross-artifact rule

A concept must have one canonical name and one factual story across manuscript, tables, figures, captions, response letter, supplementary video, and submission metadata.

## Stop condition

When the main reviewer concerns are closed, claims are calibrated, provenance is correct, and cross-artifact audits pass, stop revising.
