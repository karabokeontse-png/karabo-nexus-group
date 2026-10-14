# Validation Report

**Deliverable E** · Karabo Nexus Group website · Date: 2026-10-14

Status: **structural build complete — awaiting founder approval before launch or logo phase.**

---

## Checklist results

| # | Check | Result | Evidence |
|---|---|---|---|
| 1 | Original portfolio not modified | **PASS** | All 7 source pages re-fetched post-build; byte sizes identical to pre-build audit (index 303,323 · design 29,171 · digitization 17,390 · software 19,201 · experience 14,493 · qualifications 50,910 · pricing 51,608). Source repo untouched. |
| 2 | New repository separate | **PASS (local)** | Built at `projects/karabo-nexus-group`, its own git repo. No file from the source portfolio was copied, moved, or altered. |
| 3 | All four divisions present | **PASS** | `labs.html`, `studio.html`, `advisory.html`, `print.html` — all exist, each with own title, meta description, `<h1>`, and `aria-current="page"`. |
| 4 | All public claims source-verified | **PASS** | 31 BWP prices on the built pages cross-checked programmatically against source HTML — **0 unverified**. Every service name/scope traced in `EXTRACTION_LEDGER.md` §2–§5. |
| 5 | Commercial terms accurate | **PASS** | Deposit 25%, bundle 10/15/20% (design only), digitization batch 10%/15% — each published with its documented scope limit and exclusions. No discount or deposit generalised beyond source. |
| 6 | Teaser reveals no protected info | **PASS** | Grep sweep for `vantedge`, `com.vantedge`, roadmap, architecture, screenshots, repository links — **0 hits**. Teaser preserves only source wording; renders as a homepage element, not a fifth division. |
| 7 | No personal job-seeking content migrated | **PASS** | Grep sweep for "full-time roles", "hire", "I'm ready", personal bio, experience timeline, qualifications page, badge images — **0 hits**. |
| 8 | Legal footer makes no unsupported claim | **PASS** | Grep sweep for "Pty Ltd", "trading as", "registration no", "company number" — **0 hits**. Footer reads `© 2026 Karabo Nexus Group. All rights reserved.` |
| 9 | No logos generated before approval | **PASS** | Text wordmark only (`Karabo Nexus Group` / `TeloNexus` lockup in type). No SVG, no logomark, no image assets. |
| 10 | Checkout/package-builder removed | **PASS** | Replaced with static pricing tables. Max inline JS per page = 614 bytes (theme toggle + mobile nav only); homepage 1,126 bytes (adds scroll reveal). No payment, cart, or checkout code. |
| 11 | Accessible contrast | **PASS** | All 16 text/background pairs validated in both themes. Small text (eyebrows, links, secondary copy) uses `--accent-text #E08C99` at **7.24:1** on navy — the palette fix that makes small text AA where source bronze was 4.10:1. Large hero emphasis uses bronze at 4.10:1 (AA-large). |
| 12 | Mobile-first & responsive | **PASS** | Single-column below 760px, hamburger nav with `aria-expanded`, horizontal-scroll tables for pricing, viewport meta on all pages. |
| 13 | Keyboard navigation | **PASS** | Skip link on all pages, visible `:focus-visible` ring, semantic `nav`/`main`/`table` with `scope` attributes, buttons are real `<button>` elements. |
| 14 | Fast & minimal dependencies | **PASS** | Zero JS libraries. Zero CSS frameworks. Single shared stylesheet. Only external request is Google Fonts (verified design requirement). |
| 15 | Page titles & descriptions | **PASS** | Unique `<title>` and `meta description` on all 5 pages. |

---

## What was deliberately NOT done

- **No GitHub repository created remotely.** The credentials in this environment are scoped to an unrelated repository and cannot create `karabokeontse-png/karabo-nexus-group`. A local git repo is initialised and uncommitted, ready to push once an account with access is available.
- **No logo or logomark.** Per directive §10, structural phase only. Text wordmark used.
- **No client gallery images.** Design work featuring identifiable clients (Molepolole Festival, restaurants, RAD Services, etc.) requires publication-rights confirmation before reuse. Not migrated.
- **No founder biography page.** Deferred per directive §8.
- **No legal entity name in footer.** Neutral wording until registration is evidenced.

---

## Founder decisions applied (2026-10-14)

| Decision | Applied |
|---|---|
| Legal entity name is **Karabo Nexus Group** | Footer confirmed as `© 2026 Karabo Nexus Group. All rights reserved.` Registration suffix (`Pty Ltd`) **withheld** — no registration evidence supplied, so the claim is not made. |
| CMC link lives in the founder's repos | Verified `https://karabokeontse-png.github.io/CMC-website-/` (CMC Africa \| Crisis Management Consulting Africa). Linked from `labs.html` with a "View the live site" button. |
| Portfolio experience = company capability | Published as group capability on `index.html` (proof strip: 6+ / 4 / 100%) and `advisory.html` (Capability track record). Founder-authorised. |
| Founder info = link to portfolio | Third contact card now links `https://karabokeontse-png.github.io/Portfolio/`. Personal LinkedIn **removed** from the corporate site. |

## Self-containment

All five pages were rewritten to be **fully self-contained**: CSS inlined into each file, Google Fonts `<link>` and `preconnect` removed, font stacks carry system fallbacks (`'Fraunces', Georgia, serif` · `'Inter', system-ui, sans-serif` · `'IBM Plex Mono', ui-monospace, monospace`). Remaining external URLs are anchor `href`s only (WhatsApp, Amazon, CMC, founder portfolio) — no resource loads.

Render verification (`POST /render`, all 5 pages):

| Page | Verdict | Console errors | Horizontal overflow |
|---|---|---|---|
| `index.html` | **pass** | 0 | none (442px viewport) |
| `labs.html` | **pass** | 0 | none |
| `studio.html` | **pass** | 0 | none |
| `advisory.html` | **pass** | 0 | none |
| `print.html` | **pass** | 0 | none |

---

## Blockers before launch

1. **GitHub repo** — remote repo still needs to be created. See below.
2. **Registration suffix** — if Karabo Nexus Group is registered, supply the registration number and the footer upgrades to the full corporate line.
3. **Client works rights** — Molepolole Festival, restaurants, RAD Services, D-Phet. Not published. Confirm whether you want them on the corporate site at all.
4. **Price recency** — all pricing copied verbatim from source and undated; confirm current before launch.
5. **Fonts** — pages are self-contained and currently fall back to system fonts. If you want Fraunces/Inter/IBM Plex Mono rendered, either self-host the woff2 files or re-add the Google Fonts link at deploy time.