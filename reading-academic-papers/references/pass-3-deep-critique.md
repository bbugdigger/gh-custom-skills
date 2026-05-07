# Third Pass: Deep Critique and Virtual Re-implementation

Goal: understand the paper deeply enough to identify both its real innovations and its hidden failings. The hallmark of this pass is **virtual re-implementation** — mentally reconstructing the work from scratch (making the same assumptions as the authors), then comparing your version to theirs. The gap between the two is where insight lives.

For a human, a third pass takes 4–5 hours for a beginner, ~1 hour for an experienced reader.

## Mindset

Approach with skepticism but not hostility. Plenty of published work has flaws; finding them is the point of this pass. Challenge every assumption in every statement. Ask "how would I have done this?" — if your version diverges from theirs, that divergence is data about either the paper or your understanding.

Beware of two failure modes:

- **Performative skepticism** — listing generic concerns ("could be larger sample size", "more diverse population") that apply to almost any paper. Specific, paper-grounded critique only.
- **Reverence** — assuming the authors knew what they were doing because they got published. Many published results don't replicate. Read for what's there, not what you expect to be there.

## The challenge framework

For each major claim in the paper, work through these questions.

### Examine the assumptions
- What does this result rely on — about the environment, the data, user behavior, hardware, the population studied, etc.?
- Are those assumptions defensible? In what regime do they break?
- Are there assumptions the authors didn't state explicitly but the result depends on?

### Examine the methods
- Did they actually measure what they claim? (Construct vs. operationalization — the thing they measured may not be the thing the abstract names.)
- Were the controls adequate? What confound is left unaddressed?
- Were tests carried out in a standard way, or did they invent a non-standard protocol that conveniently produces the result?
- For empirical work: what's the data source? Is selection bias plausible? Is the sample representative of the population the conclusion generalizes to?
- Could the result be a measurement artifact rather than a real effect?

### Examine the statistics
- Were the right tests applied? Were they applied correctly?
- Is "significant" used in the colloquial sense or the statistical sense? They are not the same.
- Sample size: 10 or 10,000? In what regime is the effect size meaningful?
- Is error analysis present, or is it eyeball-and-hope?
- Is there a multiple-comparisons problem? (Many tests run, only the significant ones reported.)

### Examine the conclusions
- Do the conclusions follow from the observations, or is there a leap?
- What other explanations fit the same data? (Always generate at least one alternative.)
- Are there correlations or counter-patterns in the data the authors didn't discuss?
- Does the discussion overclaim relative to what the results actually show?

### Verify the abstract
Re-read the abstract last. Does it accurately summarize what the paper actually showed? Authors sometimes overclaim in the abstract while hedging in the body — the gap between the two is informative.

## Virtual re-implementation

This is the move that distinguishes a careful third pass from a thorough second pass. Walk through the paper as if you were doing the work:

1. **State the problem in your own terms**, before peeking at how they framed it.
2. **Sketch the approach you would take**. What's the simplest thing that could work?
3. **Compare to what they did.** Where do you diverge? Why?
4. **Pick one key result** and ask: if I ran this experiment with their methodology, would I get their numbers? What would I expect to vary?
5. **Identify the missing experiment** — the one a critical reviewer would ask for that the paper doesn't include.

This exercise surfaces hidden assumptions and gaps that you'd miss on a passive read.

## What to produce

Append to the second-pass report:

```
## Strengths
[2–5 bullets. Specific contributions of evidence, methodology, framing, or insight. Not "well-written" — be specific.]

## Weaknesses and unaddressed concerns
[2–5 bullets. Specific challenges to assumptions, methods, statistics, or interpretation. Cite the section or figure where relevant. No generic complaints.]

## Hidden assumptions
[Things the authors took for granted that a careful reader should question. State each assumption and what it would take to violate it.]

## Alternative explanations for the headline result
[At least one. What else could produce the same data?]

## What I would have done differently
[The virtual re-implementation check. Where does your version diverge, and what would that change about the conclusions?]

## The missing experiment
[The one piece of evidence a critical reviewer would want that this paper doesn't provide.]

## Future work this opens up
[Genuinely interesting follow-on questions, not boilerplate.]

## Bottom line
[2–3 sentences. Is this a real contribution? What kind of reader is it for? What should they take away — and what should they not?]
```

## Calibration

After a successful third pass you should be able to:

- Reconstruct the paper's structure from memory.
- Name implicit assumptions the authors didn't flag.
- Pinpoint experimental, statistical, or analytical weaknesses by section/figure.
- Identify missing citations to relevant work (if you know the field).

If you can't do these things, do another careful read of the section you're shaky on rather than declaring done.
