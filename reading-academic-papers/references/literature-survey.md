# Literature Survey: Reading Tens of Papers in an Unfamiliar Field

Adapted from Keshav's three-step survey method. Use when the user asks for a literature survey, "what's the state of the art in X?", "ramp me up on Y", or wants to identify the key papers in a field they don't know.

## The three-step method

### Step 1: Find an entry point
- Use Google Scholar (or the user's preferred academic search engine — Semantic Scholar, arXiv, ACM DL, PubMed depending on field) with well-chosen keywords.
- Find **3–5 recent papers** in the area.
- Do a **first pass** on each (see main `SKILL.md` for the first-pass procedure).
- Read the related-work / background section of each. You'll get thumbnail summaries of the recent landscape.
- **If you find a recent survey paper** cited by multiple of these — stop. Read the survey. You're done.

### Step 2: Find the key papers and key researchers
- In the bibliographies of your starting set, look for:
  - **Shared citations** — papers cited by multiple of your starting set. These are the field's anchors.
  - **Repeated author names** — the people whose names show up across multiple bibliographies are the field's central figures.
- Download the key papers; set them aside for later reading.
- Visit the websites (or Google Scholar profiles) of the key researchers. Where do they publish recently? That tells you the **top venues** in this field.

### Step 3: Mine the top venues
- Browse recent proceedings of those top venues (last 2–3 years).
- Quickly scan titles and abstracts for relevance — a brief first-pass on each candidate.
- These, plus the key papers from step 2, form your **first version of the survey**.
- Make **two passes** through these papers (first + second from `references/pass-2-content.md`).
- If they all cite a key paper you haven't found, get it and read it. Iterate.

## What to produce

Deliver this structured survey:

```
# Literature survey: [topic]

## Scope and search strategy
[Keywords used, venues consulted, date range, anything excluded.]

## The landscape
[2–3 paragraphs: what the field is trying to solve, the major sub-threads or schools of thought, where the action is right now, what's contested.]

## Key papers (must-reads)
[5–10 papers with one-line annotations explaining why each matters. Mark which you've read at first-pass vs. second-pass depth, and which you've only seen referenced.]

## Key researchers / groups
[3–5 names with affiliations and what they're known for. Note if they disagree with each other on substantive points — that's useful structure.]

## Top venues
[Where this work appears — conferences, journals, workshops.]

## Open questions
[What the field doesn't yet know, based on what the recent papers themselves identify as open problems. Cite the papers that flag each open question.]

## Recommended next reads
[If the user wants to go further, what to pick up next and why.]
```

## When to stop

A literature survey is iterative; it's never "complete". Stop when:

- New papers stop introducing new key references.
- You can name the major positions in the debate without checking notes.
- The user has what they need to act — that's the actual goal, not exhaustiveness.

## Caveats for this skill

- **Be honest about what you've actually read** vs. what you're summarizing from abstracts or related-work sections. The survey is more useful if it distinguishes "I read this" from "this paper was cited a lot, here's what others say about it".
- **Flag if your training data is stale.** If the user asks about state-of-the-art in a fast-moving field, the most recent work may be after your knowledge cutoff. Say so and suggest the user check recent venues directly or hand you specific papers.
- **Ask the user for venue preferences** if it's not obvious from the topic. Different communities (e.g., ML systems vs. ML theory) publish in different places, and the right venue list depends on the user's actual research question.
