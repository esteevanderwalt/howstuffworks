# LinkedIn launch post — Explainer #1

> Edit the bracketed bits, drop in your link, and attach `assets/roadmap.svg` (or a screenshot of the explainer) as the image.

---

## Primary version

I'm a programmer learning AI/ML — so I'm starting a series of visual explainers, in public, one concept at a time.

**#1 is live: How GPUs Work.** 🧵

I never really understood *why* GPUs run AI. I knew "they're parallel," but couldn't have told you what a thread, a warp, or occupancy actually was.

So I built the explainer I wish I'd had. It starts from something every programmer already knows — a `for` loop adding two arrays — and shows the exact leap to GPU thinking: if every iteration is independent, why run them in order? Launch a million tiny threads instead.

From there it builds up, each section answering the question the last one raised:
→ why thousands of slow cores beat a few fast ones
→ how code actually runs (grids, blocks, warps) — with the real CUDA
→ the two things that make GPU code fast or slow (divergence + memory coalescing)
→ and finally: *why this is the engine of modern AI*

It's interactive — you can drag the occupancy slider, watch warps swap, and click through a matrix multiply — with an "in plain words" line on every section and a searchable glossary.

It's grounded in NVIDIA's own documentation and the classic Hwu et al. textbook — and big thanks to **Abhinav Upadhyay**, whose excellent primer helped inspire it. Full references are inside; go read them.

👉 https://esteevanderwalt.github.io/howstuffworks/content/gpu-to-frontier/01-how-gpus-work.html

This is #1 of 8, going from GPUs → tensors → PyTorch → transformers → what's next. Follow along if you're a dev trying to actually understand what's under the hood.

What should I make clearer in the next one?

#AI #MachineLearning #GPU #CUDA #LearningInPublic #SoftwareEngineering

---

## Shorter version (if you prefer punchy)

I'm a developer learning AI/ML in public — starting with the stuff under the hood.

**Explainer #1: How GPUs Work.**

It starts from a plain `for` loop and builds — interactively — to why GPUs are the engine of modern AI. Warps, occupancy, memory coalescing, real CUDA, a clickable matrix multiply. Every section has a one-line "plain words" summary.

Grounded in NVIDIA's docs + the Hwu textbook, and inspired by Abhinav Upadhyay's superb primer (all linked inside — go read them).

#1 of 8: GPUs → tensors → PyTorch → transformers → what's next.

👉 https://esteevanderwalt.github.io/howstuffworks/content/gpu-to-frontier/01-how-gpus-work.html

#AI #MachineLearning #GPU #LearningInPublic

---

## Posting tips

- **Image matters most.** Attach the roadmap graphic or a clean screenshot of an interactive section — it's what stops the scroll.
- **Put the link in the first comment** if you find reach drops with an outbound link in the body; mention "link in comments" in the post.
- **Tag the source author** (Abhinav Upadhyay) if he's on LinkedIn — credit is good practice and often earns a reshare.
- **End with a question** (already included) to invite comments, which boosts reach.
