# The Revision Six Questions

Run these before accepting any substantive revision change.

## 1. Is this actually new in the revision?
Classify it: new experiment, new baseline, new analysis, old experiment newly clarified, corrected description, or presentation-only change.

## 2. What did the original submission actually say and do?
Return to the original manuscript, figures/video, code/logs if needed. The original submission is the provenance anchor.

## 3. What is the reviewer actually worried about?
Translate wording into the underlying decision concern. Answer the concern, not merely the sentence.

## 4. Does the proposed change actually close that concern?
Imagine the reviewer reading the revision. Would the original question naturally disappear?

## 5. Does the change create a new question?
Ask whether the revision could make the reviewer wonder:
- Did the authors change the test scene?
- Why are the numerical results unchanged?
- Was this baseline tuned on the test set?
- Are there now two definitions of the same metric?
- Does this new limitation contradict the abstract?
- Is the video showing training or evaluation?
- Did a renamed variable leave stale labels in plots/tables?
- Did a clarification accidentally make a stronger claim?

## 6. Do all artifacts tell the same story?
Check clean manuscript, highlighted manuscript, response letter, tables, plots, figure legends, supplementary video, supplementary text, and submission metadata.

## Compact rule

> Original truth → reviewer concern → minimum sufficient fix → new-question test → cross-artifact consistency.
