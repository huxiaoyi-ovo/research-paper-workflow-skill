---
name: scientific-paper-revision
description: Lean PI/reviewer workflow for revising a scientific paper after peer review. Use it to identify the real reviewer concern, decide the minimum sufficient revision, preserve evidential provenance, strengthen interpretation, write response letters, and run final consistency checks without overengineering the revision.
---

# Scientific Paper Revision Skill

Use this skill for **peer-review revision and near-final revision review**, not for generic paper writing.

The goal is:

> Close the concerns that can change the reviewer/editor decision with the minimum sufficient scientific change, while preserving the factual history of the work, extracting the strongest interpretation actually supported by the evidence, and avoiding new contradictions.

Do **not** preload other repository files unless a task specifically needs a template or expanded checklist. This file is the default workflow.

## 1. Work from both sides of the review process

### Author viewpoint

Protect:
- the real contribution;
- scientific correctness;
- evidential provenance;
- time and experiment cost;
- consistency of the final submission.

Do not add work merely because another weakness can be imagined.

### Reviewer viewpoint

A reviewer needs to see:
- that the concern was understood correctly;
- evidence that directly bears on the concern;
- an interpretation that explains what the evidence means;
- a revision that is easy to verify;
- fair comparisons and calibrated claims;
- no new ambiguity introduced by the response.

A good revision serves both viewpoints at once.

## 2. Identify what can actually change the decision

Reconstruct the review in its original order and distinguish:

- **positive/descriptive remarks** — usually no action;
- **actionable minor comments** — fix efficiently;
- **major concerns** — require explicit closure.

Do not treat every comment equally.

Internally prioritize:
- **A:** can invalidate the main claim, evidence, protocol, or fairness;
- **B:** materially affects reviewer confidence, interpretation, reproducibility, or acceptance;
- **C/D:** polish, preferences, or edge cases.

Spend most effort on A and important B issues.

## 3. Run the Six Questions for every important revision

1. **What kind of change is this?**  
   New evidence, new analysis, clarification of existing evidence, correction of description, claim adjustment, or presentation-only change?

2. **What was true in the original submission?**  
   Recover the original claim, protocol, evidence, and wording whenever revision history matters.

3. **What is the reviewer actually deciding?**  
   Identify the underlying concern rather than reacting only to the literal phrasing.

4. **Does the proposed change close that concern?**  
   After reading the revision, would a skeptical reviewer still need to ask the same question?

5. **What new interpretation could this change accidentally create?**  
   Check for new ambiguity about provenance, protocol, fairness, metric meaning, scope, or evidential role.

6. **Is the same scientific story preserved everywhere?**  
   Manuscript, response, figures, tables, supplementary material, and metadata must agree.

Compact form:

> Original truth → reviewer concern → minimum sufficient fix → unintended-consequence test → cross-artifact consistency.

## 4. Choose the smallest sufficient action

A reviewer comment may require only:

- clarification;
- wording or presentation repair;
- claim narrowing;
- additional analysis;
- stronger comparison;
- new experiment;
- explicit scope definition.

Do not default to new experiments.

Before proposing one, ask:

> If the result changes, what claim or decision changes with it?

If no meaningful decision changes, the experiment is low value.

## 5. Preserve evidential provenance

Revision history is part of scientific accuracy.

Use language that matches what actually happened:

- **clarified / made explicit** — existing evidence is described more clearly;
- **added / extended / evaluated** — genuinely new revision work;
- **corrected** — an earlier description was factually inaccurate;
- **revised the interpretation** — the evidence is unchanged but its interpretation is refined;
- **replaced / redrew** — presentation changed, not the underlying evidence.

Do not let clearer revised wording rewrite the history of the original submission.

Any change in wording, figures, or framing must remain compatible with the origin of the reported evidence.

## 6. Interpret evidence without inventing mechanism

Do not confuse two errors:

- **over-claiming:** turning aggregate results into an untested causal mechanism;
- **under-interpreting:** reporting a table correctly but failing to explain what its pattern means.

A strong Results section should move beyond number repetition and state the most informative conclusion directly supported by the comparison.

Prefer:

> observed pattern → controlled contrast → supported interpretation

Avoid claiming a unique internal cause unless the experiment isolates it.

When several metrics or baselines reveal a common tension, compress them into the higher-level scientific finding instead of narrating every row.

## 7. Write responses for closure, not self-defense

For each actionable comment, prefer:

> **Direct answer → strongest relevant evidence → what changed → exact location**

Good responses:
- answer early;
- acknowledge genuine ambiguity when it existed;
- distinguish evidence from interpretation;
- state scope when scope is the concern;
- stop once the concern is closed.

Avoid:
- long defensive disclaimers;
- unrelated limitations;
- answering a stronger question than the reviewer asked;
- adding caveats after the evidence is already sufficient;
- claiming necessity when the evidence only supports usefulness or tested-condition value.

When a reviewer suggests an ideal stronger version, distinguish it from the core condition needed to resolve the concern.

## 8. The response letter must not carry missing science

Every important response must correspond to a real manuscript state.

Verify:
- the response claim is reflected in the paper where necessary;
- the stated location is correct;
- terminology is consistent;
- figures and tables support the response;
- no essential explanation exists only in the response letter.

A useful final check is:

> **Does the response letter contain a scientific interpretation that the paper itself still needs?**

If yes, move the essential insight into the manuscript and let the response letter point to it.

Reviewer closure is not complete when the rebuttal is persuasive but the revised paper still leaves the same scientific question unexplained.

## 9. Near-final review requires four separate passes

Do not equate “no major factual error” with “the paper is finished.”

### Scientific truth audit
Check:
- central claim;
- evidence;
- protocol;
- comparison fairness;
- metric definitions;
- numerical consistency;
- provenance;
- claim scope.

### Reviewer closure audit
Check:
- reviewer/comment mapping and order;
- closure of all major concerns;
- whether the response addresses the real concern;
- whether the reply is evasive, inflated, or over-defensive.

### Scientific interpretation audit
Read the Results and Discussion as if seeing the paper for the first time.

Ask:
- What does each major experiment actually teach the reader?
- Do key tables/figures participate in the argument, or merely contain data?
- Are failure modes or trade-offs interpreted at the strongest level the evidence supports?
- Are controlled interventions distinguished from separately trained baselines?
- Does Discussion synthesize evidence rather than repeat Results?
- Did a reviewer’s “why / failure mode / mechanism” concern produce deeper understanding in the manuscript, not only a longer response letter?

This pass looks for **argument gaps**, not bugs.

### Cross-artifact audit
Check:
- clean manuscript;
- highlighted manuscript;
- response letter;
- tables and figures;
- supplementary material;
- submission metadata.

Search for:
- stale terminology;
- inconsistent numerical values;
- changed definitions;
- mismatched experiment roles;
- outdated labels;
- artifacts that imply different scientific histories.

## 10. Run a fresh-reviewer pass before freezing

After the revision history has become familiar, deliberately ignore it once.

Read the paper in normal order, especially:

> Results → Discussion → Conclusion

Ask only:

- What is the central finding?
- Which evidence supports it?
- What did the ablations reveal beyond “ours is better”?
- What did the external baselines teach?
- Which claims are directly supported, and which are only plausible?
- Are the real operating boundaries clear without sounding defensive?

If the answers depend on knowing the rebuttal history, the manuscript is not yet self-sufficient.

## 11. General failure modes

### Solving the wording instead of the concern
The response sounds responsive but leaves the reviewer’s underlying decision uncertainty untouched.

### Rewriting history during revision
A clarification is described as new evidence, or new evidence is presented as if it had always existed.

### Treating every concern as an experiment request
The revision becomes larger without becoming more informative.

### Over-defending
The response introduces additional weaknesses, caveats, or attack surfaces that were unnecessary to answer the reviewer.

### Over-claiming from a narrow comparison
Evidence for usefulness or tested-condition benefit is turned into a general or causal claim.

### Under-interpreting strong evidence
The paper reports correct data but fails to extract the scientific pattern already present in the results.

### Letting the rebuttal become better than the paper
The authors understand the concern in the response letter but do not transfer that understanding into the manuscript.

### Inconsistent scientific identity
The same method, metric, condition, or experiment acquires different names or roles across manuscript, response, figures, and supplementary material.

### Local optimization after the main case is already closed
Late polishing creates version drift or new inconsistencies without materially improving the editor’s decision.

## 12. Stop condition

Freeze the science only when:

- all major concerns have a direct answer;
- the evidence is fair and sufficient;
- claims match the evidence;
- key results are interpreted, not merely reported;
- the manuscript is self-sufficient without the rebuttal;
- provenance is correct;
- all submission artifacts are scientifically consistent.

If only low-impact polish remains, further revision may introduce more risk than value.

## Default output style

Do not dump a long checklist unless asked.

For near-final review, return:
1. **overall judgment**;
2. **A/B issues that still matter**;
3. **argument or interpretation gaps**;
4. **exact changes to make**;
5. **what should not be touched**;
6. **whether the revision is ready to freeze**.
