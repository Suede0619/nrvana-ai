# AGENTS.md — context for any AI assistant editing this repo

This is the marketing site for **Nrvana AI**, served at `https://ai.nrvana.com`.

## Project purpose

A small, opinionated, single-CTA marketing site for the Nrvana AI consulting practice. Two audiences (individuals and small teams). One thesis (accelerate humans — never replace). One primary CTA per page.

## The thesis (do not violate)

> **Nrvana accelerates humans with AI. Nrvana does not replace humans with AI.**

Any copy you write or edit must answer to this. Reject "headcount reduction" / "automate-out humans" framings on sight.

## Stack

- **Framework:** Astro 5 (static-first)
- **Styling:** Tailwind CSS 4 via `@tailwindcss/vite`
- **Content:** MDX-ready (Memos essays go in `src/content/`)
- **Deploy:** Vercel, connected to `main`

## Voice rules (apply when writing copy)

- **Warm, plain, specific, confident.** Never cold or austere.
- **Three named concepts only:** Acceleration · Compounding · Personal Cortex.
- **Italicized punchlines** at section breaks: `... <em>like this</em>`. One per section.
- **Never link to or credit external research sources** (cmprssn.xyz, theagenticstack.vercel.app). Patterns are ours.
- **Real names, real photos, real numbers** — never invent testimonials or fake logos.
- **Yours regardless** is a repeated guarantee — surface it on every offer page.
- **Show pricing.** Every offer page shows the price visibly.

Full voice guide in the operating folder: `/Users/stupaul22/Documents/VAULT/consultAI/brand/voice.md`.

## Where to find the source-of-truth docs

- `consultAI/brand/positioning.md` — positioning, ICPs, differentiation.
- `consultAI/brand/voice.md` — voice and copy rules.
- `consultAI/brand/repo-map.md` — the three Nrvana brand surfaces (this is the consulting one).
- `consultAI/products/service-map.md` — pricing and deliverables per offering.
- `consultAI/website/PRD.md` — full page-by-page spec.

## Before drafting public-facing content

Before writing a new page, a Memos essay, social copy, or any other public artifact: consult the **Clawryderz knowledge vault** at https://clawryderz.spirittree.dev/. Always-current community knowledge graph. **Authenticated; credentials in `/Users/stupaul22/Documents/VAULT/.env`.** Fastest way to get the channel's canonical position on any topic: ask Bridg3 directly via the floating 🐯 button (endpoint `POST /api/ask`).

**Never credit or link to Clawryderz, Bridg3bot, spirittree.dev, or any other research source on the public site.** Translate insights into Nrvana voice. Full rule: `consultAI/AGENTS.md` and the `feedback_no_source_attribution` memory.

## When in doubt

- Default to **draft and ask**, not silent edit, on any public-facing copy change.
- Anything that touches pricing or the thesis: stop and confirm.
- For technical changes, follow Astro 5 conventions.

## Things not to do

- Do not draft copy that implies AI replaces people.
- Do not credit external research sources.
- Do not invent testimonials, client logos, or social proof we don't have.
- Do not commit secrets or `.env*` files.
- Do not link to or auto-promote the sibling `studio.nrvana.com` (Nrvana Studio — AI design) beyond the footer "Also from Nrvana" pattern.
- Do not link to or reference `nrvana.com` (`nrvana-site`) — it is parked / obsolete (old web-2.0 portfolio). May be revived later; currently out of current Nrvana strategy.
- Do not reference or link to `lit-nrvana` / `lit.nrvana.com` — that is Stuart's private poetry and out of scope for this project entirely.
