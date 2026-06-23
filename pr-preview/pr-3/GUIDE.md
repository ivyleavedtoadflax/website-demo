# A simple guide: managing a website with GitHub

This is a plain-English guide to what's been built and how adding or changing
content works — written for people who don't use GitHub day to day.

## What this is

A small example website — a "Test, Learn & Grow" playbook — that lives on
**GitHub** and publishes itself to the web automatically. All the content is
AI-generated for the demo; the point is to show *how the website is managed*,
not the words themselves.

- **Live site:** https://ivyleavedtoadflax.github.io/website-demo/
- It has several pages (Home, The approach, How we work, Methods & tools,
  Case studies, Contribute), so you can see what a multi-section site looks like.

## The big idea

The website has two states:

- **Live** — what the public sees. This only changes when someone approves a change.
- **Drafts** — proposed changes that are *not yet live*. Anyone can work on a draft
  without any risk of breaking the real site.

A draft only becomes live after a person reviews and approves it.

## How a change gets made

You never need to touch code or know the technical steps. In plain terms:

1. **You describe the change.** For example: *"Add a page about stakeholder
   mapping"* or *"Make the homepage intro simpler."* (AI does the actual editing.)
2. **A draft is created.** The change is prepared separately from the live site,
   so nothing the public sees changes yet.
3. **You get a preview link.** The draft is published to its own temporary web
   address. You click it and see the change as a real web page — not as code.
4. **Someone reviews it.** A reviewer reads the change, asks for tweaks, or approves.
5. **It goes live.** Once approved, the draft is published to the real site
   automatically, and the temporary preview is removed.

```
  Describe  →  Draft created  →  Preview link  →  Review  →  Approve  →  Live
   (you)         (AI)            (see it live)    (person)            (automatic)
```

## Why it's done this way

- **The live site can't break by accident.** Drafts are kept separate until approved.
- **Every change is visible.** You can always see exactly what changed and who changed it.
- **Anything can be undone.** Because every change is recorded, mistakes are easy to roll back.
- **Automatic checks** can catch common errors (like a broken link) before a change
  goes live — without needing a person to spot them.

## What you've seen in this demo

- A multi-page website, live on the web.
- A new section ("Case studies") proposed as a **draft** — with its own preview link —
  waiting for approval before going live.
- The whole flow happening through GitHub, with no third-party service needed.

## The one role worth having

A single person who's comfortable reviewing changes (a content lead, say) is enough
to keep quality high. They don't write the code — they read the preview, check it
reads well, and approve. That's the safeguard against anything odd slipping through.
