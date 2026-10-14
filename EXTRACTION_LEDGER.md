# Karabo Nexus Group — Extraction Ledger

**Deliverable A** · Status: draft for founder review · Content phase only (no repo build, no logos)

## Source manifest (all claims traceable here)

| Field | Value |
|---|---|
| Live source | https://karabokeontse-png.github.io/Portfolio/ |
| Source repository | https://github.com/karabokeontse-png/Portfolio (public, verified HTTP 200) |
| Pages audited | index.html, design.html, digitization.html, software.html, experience.html, qualifications.html, pricing.html |
| Audit method | Direct fetch of all 7 pages; static HTML + inline `<style>` and `<script>` parsed |
| Audit date | 2026-10-14 |
| Boundary | Source repo read-only. Not modified, renamed, or redeployed. |

> Note: this ledger was produced from the live source, not from any prior agent's summary. Any claim below without a source location is marked per §6.

---

## 0. Source structure (control reference)

Nav (identical across pages): Home · About · Services · Design · Digitization · Development · Experience · Qualifications · Pricing · Contact.
Global tagline: **"Systems that scale. Creativity that lands."**
Marquee strip: `Software Development ◆ Graphic Design ◆ ICT & Audit ◆ Web & Branding`

---

## 1. Corporate / global (→ KNG footer, contact)

| Item | Source | Verified wording | Status |
|---|---|---|---|
| Email | index/design/software/pricing `mailto:` | `karabokeontse@gmail.com` | Verified |
| Phone / WhatsApp | index contact; digitization & pricing `wa.me` | `+267 7294 7916` · `wa.me/26772947916` | Verified |
| LinkedIn | index contact | `linkedin.com/in/tetelo-karabo-keontse-89tt89` | Verified — **excluded from corporate site** per founder decision; replaced by founder portfolio link |
| Footer (source) | index `<footer>` | "Tetelo Karabo Keontse · Software Development · Graphic Design · Digitization · ICT Systems & Audit" | Verified — **personal; do not migrate** |
| Public counters | index `.stat` `data-count` | `6+` Years of Experience · `4` Government Institutions · `100%` Audit Readiness Achieved | Verified (from data attrs) |

---

## 2. TeloNexus Labs — verified offerings

| Item | Source | Verified wording / value | Price (BWP) | Destination |
|---|---|---|---|---|
| Offer summary | index #services | "Software Development by quote — Websites, automation, integrations & system support" | by quote | Labs |
| Website — Landing | pricing | 1 page, single page, contact / WhatsApp, launch-ready | 2,500 | Labs |
| Website — Basic business | pricing | 3–5 pages, small business / NGO presence, mobile-first | 4,500 | Labs |
| Website — Standard business | pricing | 6–10 pages, multi-page, forms, blog/services, basic SEO | 7,000 | Labs |
| Website — Corporate | pricing | 10–20 pages, editorial multi-page, sector pages | 10,000 | Labs |
| Website — Custom/enterprise | pricing | 20+ pages, custom layouts, portals (from) | 15,000 | Labs |
| Web App — Simple MVP | pricing | public site + login, 1–3 modules, single dashboard, 1 role | 10,000 | Labs |
| Web App — Medium | pricing | login + roles, 3–6 modules, dashboards/reports, API/3rd-party | 20,000 | Labs |
| Web App — Advanced | pricing | RBAC, 6+ modules, real-time, online payments, multi-tenant | 35,000 | Labs |
| Ecommerce — Basic | pricing | few products, WhatsApp checkout | 6,500 | Labs |
| Ecommerce — Full | pricing | payments, inventory, full cart | 15,000 | Labs |
| Skills | index #skills | Java / C# / SQL · PowerShell Automation · System Integration & APIs · Database Design & Admin | — | Labs |
| Case study | index featured | "CMC Africa — Corporate Website … 17 pages" | — | Labs (see Unresolved) |
| Apps / teaser | software `.apps-section` | "Mobile Application · In Progress" (see §7) | — | Labs (IP-protected) |

**Classification rule applied:** all coded website work → Labs, including landing pages (per directive §4.1).

---

## 3. TeloNexus Studio — verified offerings

| Item | Source | Variant | Price (BWP) | Destination |
|---|---|---|---|---|
| Offer summary | index #services | "Graphic Design from P150 — Logos, flyers, menus, cards, social media & brand packages" | from 150 | Studio |
| Logo | pricing | Typography (wordmark) | 250 | Studio |
| Logo | pricing | Illustrated (custom icon/symbol) | 350 | Studio |
| Logo | pricing | 3D (dimensional, premium) | 450 | Studio |
| Business Card | pricing | Standard (clean professional) | 200 | Studio |
| Business Card | pricing | Premium (foil / specialty) | 300 | Studio |
| Letterhead | pricing | Basic (branded header) | 150 | Studio |
| Letterhead | pricing | Premium (footer & layout) | 250 | Studio |
| Receipt / Payslip | pricing | Standard template | 300 | Studio |
| Receipt / Payslip | pricing | Premium branded layout | 500 | Studio |
| Flyer / Poster | pricing | Basic A5–A6 | 150 | Studio |
| Flyer / Poster | pricing | Standard A4 | 250 | Studio |
| Flyer / Poster | pricing | Premium custom illustrated | 400 | Studio |
| Social Media Graphic | pricing | Standard (template) | 100 | Studio |
| Social Media Graphic | pricing | Custom illustration | 200 | Studio |
| Menu | pricing | Standard (food/beverage layout) | 300 | Studio |
| Menu | pricing | Custom illustrated | 500 | Studio |
| Gallery categories | design | Logos · Flyers & Posters · Business Cards · Documents · Packages · Social Media · Menus | — | Studio |
| Gallery names (sample) | design | Molepolole Festival, D-Phet Brand Mark, RAD Services, Initial-Letter Logo, Fast-Food Ad, Veggie Party, Fashion District | — | Studio (IP: client work — verify publication rights) |

### 3b. Digitization (→ Studio per directive §4.2)

| Item | Source | Verified wording | Price (BWP) | Destination |
|---|---|---|---|---|
| Offer summary | index #services | "Digitization from P80 — Clean copies, restoration & vector rebuilds of your art" | from 80 | Studio |
| Clean Copy | pricing | flat digitize, tidy hi-res image | 80 | Studio |
| Retouch / enhance | pricing | remove stains, scratches, fix light | 150 | Studio |
| Restoration | pricing | repair damaged/aged originals | 250 | Studio |
| Vector rebuild | pricing | trace into scalable vector, logo-ready | 300 | Studio |
| Workflow | digitization | 3 steps: Send it over → I digitize it → You get the files | — | Studio |

---

## 4. TeloNexus Advisory — verified offerings

| Item | Source | Verified wording | Price | Destination |
|---|---|---|---|---|
| Offer summary | index #services | "ICT & Audit — Network admin, data protection compliance & internal audit" | by quote | Advisory |
| Published rate | pricing | "ICT & Audit — BWP 3,000 / day — Systems support, data protection compliance and internal audits — backed by years of hands-on IT operations" | 3,000/day | Advisory |
| Skills | index #skills | IT Audit · Data Protection Compliance · Role-Based Access Control · Disaster Recovery & Backup | — | Advisory |
| Section tags | index #about | `ERP STABILITY / DATA PROTECTION / INTERNAL AUDIT` | — | Advisory |
| Experience claim | index #about | "over six years keeping mission-critical government systems running" | — | Advisory (see Unresolved) |

**Constraint applied:** no service added beyond those explicitly advertised (directive §4.3).

---

## 5. TeloNexus Print — verified offerings

| Item | Source | Verified wording | Price / Terms | Destination |
|---|---|---|---|---|
| Product | index featured (Amazon) | "My Alphabet Dot-to-Dot & Coloring Book" | £5 (Amazon UK) | Print |
| Description | index featured | "100+ connect-the-dots and coloring pages from my other publishing venture" | — | Print |
| Purchase link | index featured | https://www.amazon.co.uk/dp/B0G4F7DC29 | — | Print |
| Other print services | — | **None advertised in source** | — | none |

---

## 6. Commercial rules (global — verify each before publishing)

| Rule | Source | Verified wording | Scope limit (do not generalize) | Status |
|---|---|---|---|---|
| Deposit | pricing | "A non-refundable 25% upfront deposit confirms your order… balance due on delivery. Larger projects (websites & apps) may use milestone payments." | Deposit wording applies to design/package; sites/apps "may" use milestones | Verification target |
| Bundle discount | pricing | 2 items 10% · 3 items 15% · 4+ items 20% | Applies to design items only; **explicitly excludes** web dev, mobile apps, ICT | Verification target |
| Digitization batch | pricing | 5+ pieces 10% off · 10+ pieces 15% off the digitization items | Digitization items only | Verification target |
| Currency support | pricing switcher | BWP, USD, EUR, GBP, ZAR, NAD, ZMW, ZiG, NGN, KES, CNY, INR, JPY, CAD, AUD, CHF (**16**) | — | Verification target |
| Refund terms | pricing | Only the 25% deposit is stated non-refundable; no broader refund policy published | — | Verified (limited) |
| Checkout | pricing | Interactive "Build your package" + "Continue to checkout" | **Directive §7: replace with static tables; do not reproduce checkout** | Excluded from build |

---

## 7. "Coming Soon" teaser (IP-protected — directive §5)

| Field | Source | Verified wording |
|---|---|---|
| Heading | software `.apps-section` | "Applications" |
| Flags | software | "In development" · "Upcoming ⭐" |
| Status | software | "Mobile Application · In Progress" |
| Name | software | "Project name hidden until launch" |
| Body | software | "A native Android application currently in active development. More details once it ships." |
| Tags | software | "Kotlin Android" |

**Redaction rules:** must not reveal the product name, roadmap, screenshots, architecture, repo links, or package identifiers. Preserve as a single homepage element, **not** a fifth division.

---

## 8. Exclusions (do NOT migrate — directive §8)

| Item | Source | Reason |
|---|---|---|
| "Available for full-time roles, freelance software development, and design engagements" | index #about | Job-seeking |
| "Hiring, freelance software development, or a fresh design project — I'm ready" | index #contact | Job-seeking |
| Owner name as site identity (Tetelo Karabo Keontse) | all footers/titles | Personal; founder bio deferred to future About |
| Experience timeline | experience.html | Personal history (may inform Advisory credibility — see Unresolved) |
| Qualifications page (26 credentials, 62 badge images) | qualifications.html | Personal; not a corporate service page |
| Package-builder JS + checkout | pricing | Directive §7 |
| Client gallery items | design | **Verify publication rights/consent before reuse** |

---

## 9. Founder resolutions (2026-10-14) — formerly unresolved

| # | Item | Resolution |
|---|---|---|
| 1 | **CMC Africa** | **RESOLVED.** Live site found and verified: `https://karabokeontse-png.github.io/CMC-website-/` — "CMC Africa \| Crisis Management Consulting Africa", served from repo `karabokeontse-png/CMC-website-`, 199,926 bytes, 17 sector sub-pages. Linked from `labs.html`. |
| 2 | **Experience claims** | **RESOLVED — AUTHORISED.** Founder directed that the portfolio's operating record be published as group capability: `6+` years, `4` government institutions, `100%` audit readiness. Published on `index.html` (group proof strip) and `advisory.html` (Capability track record). |
| 3 | **Legal entity name** | **RESOLVED — name confirmed as "Karabo Nexus Group".** Registration suffix (e.g. "Pty Ltd") is still withheld: no registration evidence has been supplied, so the footer remains the neutral `© 2026 Karabo Nexus Group. All rights reserved.` Upgradeable once registration is evidenced. |
| 4 | **Founder information** | **RESOLVED.** Founder is **not** published as a corporate contact. Instead, the third contact card links to the founder's existing portfolio: `https://karabokeontse-png.github.io/Portfolio/`. The personal LinkedIn was removed from the corporate site. |
| 5 | **Print scope** | Source supports exactly one product (the book). `print.html` carries a "Future titles" heading with an explicit no-speculation rule and no invented titles. |
| 6 | **Client gallery works** | **STILL OPEN.** Identifiable client work (Molepolole Festival, restaurants, RAD Services, D-Phet) is **not** published on the corporate site pending rights confirmation. No assets migrated. |
| 7 | **Price currency** | **STILL OPEN — low risk.** All prices carried verbatim from source and undated. Founder to confirm before launch. |
| 8 | **Repository creation** | **BLOCKED on credentials.** See `VALIDATION.md` §Blockers. The `karabo-nexus-group` remote repo cannot be created with the token available in this environment. |

---

## 10. Design tokens — verified against live stylesheet (directive §10)

The directive's 4-token palette is **confirmed but incomplete**. Live `:root` (dark) contains 12 tokens:

| Token | Hex | Directive had it? |
|---|---|---|
| `--bg` | `#0F1621` | ✅ |
| `--bg-2` | `#1E293B` | ➕ added |
| `--bg-3` | `#24324A` | ➕ added |
| `--ink` | `#F3F4F6` | ➕ added |
| `--ink-dim` | `#A8B2C1` | ➕ added |
| `--border` | `#2A3A54` | ➕ added |
| `--bronze` | `#C15563` | ✅ |
| `--bronze-deep` | `#8E1D2C` | ✅ |
| `--bronze-soft` | `rgba(193,85,99,0.30)` | ➕ added |
| `--steel` | `#A8B2C1` | ➕ added |
| `--nav-bg` | gradient | ➕ added |
| `--accent-text` | `#E08C99` | ✅ (proposed) |

Fonts (verified via Google Fonts link): **Fraunces** (opsz 9..144; 300–600), **Inter** (300–600), **IBM Plex Mono** (400/500).
Contrast (computed): `--bronze` on `--bg` = 4.10:1 (large/UI only). `--bronze-deep` on `--bg` = 2.04:1 (fills only). `--accent-text #E08C99` = 7.24:1 (AA/AAA small text).
