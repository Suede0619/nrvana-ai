# nrvana-ai

Marketing site for **Nrvana AI** — AI consulting that accelerates humans (not replaces them) for individuals and small businesses.

**Live at:** `https://ai.nrvana.com` (deployed via Vercel)
**Stack:** Astro 5 · Tailwind CSS 4 · MDX
**Operating folder:** `/Users/stupaul22/Documents/VAULT/consultAI/` (private; not in this repo)

## Quickstart

```bash
npm install
npm run dev
```

Then open [http://localhost:4321](http://localhost:4321).

## Build & deploy

Pushing to `main` triggers a Vercel production deploy. Preview deploys run on every PR.

```bash
npm run build      # local production build to ./dist
npm run preview    # serve the built dist locally
```

## Structure

```
src/
├── layouts/BaseLayout.astro     Site chrome (head, nav, footer)
├── components/                  Nav, Footer, shared bits
├── pages/                       Route per file
│   ├── index.astro              Home — hero + thesis + 2 doorways + stats + CTA
│   ├── services/
│   │   ├── index.astro          Services overview (the ladder + offerings table)
│   │   ├── snapshot.astro       Acceleration Snapshot — $450
│   │   ├── personal-cortex.astro (stub)
│   │   ├── diagnostic.astro     (stub)
│   │   ├── sprints.astro        (stub)
│   │   ├── governance.astro     (stub)
│   │   └── retainers.astro      (stub)
│   ├── method.astro             (stub — full method page coming)
│   ├── about.astro              Stuart Paul · Founder
│   ├── memos/index.astro  Memos index (essays coming)
│   ├── contact.astro            Two doorways: book / say hi
│   └── legal/                   Privacy + Terms (stubs)
├── styles/global.css            Tailwind + brand tokens
└── content/                     (reserved for MDX essays)
```

## Brand rules

The operating brand/voice/positioning lives in `consultAI/brand/`. Three rules to remember:

1. **Thesis is immovable:** *Accelerate humans with AI. Never replace them.*
2. **Three named concepts only:** Acceleration · Compounding · Personal Cortex.
3. **Never link to or credit external research sources** in public copy.

See `AGENTS.md` for the full instructions any AI assistant should follow when editing this repo.

## License

Proprietary. © Nrvana / Stuart Paul.
