# Boppart Digital — Full Documentation

> Last updated: 2026-06-17

## Live URL
- Production: **https://boppartdigital.ch**
- Vercel preview: https://boppart-digital-site-t77b.vercel.app

## Repository
- GitHub: https://github.com/michaelaboppart/-boppart-digital-site
- Branch: `main`
- Auto-deploy: via Vercel (commit-triggered)

## Pages (5 Premium Pages)

| Page | File | Purpose |
|---|---|---|
| Landing | `boppartdigital.html` + `index.html` | Hero, Anchor, Portfolio teaser, Services teaser, Contact form |
| About | `boppart_about.html` | Hero, Letter, Numbers (24/5/4), Story with portrait, Timeline, Principles |
| Studio (Services) | `boppart_studio.html` | 2 Services (Finance AI Lead + Platform Studio), Trust & Governance, Process, FAQ, CTA |
| Portfolio | `boppart_portfolio.html` | 5 ventures (AIXXII, CasaFin, CHICCA, DreamNest, LOVMINDA) |
| Imprint | `boppart_imprint.html` | Legal: Imprint, Privacy, Terms, Copyright |

## Services Positioning

**01 — AI for Finance Teams** (LEAD)
- ERP-native: SAP ECC, ABACUS, Dynamics NAV, Business Central
- Swiss Payroll (SwissDec, AHV, BVG, Quellensteuer)
- Pricing: CHF 8k Discovery · CHF 25-40k Pilot · CHF 80-120k Stack Migration · CHF 100-150k/yr Annual Partnership · CHF 6k Payroll Audit
- ROI lines: 5-10x cheaper than Big 4

**02 — Platform Studio**
- 4 weeks to 4 months custom builds
- MVP Platform · Full Platform · Enterprise
- Custom scope, transparent pricing on inquiry

## Trust & Governance (6 Commitments)
1. Swiss & EU Data Residency (Infomaniak, Swisscom, AWS Frankfurt)
2. No Training Data Reuse (NDA day 1)
3. GDPR & Swiss DSG Compliant
4. EU AI Act Ready
5. GoBD-aware (DE) / OR-aware (CH)
6. Professional Liability Insurance

## Tech Stack
- HTML/CSS (vanilla, no framework)
- Fonts: Inter Tight (display), Fraunces (italic accents), Inter (body)
- Hosting: Vercel (Pro plan)
- Domain: boppartdigital.ch (Infomaniak, NS via Infomaniak)
- Email: welcome@boppartdigital.ch (Infomaniak Mail)
- Form backend: formsubmit.co → welcome@boppartdigital.ch

## Email Setup
- All forms route to: `welcome@boppartdigital.ch`
- Form provider: formsubmit.co
- One-time activation: submit test form → click activation link in confirmation email

## Bilingual Setup
- DE/EN toggle on Landing + Studio
- localStorage persistence (key: `bopplang`)
- data-en / data-de attributes on all key text
- data-en-html / data-de-html for HTML content

## Mobile Setup (added 2026-06-17)
- Hamburger menu on `<768px`
- Slide-overlay with all nav links
- body `overflow-x: hidden` to prevent horizontal scroll

## File Structure

```
/
├── index.html              # = boppartdigital.html (mirror)
├── boppartdigital.html     # Landing
├── boppart_about.html      # About
├── boppart_studio.html     # Services
├── boppart_portfolio.html  # Portfolio
├── boppart_imprint.html    # Legal
├── boppart-logo.png        # Logo
├── michaela-portrait.jpg   # Portrait (Aragon)
├── hero-zuerich.jpg        # Landing hero
├── about-hero.jpg          # About hero
├── bridge-vascodagama.jpg  # Studio hero
├── zurich-prime.jpg        # Portfolio hero
├── venture-aixxii.png      # Venture screenshots
├── venture-casafin.png
├── venture-chicca.png
├── venture-dreamnest.png
├── .gitignore
├── README.md
└── DOCUMENTATION.md (this file)
```

## DNS Records (Infomaniak)

| Type | Source | Target |
|---|---|---|
| NS | @ | ns11.infomaniak.ch |
| NS | @ | ns12.infomaniak.ch |
| A | @ | 76.76.21.21 (Vercel) |
| CNAME | www | cname.vercel-dns.com |

## Marketing Assets (External)

Located in: `C:\Users\micha\OneDrive\Dokumente\Claude\Projects\Belimed AR report\`
- `LINKEDIN_POST_FINANCE_AI.md` — 3 LinkedIn post variants (DE/EN/Reel-Hook)
- `OUTREACH_TEMPLATE_FINANCE_AI.md` — 4 outreach templates + Discovery Call script + 30-day tracker

## Day 1 Build Stats (2026-06-17)

| Metric | Count |
|---|---|
| HTML pages built | 5 |
| Lines of code | ~3,500 |
| Git commits | 30+ |
| Tasks completed | 25 |
| Real outreach templates | 4 |
| LinkedIn posts ready | 3 variants |

## Brand Voice

- **Tone**: Premium, operator-built, no hype
- **References**: Pentagram, Stripe Press, McKinsey-Boutique (NOT tech-Twitter)
- **Audience**: DACH CFOs, Finance Managers, Treuhänder, Family Offices
- **Differentiator**: 24-year finance operator who actually ships AI

## What Never Goes on Site (Hard Rules)

- ❌ Belimed (private employer, never named publicly)
- ❌ Furniture business (private Möbelgeschäft)
- ❌ Specific Belimed insider data (DSO numbers, Andreja name, etc.)
- ❌ DreamNest insider info (Burgundy Château, etc.)
- ❌ Trading details

## Founder

- **Michaela Boppart** — Founder
- LinkedIn: https://linkedin.com/in/michaela-boppart-21653552
- Boppart Digital LinkedIn: https://www.linkedin.com/company/108615759/
- Instagram: https://instagram.com/boppartdigital

## License

© 2026 Boppart Digital · Zürich, Switzerland. All rights reserved.
