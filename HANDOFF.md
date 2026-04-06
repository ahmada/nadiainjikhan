# Handoff — Nadia Inji Khan Website

**Last session:** 2026-04-06  
**Status:** Live, paused — waiting on content and design decision from Nadia

---

## What was built

A minimalist academic website for Dr. Nadia Inji Khan (PhD, University of Chicago, Arabic & Islamic Studies). Built with Astro, deployed to Cloudflare Pages.

**Five design versions**, each with a distinct visual language based on Islamic geometric patterns:

| Version | Name | Vibe |
|---------|------|------|
| `/v1` | Alchemy | Near-black, tiled gold 8-pointed star, Cinzel serif |
| `/v2` | Andalus | Cobalt blue hero, diamond tile pattern, Josefin Sans |
| `/v3` | Manuscript | Warm parchment, arabesque circles, Cormorant Garamond |
| `/v4` | Minaret | White/emerald, wireframe star ornament, DM Serif |
| `/v5` | Observatory | Animated tri-ring star, Italiana, grain, scroll reveals ← best |

All 5 versions have: Bio, CV (download + HTML), Publications, Web3Forms contact.

---

## Live links
- **Picker:** https://nadiainjikhan.pages.dev  
- **Best version:** https://nadiainjikhan.pages.dev/v5  
- **GitHub:** https://github.com/ahmada/nadiainjikhan

---

## What's needed before launch

1. **Nadia picks a design** (v1–v5)
2. **Content** — all bracketed placeholder text needs to be filled in
3. **Web3Forms key** — free at https://web3forms.com → replace `YOUR_ACCESS_KEY_HERE` in the chosen version's contact section
4. **CV PDF** → drop the real file at `public/cv-nadia-inji-khan.pdf`
5. **Custom domain** (optional) → add in Cloudflare Pages dashboard

---

## Key files
- Designs: `src/pages/v1.astro` → `v5.astro`
- Picker: `src/pages/index.astro`
- Shared base: `src/layouts/BaseLayout.astro`
- Old components (unused in v1–v5): `src/components/`
- Backlog: `tasks/todo.md`

---

## Next session checklist
1. Read `tasks/todo.md`
2. Ask which design Nadia chose
3. Fill in content from Nadia
4. Wire up Web3Forms key
5. Point index to the chosen version
