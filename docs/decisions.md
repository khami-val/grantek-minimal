# Decision log

| Date | Decision | Why | Alternatives rejected |
|---|---|---|---|
| 2026-10-22 | Languages: UA default + EN; no RU pages | Language law, reputation, UA search share | UA + RU + EN |
| 2026-10-22 | Stack: Astro static + Keystatic + Cloudflare Pages | Speed budget, zero hosting cost, owner keeps code | WordPress rebuild, Next.js on Vercel |
| 2026-10-22 | Accent color cobalt #2F5BFF (concept) | Separates from green "eco" packaging brands | Safety orange, acid lime |
| 2026-10-30 | No public prices; RFQ + dealer price list on request | All named clients are resellers; public prices would undercut them | Retail prices on site |
| 2026-10-30 | Unverified claims («єдина в Україні», «у 80 разів краще за скло») not published | No test reports | Publish as given |
| 2026-10-30 | Third segment «Агро» (greenhouse film) | Niche with no competitor pages | Two segments only |
| 2026-10-31 | Catalog: thickness filter replaced by text search | Filter hid 16 of 20 products (no thickness data); units differ by family (мкм, мм, Ø) | Keep filter; show products without data in every range |
| 2026-10-31 | RFQ: quantity optional; dealer and tender requests without products; consent checkbox | Buyers who don't know volume or need a price list dropped out at step 1; personal data needs consent | Required qty; separate dealer form |
| 2026-10-31 | Product card gets its own address `#p-<id>`, Back closes it | Shareable links for buyers; Back no longer leaves the site. Full product pages come with Astro | Modal without URL |
| 2026-11-02 | Minimal design variant on a separate branch (`claude/project-thread-3k2cpq`) | Owner asked for the simplest possible design to compare with v3; same catalog and copy, logo C, one font, no video/animation, one-screen RFQ form | Restyle v3 in place |
| 2026-11-02 | Minimal variant v2: added hero photo, key figures, "Як замовити" steps, segment photos, production photo, sticky header with CTA, mobile section nav | Owner asked for a few more elements; all figures come from existing copy (15+ років, 2 заводи, 2 год, catalog count) | Video/ticker from v3 |
| 2026-11-02 | Minimal variant v3: UX/UI audit fixes (control contrast 3:1, 44 px targets, aria errors, no dead links, no fake RFQ number, product dialog in two columns, sticky CTAs, full footer, OG tags) | Audit by ux-ui-designer agent; Viber/Telegram, EN switch, ЄДРПОУ and privacy link wait for client data | Keep v2 as is |
| 2026-11-02 | Minimal variant: audit items 1, 2, 4, 7, 8, 16–20 approved by Valeriia and done | Back closes the product card; form gets file + reply channel back (texts promised them); photos WebP 400/800 with srcset (mobile first load 1.0 MB → 0.25 MB); Onest self-hosted; filter reset + filters in URL; tenders linked from dealers and footer | Original JPGs stay in studio-v3 |
