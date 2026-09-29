---
name: scientific-paper-revision
description: Lean PI/reviewer workflow for revising a scientific paper after peer review. Use it to identify the real reviewer concern, decide the minimum sufficient revision, preserve experiment provenance, write response letters, and run final cross-artifact checks without overengineering the revision.
---

# Scientific Paper Revision Skill

Use this skill for **peer-review revision**, not for generic paper writing.

The goal is simple:

> Close the concerns that can change the reviewer/editor decision, with the minimum sufficient scientific change, while preserving the factual history of the original submission and avoiding new contradictions.

Do **not** preload the other repository files unless a task specifically needs a template or expanded checklist. This file is the default workflow.

## 1. Work from two viewpoints

### Author viewpoint
Protect:
- the real contribution;
- scientific truth and provenance;
- time and experiment cost;
- consistency across all submitted artifacts.

Do not add work merely because a weakness can be imagined.

### Reviewer viewpoint
The reviewer wants to see:
- that the concern was understood correctly;
- decisive evidence, not rhetoric;
- a manuscript change that is easy to verify;
- fair comparisons;
- calibrated claims;
- no new ambiguity introduced by the revision.

The best revision is the intersection of these two viewpoints.

## 2. First find the decision-critical concerns

Reconstruct the complete review in original order.

Separate:
- **positive/descriptive remarks** — usually no action;
- **actionable minor comments** — fix efficiently;
- **major concerns** — can affect acceptance and need explicit closure.

Do not treat every comment equally.

Internally prioritize:
- **A:** can invalidate the main claim, protocol, fairness, or evidence;
- **B:** materially affects reviewer confidence, reproducibility, or acceptance;
- **C/D:** polish or edge cases.

Spend most effort on A and important B issues.

## 3. For every important revision, run the Six Questions

1. **Is this actually new in the revision?**  
   New experiment, new baseline, new analysis, old evidence newly clarified, corrected description, or presentation-only change?

2. **What did the original submission actually say and do?**  
   Check the original manuscript / figures / video / logs when history matters.

3. **What is the reviewer really worried about?**  
   Answer the underlying decision concern, not just the surface wording.

4. **Does the proposed change actually close that concern?**  
   Would the reviewer naturally stop asking the original question?

5. **Does the change create a new question?**  
   For example: Did the test scene change? Why are numbers unchanged? Was a baseline tuned on the test set? Are there now two metric definitions?

6. **Do all artifacts tell the same story?**  
   Manuscript, response, tables, figures, captions, supplementary video, and submission metadata must agree.

Compact form:

> Original truth → reviewer concern → minimum sufficient fix → new-question test → cross-artifact consistency.

## 4. Choose the smallest sufficient action

A reviewer comment may require only one of:

- clarification;
- terminology / presentation fix;
- claim narrowing;
- additional analysis;
- stronger baseline;
- new experiment;
- explicit scope limitation.

Do not default to new experiments.

Before proposing an experiment, ask:

> If the result goes either way, what claim or decision changes?

If essentially nothing changes, the experiment is low value.

## 5. Preserve provenance

Revision history is evidence.

Use wording that matches what actually happened:

- **clarified / made explicit** → evidence already existed;
- **added / extended / evaluated** → genuinely new revision work;
- **corrected** → factual description was wrong;
- **revised the interpretation** → same evidence, different interpretation;
- **replaced / redrew** → presentation change.

Never write “we added” for an experiment already present in the original submission.

Never imply a new test layout if the original formal results already used it.

Unchanged numerical results must make sense under the stated revision history.

## 6. Write responses for closure, not for self-defense

For each actionable comment, prefer:

> **Direct answer → strongest evidence → what changed → exact location**

Good response behavior:
- answer early;
- acknowledge a real ambiguity when it existed;
- show fair evidence;
- state scope when the reviewer explicitly asks about scope.

Avoid:
- long defensive disclaimers;
- unrelated weaknesses;
- answering a stronger question than the reviewer asked;
- adding caveats after the concern is already closed;
- claiming necessity when the experiment only shows value under tested conditions.

If the reviewer says “ideally”, distinguish the core requirement from the optional stronger version.

## 7. Couple response and manuscript

Every important response must have a matching manuscript state.

Check:
- the response claim exists in the manuscript;
- the stated “Location of changes” is correct;
- terminology matches;
- figures/tables support the wording;
- the response does not rely on an explanation absent from the paper when that explanation is needed for understanding.

No orphan response claims. No orphan manuscript changes.

## 8. Audit the package, not just the paper

Near submission, stop exploratory revision and run three passes.

### Scientific truth audit
Check:
- central claim;
- evidence;
- protocol;
- baseline fairness;
- metric definitions;
- numerical invariants;
- provenance.

### Reviewer closure audit
Check:
- correct reviewer/comment mapping and order;
- all major concerns explicitly closed;
- skipped numbering explained if positive comments were omitted;
- response is neither evasive nor over-defensive.

### Cross-artifact audit
Check:
- clean manuscript;
- highlighted manuscript;
- response letter;
- figure-internal labels;
- table labels;
- supplementary video;
- supplementary text.

Look especially for:
- old method names;
- renamed variables left in legends;
- map/metric naming drift;
- video clips mislabeled as formal evaluation vs training examples;
- playback speed not marked;
- result tables that no longer match the manuscript.

## 9. Common failure patterns learned from real revision work

These deserve explicit suspicion:

- a clarification is accidentally written as a newly added experiment;
- reviewer concern is about fairness, but the response talks only about architecture;
- a baseline is too weak to support the comparison;
- a variable is renamed in prose but survives in plots/video;
- a map/metric gets multiple near-synonymous names and looks like multiple objects;
- a response overexplains limitations and opens a new attack surface;
- a revised figure silently changes the apparent role of an experiment;
- authors keep polishing local details after the main reviewer concerns are already closed;
- final files drift into different scientific versions.

## 10. Stop condition

When:
- all major concerns have a direct answer;
- the evidence is fair and sufficient;
- claims match the evidence;
- provenance is correct;
- manuscript/response/figures/video are consistent;

**stop changing the science.**

If only C/D-level polish remains, further revision is more likely to introduce version drift than improve the decision.

## Default output style when using this skill

Do not dump a long checklist unless asked.

Return:
1. **overall judgment**;
2. **A/B issues that still matter**;
3. **exact changes to make**;
4. **what should not be touched**;
5. **whether the revision is ready to freeze**.
