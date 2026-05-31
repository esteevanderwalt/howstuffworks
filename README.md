# Explainers

Visual, interactive explainers for programmers learning how things work under the hood — built one concept at a time, each grounded in primary sources and crediting the educators who inspired it.

I come from a programming background and I'm learning in the open. Each **series** takes a topic from the ground up: start from something you already understand (a `for` loop, an array, a function) and show the leap to the new idea — without dumbing down the technical detail.

**🔗 Live: https://esteevanderwalt.github.io/howstuffworks/**

## Series

| Series | About | Status |
|--------|-------|--------|
| [**From GPUs to the Frontier**](./content/gpu-to-frontier/) | 8 explainers taking you from low-level GPU hardware → tensors → PyTorch → transformers → what's next | 🟢 1 of 8 live |
| *(more to come)* | | |

## How it's organised

Each series lives in its own folder under `content/`, holding that series' explainers, landing page, roadmap, and assets. Shared, repo-wide files live at the root.

```
.
├── index.html              ← top-level landing (links to every series)
├── README.md               ← you are here
├── LICENSE                 ← MIT (code & visuals only; see notes)
├── template.html           ← shared: copy this to start a new explainer
├── STYLE.md                ← shared: the explainer formula
└── content/
    └── gpu-to-frontier/    ← a series
        ├── index.html          ← series landing
        ├── README.md           ← series index
        ├── linkedin-post.md
        ├── assets/roadmap.svg
        └── 01-how-gpus-work.html
```

## How the explainers are built

Every explainer is a **single, self-contained HTML file** — no build step, no dependencies, no framework. That keeps each one portable (shareable as one file) and the whole repo easy to host on GitHub Pages. Start a new one by copying [`template.html`](./template.html); the recipe is in [`STYLE.md`](./STYLE.md).

## Hosting

Enable GitHub Pages (Settings → Pages → *Deploy from a branch* → `main` / `/root`). The top-level landing is served at `https://esteevanderwalt.github.io/howstuffworks/`, and each series at `…/content/<series>/`.

## Credit & sourcing

Each explainer is an **original synthesis grounded in primary sources** — every spec and concept is verified against canonical references (official documentation, foundational textbooks, peer-reviewed papers), cited in full at the end of each piece. The writing, structure, diagrams, and interactives are my own.

Where another explainer or talk inspired one, it's credited generously in that piece's "References & further reading" — **go read and support them.**

## License

Code and visualizations are MIT-licensed (see [`LICENSE`](./LICENSE)). This does **not** cover the third-party articles, figures, or ideas referenced in each explainer — those belong to their authors and are referenced under fair-use commentary/education.

---

*Made by Estee van der Walt · learning in public, one explainer at a time.*
