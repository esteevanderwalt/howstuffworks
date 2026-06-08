# LinkedIn posts — From GPUs to the Frontier

> Edit to taste, attach `assets/roadmap.svg` (or a screenshot of an interactive) as the image, and **keep the link in the post body** (see "Posting tips" for why the old comment-trick no longer helps). The series announcement is the main one now that all 8 are live; the per-explainer drafts are for dripping individual ones later.

---

## ⭐ Primary — series announcement (authentic, "how it all fits together")

I'm a software engineer. For about ten years I've worked alongside machine learning — using it far more than building it — and I've always loved the math underneath. What I never quite had was the *whole* picture: how it all fits together, from a `for` loop running on GPU silicon up to how a model actually writes a sentence.

I learn a topic best when I can see how every piece connects. So I built that map for myself — and figured someone else might find it useful too.

**From GPUs to the Frontier** — 8 short, interactive explainers, each one building on the last:

1 · How GPUs Work
2 · Tensors
3 · Matmul
4 · How Machines Learn
5 · PyTorch
6 · Attention
7 · Transformers & LLMs
8 · What's Next

Each starts from something a programmer already knows and connects it forward, so the eight read as one continuous thread: silicon → tensors → matmul → learning → PyTorch → attention → transformers → the frontier.

They're properly interactive — drag a learning rate down a loss curve, watch a GPU swap between warps, click a word and see what it attends to, step a model through generating tokens. Every section has a one-line plain-English summary, every claim is checked against primary sources, and the educators I learned from are credited throughout.

I built it mostly to satisfy my own curiosity. Sharing it in case it helps you join the dots too — it's free, no signup:
👉 https://esteevanderwalt.github.io/howstuffworks/

If there's a piece you'd like to see explained, or something you think I got wrong, I'd genuinely love to hear it. Happy to keep going if there's interest.

#MachineLearning #AI #LearningInPublic #LLM #GPU

---

## Shorter variant

I'm a software engineer who's worked alongside ML for ~10 years — more a user of it than a builder — and I love the math behind it. I'd just never seen the whole thing laid out as one connected picture, from GPU silicon up to how a model writes a sentence.

I learn best when I can see how the pieces fit, so I built that map for myself: **From GPUs to the Frontier**, 8 short interactive explainers, each building on the last.

Drag a loss curve, watch a GPU swap warps, click through attention, step a model through generating text. Plain-English summaries, every claim sourced, credit to everyone I learned from.

Built it out of curiosity; sharing in case it's useful — it's all here, free: https://esteevanderwalt.github.io/howstuffworks/ — and if there's something you'd like explained next, tell me.

#MachineLearning #AI #LearningInPublic #LLM

---

## Per-explainer drafts (for dripping one at a time)

If you'd rather post weekly than all at once, release one explainer at a time. Template for any single one — same honest voice:

> I wanted to really see how [TOPIC] fits into the bigger AI picture — not just use it. So here's #[N] in a little series I'm building: **[TITLE]**.
>
> It starts from [familiar thing] and connects forward to [the payoff], interactively — [one concrete thing you can play with]. Plain-English summaries, sourced, with credit to [who I learned it from].
>
> Read it here 👉 [explainer URL]. #[N] of 8, From GPUs to the Frontier — what would you want explained next?
>
> #MachineLearning #AI #LearningInPublic

Explainer URLs:
`https://esteevanderwalt.github.io/howstuffworks/content/gpu-to-frontier/NN-name.html`
Home (all 8): `https://esteevanderwalt.github.io/howstuffworks/`

---

## Posting tips

- **Image stops the scroll.** Attach `assets/roadmap.svg` (the 8-step roadmap) or a clean screenshot of one interactive (the attention sentence and the gradient-descent ball both look great).
- **First two lines are all most people see** before "…see more" — make sure the hook lands there.
- **Link placement (2026 reality):** the old "link in the first comment" trick mostly stopped working — LinkedIn now penalises external links *whether they're in the post (~60% less reach) or the first comment (suppressed even harder)*, and it detects funnel-to-comment intent. So don't over-optimise it. Lead with native value; then **put the link in the post body** — everyone who sees the post can click, and it's the more honest placement. (If you're chasing raw reach over clicks, post with no link and add it in a comment once it gets traction — but the upside is small now.)
- **Tag the people you credit** (e.g. Abhinav Upadhyay, and others per explainer) — good practice, often earns a reshare.
- **Replies > likes.** Answer early comments fast — comment velocity drives reach more than anything else, and the closing invitation is there to spark them.
