# Second Pass: Grasp the Content

Goal: understand the paper's content well enough that you could summarize it, with supporting evidence, to a colleague who hasn't read it. Not yet a critique — that's pass 3.

For a human, a second pass takes about an hour. You're now reading the body of the paper, but ignoring proofs and the most technical derivations.

## What to do

1. **Read every section in full**, but skim proofs, dense derivations, and appendices unless they're load-bearing.
2. **Examine every figure and table carefully**, especially graphs. Common things that separate careful work from rushed work:
   - Are the axes labeled? Logarithmic or linear?
   - Are error bars or confidence intervals shown?
   - Does the figure actually support the claim it's cited for, or is the caption oversold?
   - Is the y-axis truncated to make a small effect look big?
3. **Look up unfamiliar terms** when they're load-bearing for the argument. Skip jargon that's incidental.
4. **Mark interesting references** for later reading — papers cited multiple times, or in the related-work section as the direct comparisons.
5. **Construct your own example** for any new definition or technique. If you can produce a worked instance the paper didn't give, you've understood it. If you can't, you haven't — flag it.
6. **Take running notes** as you go: definitions, surprising claims, points of confusion, your own questions.

## What to produce

Append to (or replace, if the user wants a single document) the first-pass report with these sections:

```
## Methods in detail
[Per major experiment / analysis: what they did, what they measured, what they controlled for. If the protocol is complex, sketch a brief diagram or step-list — it forces you to actually understand the procedure rather than just paraphrasing the prose.]

## Results
[Per major result: what the data shows. Just the observations — not what they mean. This separation matters: it lets you check the authors' interpretation against your own.]

## Authors' interpretation
[What the authors say their results mean. Their framing of the contribution. Keep this distinct from the previous section.]

## Definitions and terms worth remembering
[New terminology the paper introduced or used in a specific way. Include the definition.]

## Notes for further reading
[2–5 references from the bibliography that are worth chasing if you want depth on this topic. Say briefly why each one is worth reading.]

## Confidence check
[Anything in the paper you'd flag as not-fully-understood. Be honest — this list tells the user where to push you in pass 3, or where to look up background themselves.]
```

## Stopping point

After the second pass, you should be able to explain the paper's main thrust, with supporting evidence, without re-reading. If you can't, the issue is one of:

- **Subject matter is new** — read background material (or a textbook chapter, or a survey paper) first, then come back.
- **Authors used a technique you don't recognize** — look it up before continuing.
- **The paper itself is poorly written** — set it aside, or persevere into pass 3 if it's important enough.

A second pass is the right depth for a paper in your field but outside your immediate specialty. Go to the third pass only if the user wants to review, replicate, build on, or formally critique the work.

## At the end, offer the third pass

End with:

> Want me to go to a third pass? That's a deep critique — challenging every assumption, looking for hidden failings, and mentally re-implementing the work to see where my version would diverge from theirs. Useful if you're reviewing this paper or planning to build on it.
