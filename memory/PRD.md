# Pratik Patil — AI PM Portfolio Redesign

## Original Problem
"Improve the UI/UX for this website and make it most attractive such that I will get interview calls"
Target: AI Product Manager roles
Constraints: Single static HTML file, keep all existing content as-is.

## Design Direction: "AI PM Field Manual"
Editorial / publication aesthetic — opposite of generic AI portfolios.
- **Palette**: Warm cream paper (#f3ebdc) · Deep ink (#161311) · Vermillion (#ec3a14) · Highlighter yellow · Moss · Plum · Sky
- **Typography**: Fraunces variable serif (italic display) + Geist sans + Geist Mono + Instrument Serif (lede)
- **Distinctive elements**: Custom dot+ring cursor · rotating "Available For Hire" stamp · highlighter marker on "replace work" · oversized italic display headlines · magnetic hover buttons · newspaper masthead frame · noise paper texture · section §-numbering · italic pull quote with corner mark · bento projects grid · animated SVG ping on map · marquee ticker · dark contact closer.

## Implemented (Jan 2026)
- Single HTML file: `/app/portfolio.html` (~50 KB, fully self-contained)
- All original content preserved verbatim — only visual layer redesigned
- Sections: Hero (with stamp + marquee), About (with pull quote), Skills (hover-flip cells), Framework (4-layer diagram + tools glossary), Three Dots (stealth banner + impact bar + ticker + interactive map), Projects (bento grid w/ featured dark card + YouTube wide card), Case Studies (3 cards w/ dark KPI sidebars + arch flow), Experience (tabbed, animated), Contact (dark closer w/ availability pill), Footer
- Custom cursor (auto-disabled on touch devices) · scroll reveal · magnetic buttons · active-section nav highlight · pulsing availability dot · animated map ping
- Fully responsive: 1440 / tablet / 390 mobile

## Test IDs Added
nav-*, hero-cta-*, project-card-1..5, case-study-1..3, exp-tab-*, contact-*, td-chip-*, yt-live-link

## How to Use
- Local preview: open `/app/portfolio.html` in any browser
- Host: drop the single file on Netlify / Vercel / GitHub Pages / personal server — no build step
- Edit content: all text is inline; just open and edit in any editor

## Future / Backlog
- P1: Add resume PDF download button
- P1: Add LinkedIn / GitHub icons in masthead + contact
- P2: Add 1-2 testimonial quotes (boosts credibility for recruiter screens)
- P2: Optional dark-mode toggle (cream → ink-bg)
- P3: Add OG image + favicon for link previews on LinkedIn/Twitter shares
