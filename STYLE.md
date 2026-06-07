# The Explainer Formula

This is the recipe behind every explainer in the series. Following it keeps them consistent, and consistency is what makes the series feel like a series. Start from [`template.html`](./template.html) and fill in the blanks.

## The core principle

> **Start from what the reader already knows, then show the leap.**

The reader is a working programmer, not a beginner and not a specialist. They know loops, functions, arrays, types. They do *not* know your topic's jargon — and worse, they may carry a mental model that actively misleads them (e.g. CPU threads vs GPU threads). Open every explainer from familiar ground, name any misleading prior knowledge head-on, then build up.

## The five rules

1. **Open from the familiar.** The first section ("Start here") anchors the whole piece in code or an idea the reader owns. Show the smallest possible leap to the new idea, then frame everything that follows as the answer to *one* question.

2. **Sections are answers, not topics.** Each section should answer a question the previous one raised. If a section doesn't hand off cleanly to the next, it's in the wrong place — or doesn't belong. This chain is also how you know the series is complete: the links connect end to end.

3. **Every section opens with "In plain words."** One green callout, one sentence, high-school-level. The reader should be able to skim *only* the plain-words lines and still get the gist. The technical depth lives in the prose below it — never remove the depth, just lead with the plain version.

4. **Show, don't just tell — make it interactive.** Where a concept has a knob, a before/after, or a mapping, build a small interactive (a toggle, a slider, a clickable diagram). One good interactive beats three paragraphs.

5. **Credit is not optional.** Name the source you're adapting in the hero *and* the footer, link it, and spell out what came from it vs what you added. Send readers to the original.

## The standard skeleton

```
Hero            title · one-line promise · TOC chips · source line
▶ Start here    familiar ground → the leap → the one question
1..N Sections   each: In-plain-words → prose/diagram/interactive → analogy/key callout
✓ Recap         the whole picture in one paragraph + a visual arc (.rcap-flow) + hand-off to the next explainer
Credit footer   source attribution + what's adapted vs added + your byline
📖 Glossary      every bolded term, searchable, reachable from anywhere
```

## Reusable building blocks (already in the template)

| Class | Use it for |
|-------|-----------|
| `.plain` | The green "In plain words" one-liner at the top of each section |
| `.analogy` | A concrete everyday comparison (purple) |
| `.key` | The one thing to remember / a watch-out (amber) |
| `.codecard` + `pre.code` | Annotated code snippets with light syntax highlighting |
| `.stage` + `.toggle` | A two-state interactive demo (good case vs costly case) |
| `.vs` | A side-by-side comparison table (e.g. CPU vs GPU) |
| `.rcap-flow` | The recap's visual arc — the explainer's key steps as connected nodes (`.hl` = pivotal, `.go` = payoff) |
| Glossary drawer | Edit only the `glossary` array in the script; the mechanics are shared |

## Writing checklist

- [ ] Title states a promise, not just a topic.
- [ ] "Start here" opens from something the reader already knows.
- [ ] Any misleading prior knowledge is named and corrected early.
- [ ] Every section has an "In plain words" line.
- [ ] Every bolded term is in the glossary.
- [ ] At least one interactive that teaches, not decorates.
- [ ] Numbers and claims are checked against the source.
- [ ] Source is credited in hero + footer, with what's adapted vs added.
- [ ] Reference links resolve and are current (vendor docs — NVIDIA, PyTorch, Google — restructure every year or two; re-check the back-catalogue's links at each launch, not just the new one's).
- [ ] Recap hands off to the next explainer.
- [ ] File saved as `content/<series>/NN-kebab-title.html`; row added to the series README table.

## Tone

Warm, direct, concise. Short sentences. Define before you use. Analogies must be concrete (a factory, a parking garage, a rowing crew — not "imagine a system that..."). Never sacrifice technical accuracy to sound simple; lead with the simple version and let the depth follow.
