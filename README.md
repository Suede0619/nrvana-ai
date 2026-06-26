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
│   │   ├── personal-cortex.astro Personal Cortex Setup — $2,500
│   │   ├── diagnostic.astro     Team Review — $2,500
│   │   ├── sprints.astro        Done-for-You Setup — $5k–$15k
│   │   ├── governance.astro     Safety & Quality Setup — $4k–$8k
│   │   └── retainers.astro      Monthly Support (individual + team)
│   ├── method.astro             (stub — full method page coming)
│   ├── about.astro              Stuart Paul · Founder
│   ├── memos/
│   │   ├── index.astro          Memos index — published + upcoming
│   │   └── ai-memory.astro      "Why your AI keeps forgetting you" (published)
│   ├── contact.astro            Two doorways: book / say hi
│   └── legal/                   Privacy + Terms (stubs)
├── styles/global.css            Tailwind + brand tokens — Audo typography (Playfair/Freight
│                                 display + Inter/Suisse body) on Rivian colors (off-white +
│                                 forest greens, Rivian-green accent, pill buttons, green-glow shadow)
└── content/                     (reserved for future MDX essays)
```

## Brand rules

The operating brand/voice/positioning lives in `consultAI/brand/`. Three rules to remember:

1. **Thesis is immovable:** *Accelerate humans with AI. Never replace them.*
2. **Three named concepts only:** Acceleration · Compounding · Personal Cortex.
3. **Never link to or credit external research sources** in public copy.

See `AGENTS.md` for the full instructions any AI assistant should follow when editing this repo.

## License

Proprietary. © Nrvana / Stuart Paul.
