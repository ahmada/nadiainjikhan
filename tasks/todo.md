# Nadia Inji Khan — Project Backlog

## Status: PAUSED (2026-04-06)
Live site: https://nadiainjikhan.pages.dev  
GitHub: https://github.com/ahmada/nadiainjikhan  
Local dev: `npm run dev` → http://localhost:4322  
Deploy: `npm run build && wrangler pages deploy dist --project-name=nadiainjikhan`

---

## ✅ Done
- [x] Astro project scaffolded from scratch
- [x] 5 design versions built (v1–v5)
- [x] Web3Forms contact form wired up (key placeholder)
- [x] GitHub repo created: `ahmada/nadiainjikhan`
- [x] Deployed to Cloudflare Pages

---

## 🔲 Backlog

### Content (needs Nadia)
- [ ] Replace all `[bracketed placeholder]` text with real content
  - Bio paragraphs (field, dissertation title, current position)
  - CV entries (positions, fellowships, awards)
  - Publications list (real titles, journals, DOIs)
  - Department name
- [ ] Real CV PDF → drop at `public/cv-nadia-inji-khan.pdf`
- [ ] Web3Forms access key → replace `YOUR_ACCESS_KEY_HERE` in all v* contact sections
  - Get key free at https://web3forms.com

### Design decisions (needs Nadia's pick)
- [ ] Pick one design from v1–v5 as the canonical version
- [ ] Once picked: make that version the index (`/`) rather than the picker

### Tech / polish
- [ ] Custom domain (e.g. nadiainjikhan.com) → add in Cloudflare Pages → Custom Domains
- [ ] Set up auto-deploy from GitHub (Cloudflare Pages → Git integration) so pushes auto-deploy
- [ ] Add Open Graph / social preview meta tags
- [ ] Add Google Scholar or ORCID link to bio
- [ ] Mobile nav review — consider a hamburger for very small screens
- [ ] Accessibility audit (focus states, ARIA labels, color contrast)
- [ ] Optional: add a "Research" or "Teaching" section

### Nice to have
- [ ] Headshot / portrait photo — would dramatically elevate all designs
- [ ] Real background photos of Islamic architecture or manuscripts (swap in for patterns)
- [ ] Animate the version picker index page
