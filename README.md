# Test, Learn & Grow Playbook

A static playbook site demonstrating proportionate, iterative public-service
improvement — and the GitHub-based content workflow behind it.

## Pages

- `index.html` — overview and the three strands (Test, Learn, Grow)
- `approach.html` — the four phases and principles
- `how-we-work.html` — day-to-day ways of working
- `methods.html` — methods & tools starter kit
- `contribute.html` — how non-technical contributors add or edit content

## How content changes work

1. A change is made on its own **branch** (not the live site).
2. A **pull request** opens, and a **preview link** is published automatically.
3. A reviewer reads the change and **approves** it.
4. Merging to `main` **publishes** to the live site; the preview is retired.

Each open PR gets its own live preview at
`…github.io/website-demo/pr-preview/pr-N/` via GitHub Actions — no third-party
service required.

## Run locally

```sh
python3 -m http.server -d . 8000
# then open http://localhost:8000
```
