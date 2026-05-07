---
name: reading-academic-papers
description: Read, summarize, and critique academic papers using a multi-pass method synthesized from Keshav's three-pass approach, the BIG QUESTION framework, and the 5 C's. Use this skill whenever the user shares an academic paper (PDF, arXiv link, journal URL, or pasted text), asks to "read", "summarize", "review", "skim", "critique", or "make sense of" a paper, asks "is this paper any good?", or wants to do a literature survey — even if they don't explicitly say "use the paper-reading skill". Default behavior is a fast first pass; deeper passes happen on request.
---

# Reading Academic Papers

## Why this skill exists

Researchers spend hundreds of hours a year reading papers, but reading a paper is not like reading a book. Plowing through cover-to-cover wastes time and leaves you confused. The methods bundled here — Keshav's three-pass approach, Klein's six stages, Hanson and McNamee's breadth-then-depth, Massey's "main point first" rule, and Raff's BIG-question framework — all converge on the same insight: read in passes, with a decision point after each pass about whether to go deeper.

The user's time is the scarce resource. Most papers don't deserve more than a first pass.

## The default: first pass

Unless the user has already signaled they want depth (see "When to skip the offer" below), do **only the first pass** and offer the deeper passes at the end.

A first pass is a bird's-eye view, not comprehension of every detail. For a human it takes 5–10 minutes; for you it's a single careful read of the paper's skeleton.

### What to read in the first pass

In this order:

1. **Title, abstract, and introduction** — carefully.
2. **Section and sub-section headings only** — ignore the body.
3. **Conclusion** — carefully.
4. **References** — a glance, noting any you recognize or that look load-bearing.

If a single key results figure is obvious, peek at it to see what the authors think the headline is. Otherwise leave figures for pass 2.

### Pre-read context

Before the first pass, capture (one line each):

- **Who wrote it?** Author affiliations — university lab, industry, advocacy group?
- **Where was it published?** Conference / journal name and year. Peer-reviewed?
- **When?** Could it be superseded?

Don't dwell on this. It's context, not a verdict — but it shapes how skeptically to read.

## What to produce: the first-pass report

Use this exact structure. Adapt headings only if the genre demands it (e.g., a position paper has no "results"); otherwise keep it consistent so the user gets scannable, predictable output across papers.

```
# [Paper title]
**Authors / venue / year:** [...]

## Pre-read context
[1–2 lines: who, where, when. Any obvious credibility signals.]

## The BIG question
[The overarching problem the *field* is trying to solve, that this paper sits inside. One sentence.]

## What this paper specifically asks
[The concrete question(s) or hypothesis this paper investigates. Bullets if multiple.]

## Approach in one paragraph
[How they tried to answer the specific question. Methodology in plain terms.]

## Headline contribution
[What they claim is new. One or two bullets.]

## The 5 C's
- **Category:** [Measurement? Theory? Survey? Position? System description? Empirical study?]
- **Context:** [What other work / theoretical bases does it sit alongside? Related papers if you can name them.]
- **Correctness:** [Do the assumptions look reasonable on a first read? Anything that already smells off?]
- **Contributions:** [Restate — in your own words — what's new.]
- **Clarity:** [Is the paper well-written and well-structured?]

## My read
[2–3 sentences: would a careful reader benefit from a second pass on this paper, and for whom? E.g., "Worth a second pass if you work on X. Skip if you're looking for Y."]

## Want me to go deeper?
I can do:
- **Second pass** — grasp the content with supporting evidence (~the depth you'd want for a paper outside your specialty but in your field).
- **Third pass** — challenge every assumption, virtually re-implement, full critique (the depth you'd want as a reviewer).
- **Literature survey** — find and triage related papers in this area.

Just say which.
```

Always end with the "Want me to go deeper?" offer. It makes the multi-pass nature visible — the user shouldn't have to know the framework to use it.

## When to skip the offer / go deeper without asking

Read the user's intent. Skip the offer (and just go deeper) when their request already implies depth:

- **"Review this paper" / "write me a review"** → third pass.
- **"Critique" / "what's wrong with this?" / "is this paper any good?" / "tear it apart"** → third pass.
- **"Help me understand this" / "explain this paper"** → second pass.
- **"I'm doing a lit review on X" / "what's the state of the art in Y?"** → literature survey workflow.
- **"Just summarize" / "what does it say?" / "tldr"** → first pass is sufficient. Skip the offer too — they want it brief.

When in doubt, do the first pass and offer.

## Going deeper

When the user asks for more depth, read the relevant reference file and follow it:

- **Second pass** (grasp the content) → `references/pass-2-content.md`
- **Third pass** (deep critique, virtual re-implementation) → `references/pass-3-deep-critique.md`
- **Literature survey** (read tens of papers in a field) → `references/literature-survey.md`

Do not pre-load these files. They exist to keep this SKILL.md lean — load them only when the user has signaled they want that depth.

## Working with PDFs, URLs, and pasted text

- **Local PDF:** Use the Read tool — it handles PDFs natively. For long papers (>10 pages), pass `pages` to read sections selectively (e.g., `pages: "1-3"` for intro, then a separate read for the conclusion) rather than dumping the whole thing into context.
- **URL (arXiv, journal, preprint server):** Fetch it. Many publisher pages return only the abstract (paywalled body) — if so, ask the user for the PDF rather than guessing at the content.
- **Pasted text:** Work with what's there. If sections are clearly missing (e.g., no methods section), say so in the report rather than fabricating.

## What not to do

- **Don't try to understand every word on the first pass.** If a sentence is dense or full of unfamiliar jargon, keep going — later sections often clarify earlier ones. Massey's rule: identify the main point, strengths, and weaknesses *as the author presented them* before forming your own opinions, or you'll conflate the two.
- **Don't insert your own critique into the first-pass report.** Save that for pass 3. The first-pass report is what the *authors* claim, plus light flags for things that are obviously off (e.g., no error bars on the headline graph, undefined acronyms in the abstract).
- **Don't write a generic "the paper discusses X, Y, and Z" summary.** Use the structured template above. Predictability across papers is part of the value.
- **Don't skip the "Want me to go deeper?" offer** unless the user's intent already implied a specific depth. The offer is what makes this skill different from "summarize this paper".
