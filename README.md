# Research Paper Workflow Skill

A compact, reusable workflow for scientific-paper revision.

The current repository deliberately focuses on **peer-review revision first**. The default entry point is:

> **`SKILL.md`**

For normal use, read only that file. The other folders contain expanded notes and templates and should be loaded only when needed.

## Use in Codex CLI

Use the name declared in `SKILL.md` when cloning into Codex's user skills
directory.

```sh
mkdir -p ~/.agents/skills
git clone https://github.com/huxiaoyi-ovo/research-paper-workflow-skill.git \
  ~/.agents/skills/scientific-paper-revision
```

Invoke it with `$scientific-paper-revision`. Keep the supporting folders
alongside `SKILL.md` so Codex can open them when needed. See the
[Codex skill discovery documentation](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills).

## Update the installed skill

If you installed the skill using the clone command above, update it before starting a new revision cycle:

```sh
git -C ~/.agents/skills/scientific-paper-revision pull --ff-only
```

If the local checkout contains changes, review them before updating. Keep the skill version stable throughout an active revision cycle so that changes to the workflow do not silently change the audit criteria.

## What this skill is for

Use it when you have:
- an original manuscript;
- editor/reviewer comments;
- a revised manuscript;
- a response letter;
- new experiments / figures / supplementary material.

It helps answer the questions that actually matter during revision:

- What is the reviewer really worried about?
- Is the requested change actually necessary?
- Is this evidence old or genuinely revision-new?
- Does the response fully close the concern?
- Does the fix create a new question?
- Do manuscript, response, figures, tables, and video tell the same story?
- When should we stop revising?

## Prepare a revision handoff

Keep the original submission read-only and store the current revision, response letter, and reviewer comments as separately versioned files. For each new experiment, retain the configuration, raw results, and the script or command used to generate the reported figure or table. Record which revision introduced each result. This makes the final provenance audit reproducible and prevents old evidence from being mistaken for new revision work.

## Core rule

> Preserve the truth of the original submission, identify the reviewer’s real concern, make the minimum sufficient change that closes it, test whether the change creates a new problem, and keep every artifact consistent.

## Why the skill is intentionally short

Revision work becomes worse when the workflow itself becomes heavy.

The skill therefore avoids:
- mandatory long checklists;
- unnecessary experiment generation;
- exhaustive weakness hunting;
- loading every supporting file for every task.

Expanded checklists/templates remain in the repository as optional references.

## Repository

- `SKILL.md` — **default revision skill**
- `AGENTS.md` — minimal execution rule
- `principles/` — optional expanded reasoning notes
- `workflows/` — optional detailed workflows
- `checklists/` — optional final-audit checklists
- `templates/` — response/audit templates

## Status

Revision skill v1, distilled from real reviewer-response and final-submission work.
