# Internet Doctor

Understand your Internet. Not just numbers — a living, visual story of every packet you send.

A single-page, client-side connection diagnostic. It runs a battery of in-browser network checks, narrates them live as a step-by-step "diagnosis," then renders the results as a score ring, a persona summary, a visual journey of your traffic, and a readiness verdict for common use cases (streaming, video calls, gaming, etc.) — all with zero backend and zero data leaving the browser.

## Files

- `index.html` — current production version (deployed to Vercel).
- `index-v2.html`, `index-v3.html` — later visual/UX iterations (v3 = "Heat" theme), kept for comparison/rollback.
- `internet-doctor.html` — original prototype.

Only `index.html` is served in production; the others are working drafts.

## Stack

Vanilla HTML/CSS/JS, no build step, no framework, no server-side code. Fonts via Google Fonts CDN.

## Run locally

Just open `index.html` in a browser, or serve the folder statically:

```bash
npx serve .
```

## Deploy

```bash
vercel --prod
```
