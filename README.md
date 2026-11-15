# VivahKit — Plan Your Indian Wedding, Calmly

One calm place for your Indian wedding: countdown, ceremonies, budget, guests, vendors and the checklist that gets you to the mandap. Single self-contained HTML file — no backend, no signup, everything saved in your browser's localStorage only.

**Live:** https://abhiramunni.github.io/vivahkit/

## What it does

- **Countdown card** — couple's names, wedding date and total budget in one editable card; days-to-go, budget spent, guests confirmed and vendors booked all update live from it.
- **The ceremonies** — six events (Haldi, Mehndi, Sangeet, The Wedding, Reception, Vidaai) as a snap-scroll rail, each with its own mini-checklist, progress bar and status pill that flips to Done by itself.
- **The budget** — 8 categories (Venue, Catering, Decor & Flowers, Photography & Video, Outfits, Jewellery, Guest Travel & Stay, Misc & Buffer) with an SVG donut, per-category budget vs spent bars, over-budget flags, log-spend and set-budget forms.
- **The guest list** — search, side filters (bride / groom / both) and RSVP filters; tap an RSVP pill to cycle Invited → Confirmed → Declined; expected-heads count is what the caterer needs. Add guests with headcount and notes.
- **The vendors** — 8 vendor types with status (To find / Shortlisted / Booked — advance paid), editable name and quoted cost.
- **The master checklist** — 22 tasks across 5 phases (12–6 months out → on the day) with a progress ring.
- **Good to know** — 6 plain-language guides: venue booking, catering maths, photography contracts, guest-list budgeting, the 10% buffer rule, and post-wedding paperwork.
- **Extras** — copy-ready wedding summary, remove-sample-data, two-tap erase-all, 3-step onboarding tour, 4-second cinematic intro with tap-to-skip (quick version on return visits).

## Design

Warm editorial palette (ivory paper, espresso ink, bronze / amber / gold / terracotta), Fraunces + Inter, AI-generated warm-editorial photography (golden-hour mandap hero, invitation flat-lay) with slow Ken Burns drift, inline SVG icons only, no emojis.

## Sample data

Ships with a clearly marked sample wedding (Asha & Rohan, 21 Feb 2027, ₹12,00,000 budget, 12 guests, 8 vendors). Use **Remove sample data** to start from a clean slate — your own entries are never touched by it.

## Tech

- One file: `index.html` (~618 KB, incl. two embedded photos)
- No build step, no dependencies at runtime; Google Fonts (Fraunces + Inter) via CDN
- QA: 43/43 headless jsdom assertions, `node --check` clean, zero uncaught JS errors (see `qa-test.js`)

## Privacy

Everything lives in localStorage on your device. Nothing is uploaded anywhere.
