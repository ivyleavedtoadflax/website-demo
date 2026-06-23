# website-demo

A tiny static site to demo the GitHub editing flow with Claude.

## How drafting works

1. Claude creates a **branch** for a new draft.
2. It opens a **pull request** with the changes.
3. A reviewer reads the diff and **approves** (or comments).
4. Merging to `main` publishes via GitHub Pages.

Live site: enabled via Settings → Pages (deploys from `main`).
